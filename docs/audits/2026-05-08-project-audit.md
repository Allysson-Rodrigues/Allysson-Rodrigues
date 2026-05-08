# Allysson-Rodrigues Project Audit

Date: 2026-05-08

## Scope

Profile repository, Git posture, GitHub Actions workflow posture, remote pull requests, Dependabot alerts, and local working tree state.

## Score

Overall score: 8.0 / 10

The repository is simple and locally clean. The generated snake workflow was retired because it required a non-main publication branch and mutable third-party workflow actions for a cosmetic artifact.

## Evidence

- Local branch: `chore/ALL-184-retire-snake-output` during remediation.
- Local working tree: clean before this audit report was added.
- Local branches: `main` only.
- Remote branches observed before remediation: `main`, `output`.
- Open GitHub PRs: none observed.
- Open Dependabot alerts: none observed.
- Workflow inventory before remediation: `.github/workflows/snake.yml`.
- Remediation: `.github/workflows/snake.yml` removed.

## Validation

- No package manifest was present, so no npm/pnpm validation applies.
- GitHub was inspected before remediation.
- No package-specific test suite exists for this profile-only repository.

## Findings

1. The remote `output` branch prevented a strict remote "main-only" posture.
2. The retired workflow used version-tag-pinned actions (`Platane/snk/svg-only@v3`, `crazy-max/ghaction-github-pages@v3.1.0`) instead of immutable SHA pins.
3. The retired workflow used the default `GITHUB_TOKEN` for generated asset publication.

## Resolution Status

The generated snake workflow was removed to eliminate the non-essential publication path. After this PR is merged, the remote `output` branch can be deleted so the repository keeps only `main`.
