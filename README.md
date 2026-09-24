<!--
  Copyright (c) Meta Platforms, Inc. and affiliates.

  This source code is licensed under the MIT license found in the
  LICENSE file in the root directory of this source tree.
-->

# Meta VR OS SDK Samples

This repository is a collection of code samples that demonstrate the capabilities of the **Meta VR OS SDK** for Meta Quest devices.

The Meta VR OS SDK consists of three complementary packages:

- **[Meta VR OS JSDK](https://developers.meta.com/horizon/documentation/android-apps/metavr-os-jsdk/)** — Java APIs for Horizon OS features, akin to the Android SDK. Distributed as the `metavr-os-jsdk` Android library (AAR).
- **[Meta VR OS NSDK](https://developers.meta.com/horizon/documentation/native/metavr-os-nsdk/metavr-os-nsdk-overview/)** — Native C APIs for Horizon OS features, akin to the Android NDK. Distributed as the `metavr-os-nsdk` Android library (AAR) with Prefab-packaged headers and shared libraries.
- **Meta VR OS Utility Library** — A "static" library that provides a more convenient and compatible API for common Horizon OS features, akin to AndroidX/Jetpack.

## Repository Layout

| Directory | Contents |
|---|---|
| `JavaSoftwareDevelopmentKitSamples/` | Single-API samples for the Meta VR OS JSDK (Java/Kotlin). |
| `NativeSoftwareDevelopmentKitSamples/` | Single-API samples for the Meta VR OS NSDK (native C/C++). |
| `UtilityLibrarySamples/` | Single-API samples for the Meta VR OS Utility Library. |
| `MixedSdkSamples/` | End-to-end samples that combine multiple Meta VR OS SDK packages. |

## Requirements

To build and run these samples, you will need:

- A Meta Quest device running Horizon OS.
- Mac, Linux, or Windows host with:
  - [Android Studio](https://developer.android.com/studio) (latest stable release recommended).
  - Android SDK platform-tools (`adb`, `fastboot`).
  - [Native samples only] Android NDK (installed via Android Studio's SDK Manager), which is required by the `metavr-os-nsdk` Prefab package.
  - JDK 17 or newer.

Additional per-sample requirements (specific Horizon OS feature flags, system permissions, device builds) are documented in each sample's own `README.md`.

## Getting Started

Find a sample you want to try, then follow the instructions in that sample's `README.md`.

## Reporting Issues

File a [new issue](https://github.com/meta-quest/Meta-VR-OS-SDK-Samples/issues/new/choose) — the bug report and sample request templates will guide you.

## Contributing

We welcome contributions. See [CONTRIBUTING.md](CONTRIBUTING.md) for the full process.

This repository is a public mirror of an internal Meta source-of-truth repository. Your contribution will appear in this repository once the internal review lands. The project Code of Conduct is [here](CODE_OF_CONDUCT.md).

## License

The Meta VR OS SDK samples are licensed under the **MIT License**, as found in the [LICENSE](LICENSE) file.
