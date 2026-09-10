# lynis

[中文版本](./README.cn.md)

Lynis - Security auditing tool for Linux, macOS, and UNIX-based systems. Assists with compliance testing (HIPAA/ISO27001/PCI DSS) and system hardening. Agentless, and installation optional.

![lynis](https://repo.x-cmd.io/lynis.svg)

## Install

```sh
x install lynis
```

## Code insight

Total: **20,945** lines of code across **73** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Sh | 20,896 | 7,196 | 1,552 | 63 |
| Yaml | 49 | 0 | 0 | 1 |
| Markdown | 0 | 3,326 | 863 | 8 |
| RPMSpecfile | 0 | 22 | 0 | 1 |

## OpenSSF Scorecard

Overall score: **5.3 / 10**

Lowest-scoring checks:

- **Packaging** (-1/10) — packaging workflow not detected
- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **Fuzzing** (0/10) — project is not fuzzed

## Source

- **Upstream**: <https://github.com/CISOfy/lynis>
- **Homepage**: <https://cisofy.com/lynis/>
- **License**: GPL-3.0

## Release

- **Latest**: `3.1.7` (2026-06-25)
- **Last commit**: 2026-09-09

## Popularity

- **Stars**: 16,311 · **Forks**: 1,630 · **Open issues**: 958 · **Contributors**: 252

## Totals (cumulative)

- **Releases**: 66 · **Merged PRs**: 617 · **Open PRs**: 48 · **Closed issues**: 787 · **Open issues**: 171 · **Commits**: 3934

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-11 | 0 | 1 | 2 | 1 | 1 | 4 |
| last60d | 2026-07-12 | 0 | 3 | 4 | 2 | 3 | 9 |
| 90d | 2026-06-12 | 1 | 5 | 7 | 4 | 5 | 12 |
| last180d | 2026-03-14 | 1 | 9 | 16 | 8 | 12 | 17 |
| 360d | 2025-09-15 | 2 | 23 | 28 | 20 | 34 | 34 |
| last720d | 2024-09-20 | 6 | 59 | 46 | 44 | 69 | 223 |

## Distribution status

Reported by **94** distros on [repology.org](https://repology.org/project/lynis). **22** are ✅ on the latest upstream release, **62** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
| Debian unstable | `3.1.6` | ⚠️ outdated |
| Debian 14 | `3.1.6` | ⚠️ outdated |
| Debian 13 | `3.1.4` | ⚠️ outdated |
| Ubuntu 26.04 LTS | `3.1.6` | ⚠️ outdated |
| Ubuntu 24.04 LTS | `3.0.9` | ⚠️ outdated |
| Arch | `3.1.7` | ✅ latest |
| Homebrew | `3.1.7` | ✅ latest |
| Fedora rawhide | `3.1.7` | ✅ latest |
| Nix unstable | `3.1.7` | ✅ latest |
| Void | `3.1.7` | ✅ latest |
| Alpine edge | `3.1.6` | ⚠️ outdated |
| openSUSE Tumbleweed | `3.1.7` | ✅ latest |

## Improve this data

Install metadata for lynis lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `lynis` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/lynis.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260910.yml` · 2026-09-10T20:47:40Z._
