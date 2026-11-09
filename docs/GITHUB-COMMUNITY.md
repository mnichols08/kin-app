# GitHub community files

**Status:** current as of v1.6.0.

## What Kin provides

At the repository root: the [README](../README.md), the MIT [LICENSE](../LICENSE),
[CONTRIBUTING](../CONTRIBUTING.md), a [Code of Conduct](../CODE_OF_CONDUCT.md)
(Contributor Covenant 2.1 with Kin's privacy expectations added),
[SECURITY](../SECURITY.md), [SUPPORT](../SUPPORT.md) and the
[CHANGELOG](../CHANGELOG.md). Under `.github/`: issue forms for a bug report,
a feature proposal and self-hosting help, a `config.yml` with contact links,
a pull request template and the
[Kin verification](../.github/workflows/kin-verification.yml) workflow.

Together these are what GitHub's *Community Standards* profile looks for in a
repository, plus a changelog.

## History

Until November 2026 Kin lived in the ZTM Build Fest repository
(`mnichols08/ZTM-Build-Fest`) under `projects/kin/`. GitHub only reads
community files from a repository's root, so the forms and templates were not
offered automatically there. Since the move to `mnichols08/kin-app` they are.

## Still to check

- Private vulnerability reporting is a repository setting: enable it on
  `mnichols08/kin-app` (Settings → Code security) so the first option in
  [SECURITY](../SECURITY.md) works.
- The contact links in `.github/ISSUE_TEMPLATE/config.yml` must be absolute
  URLs; they point at `main`.
