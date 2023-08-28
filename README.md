# WarpShare 📲🍏

## An Open-source AirDrop Alternative

![License](https://img.shields.io/badge/license-Apache%202.0-green)
![Android Compatible](https://img.shields.io/badge/Android-yes-blue)
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fmoseoridev%2FWarpShare&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)
[![IzzyOnDroid](https://img.shields.io/endpoint?url=https://apt.izzysoft.de/fdroid/api/v1/shield/com.moseoridev.warpshare)](https://apt.izzysoft.de/fdroid/index/apk/com.moseoridev.warpshare/)

WarpShare is an Android app that enables file transfer using AirDrop-like functionality from your Android device to
Mac. This project is a fork of [vinint/MoKee-WarpShare](https://github.com/vinint/MoKee-WarpShare), with
modifications by [moseoridev](https://github.com/moseoridev) to make it compatible with the latest version of Android.

## Features 🌟

- Utilizes the AWDL protocol, the same technology found in AirDrop, for faster file transfers between Mac and
  non-Apple devices.
- Easily transfer files by setting the AirDrop visibility to "Everyone" on your Mac.
- Sends files from Android devices to Mac with a maximum size of approximately 4.2 GB.
- Open-source and released under the Apache 2.0 License.

## Limitations ⚠️

- File transfer is limited to Android-to-Mac only.
- The maximum file size is ~4.2 GB due to limitations in the CPIO format.
- Code quality might be suboptimal due to the [developer](https://github.com/moseoridev)'s limited experience in Java or
  Android development.
- There are reports of it not working on several models of Android phones, but it's hard to troubleshoot the error unless I have one of those phones.
- You may receive a warning from Google Play Protect because the developer is not verified. Rest assured, the app is
  safe to use.

## Usage 📚

1. Install the WarpShare app on your Android device.
2. Set AirDrop visibility to "Everyone" on your Mac.
3. Launch the WarpShare app on your Android device, choose the files to transfer, and initiate the process.
4. Confirm the transfer on your Apple device and watch the magic happen!

## Download 📥

You can download the WarpShare app by visiting the "Releases" section in the GitHub repository. Click on the latest
release and download the .apk file for Android installation.

[Download from GitHub Releases](https://github.com/moseoridev/WarpShare/releases)

or you can use IzzyOnDroid:

[![IzzyOnDroid](https://gitlab.com/IzzyOnDroid/repo/-/raw/master/assets/IzzyOnDroid.png)](https://apt.izzysoft.de/fdroid/index/apk/com.moseoridev.warpshare/)

## Contributing & Issues 💡

Your input is valued! Feel free to submit a GitHub issue or pull request if you have suggestions or encounter problems
with the app.

## License 📄

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

## Acknowledgments 🙏

- A huge thank you to [vinint](https://github.com/vinint) for creating the
  original [MoKee-WarpShare](https://github.com/vinint/MoKee-WarpShare) project.
- AirDrop is a trademark of Apple Inc.
