# WarpShare 📲🍏

## An Open-sourced AirDrop

![License](https://img.shields.io/badge/license-Apache%202.0-green)
![Android Compatible](https://img.shields.io/badge/Android-yes-blue)

Welcome to WarpShare, an Android app to transfer files using AirDrop from your Android device to Apple devices. This project is a fork of [vinint/MoKee-WarpShare](https://github.com/vinint/MoKee-WarpShare), modified by moseoridev to work on the latest version of Android. The app also has the potential to transfer files between Android devices that have this app installed, although this feature has not been extensively tested.

## Features 🌟

- Uses AirDrop's original AWDL protocol for faster file transfers between Apple and non-Apple devices.
- Set AirDrop visibility setting to "Everyone" on your Apple device for seamless file transfer.
- One-way transfer from Android to Apple devices.
- Supports file transfer with approximately 4.2 GB maximum size.
- Open source and licensed under Apache 2.0.

## Limitations ⚠️

- Only possible to send files from Android devices to Apple devices.
- Cannot transfer files larger than ~4.2 GB due to the CPIO format limitation.
- Code quality might be suboptimal, especially concerning Android permissions, as the developer has little experience in Java or Android development.

## Usage 📚

1. Install the WarpShare app on your Android device.
2. Ensure that AirDrop visibility is set to "Everyone" on your Apple device.
3. Open the app on your Android device and select the files you'd like to transfer.
4. Confirm the transfer on your Apple device, and the files will be transferred!

## Contributions & Issues 💡

Any issues or contributions to the project are greatly appreciated! Please open an issue on GitHub or submit a Pull Request to help improve the app.

## License 📄

This project is licensed under the Apache License 2.0 – see the [LICENSE](LICENSE) file for details.

## Acknowledgments 🙏

- A big thank you to [vinint](https://github.com/vinint) for the original [MoKee-WarpShare](https://github.com/vinint/MoKee-WarpShare) project.
- AirDrop is a trademark of Apple Inc.
