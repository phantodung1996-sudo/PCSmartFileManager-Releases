# PCSmartFileManager

PCSmartFileManager is a Windows file-management and file-analysis application.

Latest release: **v1.5.0 — Access UX**.

Primary supported release target: **Windows 11 x64**. Windows 10 remains best-effort and is not release-certified.

Downloads are available from this repository's [GitHub Releases page](https://github.com/phantodung1996-sudo/PCSmartFileManager-Releases/releases).

## v1.5.0 — Access UX

[Release notes, downloads and SHA-256 checksums](https://github.com/phantodung1996-sudo/PCSmartFileManager-Releases/releases/tag/v1.5.0)

- Search/Favorites File and EXE Open use the target's containing folder as the initial working directory. Home Quick Access uses the same Favorite Open behavior.
- File and Folder Favorites support display names without changing their physical names or contents.
- Home Quick Access shows at most ten Favorites total. Home Recent displays ten explicitly opened files from a history capped at fifty; it currently has no reopen action.
- Preview, Reveal and Folder navigation do not record File Open history. Sidebar Gần đây retains Inventory/ModifiedDate semantics. The former Thêm vị trí quét button is removed.
- Additive schema v5 preserves existing application data. Read the packaged update guide and make a consistent backup before first use; reinstalling v1.4.0 does not downgrade schema v5.

Release build: zero warnings/errors; full regression 2951/2951 PASS. Clean Setup, portable, upgrade/reinstall, pre-upgrade-v4 backup/restore and populated exact-package feature smoke passed. All 418 product payload files match by path, size and SHA-256.

Setup is **UNSIGNED**. Native physical input and 125% DPI were not executed; no human visual acceptance is claimed. Harmless executable checks do not cover every external application. Backup/restore covers pre-upgrade v4 data only. No new populated Preview Focus/wheel/A-B acceptance is claimed. The release notes retain these and inherited limitations.

## Canonical private-source provenance

| Release | Private source tag | Private source commit |
| --- | --- | --- |
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
