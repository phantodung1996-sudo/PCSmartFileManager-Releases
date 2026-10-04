# PCSmartFileManager

PCSmartFileManager is a Windows file-management and file-analysis application.

Latest release: **v1.6.0 — Duplicate review and Document Profiles**.

Primary supported release target: **Windows 11 x64**. Windows 10 remains best-effort and is not release-certified.

Downloads are available from this repository's [GitHub Releases page](https://github.com/phantodung1996-sudo/PCSmartFileManager-Releases/releases).

## v1.6.0 — Duplicate review and Document Profiles

[Release notes, downloads and SHA-256 checksums](https://github.com/phantodung1996-sudo/PCSmartFileManager-Releases/releases/tag/v1.6.0)

- **Duplicate review:** work from completed indexed snapshots across one or more selected scopes. Metadata candidates remain distinct from explicit SHA-256 verification. The UI supports scope-aware member identity, A/B comparison, summary fields, filtering, paging and JSON/CSV report export. No duplicate deletion or physical source-file cleanup is performed.
- **Document Profiles:** free-form logical category trees support root/child nodes, rename, reorder, reparent, archive/restore, document links, display names, labels, notes, filtering, structure templates and attachment-progress reporting. Existing Preview/Open/Reveal/Favorites actions remain available; logical profile changes do not rename or modify source files.
- **Access UX retained:** Favorites display names, mixed File/Folder Quick Access, explicit-successful-open Recent history and executable-parent working-directory behavior from v1.5 remain in force. Sidebar Gần đây retains its separate Inventory/ModifiedDate meaning.
- **Additive schema v6:** migration from v1.5 schema v5 preserves prior Inventory/history, duplicate observations, Profiles/members, Favorites/aliases, Recent and settings while adding Profile structure/metadata/template data. Read the packaged update guide and take a consistent pre-upgrade backup before first use.

Release build: zero warnings/errors. The accepted product-source regression remains **3065/3065 PASS**. The final helper validation ran **303/303 PASS**. Clean Setup, portable, public v1.5 upgrade, same-version reinstall, portable existing-data use, pre-upgrade-v5 backup/restore, populated exact-package Feature acceptance and fresh-process Restart/preservation all passed. All **428/428** product payload files match by path, size and SHA-256.

Setup is **UNSIGNED**. Native physical input and 125% DPI were not executed; no human visual acceptance is claimed. Actual guest evidence used 144 DPI / 150%. Duplicate multi-scope acceptance used generated folders on one guest volume rather than two physical drives. Harmless executable checks do not prove every third-party application. The release notes retain these and inherited limitations.

## Canonical private-source provenance

| Release | Private source tag | Private source commit |
| --- | --- | --- |
| v1.6.0 | `v1.6.0` | `8c75364bbbb55ab89ee9452525833c244a042d87` |
| v1.5.0 | `v1.5.0` | `1aa4583c1ad45c9e43a476cb988e90495b897f81` |
| v1.4.0 | `v1.4.0` | `39e0fb650393009999b5002274fb1c3fe951bf2b` |
| v1.3.0 | `v1.3.0` | `27ce0983e80bb062436ac329ec889e3c75c345fa` |
| v1.2.0 | `v1.2.0` | `e8759bc0e0463395666e4a469c7d378be121e96a` |
| v1.1.0 | `v1.1.0` | `2ffab3b5cb6331b37091e0a83fa98c83e6619c07` |
| v1.0.0 | `v1.0.0` | `3bd6fa09fb6baac084d344fe0105bfb3a7786ff8` |

Private source repository: `phantodung1996-sudo/PCSmartFileManager`.

The application source is not publicly distributed by this repository. Public release tags in this repository point to distribution-metadata commits, not to private application-source commits. GitHub-generated Source code archives therefore contain only public distribution metadata, not the product binaries or private source.

## Distribution model

Releases use manual/offline **Setup + Portable ZIP** delivery. The automatic updater is not part of the active release roadmap.

## Installer signing

**UNSIGNED**

Windows may show an unknown/unverified publisher warning. Do not disable or bypass Windows Security/SmartScreen to run the installer.
