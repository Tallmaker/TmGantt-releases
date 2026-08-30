# TmGantt releases

This repository hosts public downloads of TmGantt, a Gantt visualization for
Qlik Cloud Analytics. The source code is maintained separately.

## Download

Open the [Releases](https://github.com/Tallmaker/TmGantt-releases/releases)
page and choose the version you need. Download the asset named
`tmgantt-<version>.zip`.

Do not use GitHub's automatic "Source code" archives. Those archives contain
only this distribution repository, not the Qlik extension.

Every release includes:

- `tmgantt-<version>.zip`, the extension archive to upload to Qlik Cloud
- `tmgantt-<version>.sha256`, the SHA-256 checksum for that archive

On macOS, verify a download from the directory containing both files:

```sh
shasum -a 256 -c tmgantt-<version>.sha256
```

## Install

Upload the versioned ZIP as an extension in the target Qlik Cloud tenant, then
add TmGantt to a sheet. Bind at least one dimension and two measures, choose a
Row level, and assign the Activity start and Activity end roles.
