# Cloud Spanner Emulator - ARM Releases

This repository provides **ARM-compatible binaries** for the [Google Cloud Spanner Emulator](https://github.com/GoogleCloudPlatform/cloud-spanner-emulator).

> **Disclaimer:** This is an **unofficial distribution**. The official Google Cloud Spanner Emulator currently does **not provide pre-built ARM binaries** for download. Official binaries are available only for amd64 architecture and can be found at [https://storage.googleapis.com/cloud-spanner-emulator](https://storage.googleapis.com/cloud-spanner-emulator), but ARM builds are **not included** for most versions.

## Project Goals

- Distribute **Cloud Spanner Emulator ARM binaries** for modern platforms (Linux and macOS ARM64).
- Match the latest [upstream emulator releases](https://github.com/GoogleCloudPlatform/cloud-spanner-emulator/releases) as closely as possible.
- Fill the gap for ARM users who cannot find official binaries for their architecture.

## Background

The official [Cloud Spanner Emulator binaries](https://storage.googleapis.com/cloud-spanner-emulator) released by Google currently **support only the amd64/x86_64 architecture**. ARM builds (such as those needed for Apple Silicon, Raspberry Pi, or cloud ARM servers) are missing from most releases. This repository exists to provide up-to-date ARM binaries for these environments.

## Releases

- You can find the **latest ARM builds** in this repository's [Releases page](https://github.com/[your-username]/cloud-spanner-emulator-arm/releases).
- Each release corresponds to a version of the upstream emulator.
- This repository will focus on making available the **most current versions**.

## Usage

1. Download the binary for your platform from the [Releases](https://github.com/[your-username]/cloud-spanner-emulator-arm/releases) page.
2. Follow the official [Cloud Spanner Emulator setup documentation](https://cloud.google.com/spanner/docs/emulator), substituting the emulator binary you downloaded.

> **Note:** These binaries are built from the official source code, only differing in being compiled for ARM architectures. All features and limitations are inherited from the upstream project.

## License

This repository distributes binaries built from the upstream [Cloud Spanner Emulator](https://github.com/GoogleCloudPlatform/cloud-spanner-emulator), licensed under the [Apache 2.0 License](https://github.com/GoogleCloudPlatform/cloud-spanner-emulator/blob/main/LICENSE).
