# Merge log

Scroll down for the original README.md!

Base revision: daae327e864e169e6795d1ac313a87b32360c21e

|Pull Request|Commit|Title|Author|Merged?|
|----|----|----|----|----|
|[1](https://github.com/yuzu-emu/yuzu-canary/pull/1)|[a8dfe54](https://github.com/yuzu-emu/yuzu-canary/pull/1/files/)|Canary Base|[chris062689](https://github.com/chris062689)|Yes|
|[2851](https://github.com/yuzu-emu/yuzu/pull/2851)|[6b997c8](https://github.com/yuzu-emu/yuzu/pull/2851/files/)|renderer_opengl: Fix sRGB blits|[ReinUsesLisp](https://github.com/ReinUsesLisp)|Yes|
|[2846](https://github.com/yuzu-emu/yuzu/pull/2846)|[17a9b01](https://github.com/yuzu-emu/yuzu/pull/2846/files/)|gl_shader_decompiler: Avoid writing output attribute when unimplemented|[ReinUsesLisp](https://github.com/ReinUsesLisp)|Yes|
|[2824](https://github.com/yuzu-emu/yuzu/pull/2824)|[5f309b8](https://github.com/yuzu-emu/yuzu/pull/2824/files/)|Revert "Revert #2466" and stub FirmwareCall 4|[ReinUsesLisp](https://github.com/ReinUsesLisp)|Yes|
|[2784](https://github.com/yuzu-emu/yuzu/pull/2784)|[0f7b813](https://github.com/yuzu-emu/yuzu/pull/2784/files/)|shader_ir: Implement shared memory|[ReinUsesLisp](https://github.com/ReinUsesLisp)|Yes|
|[2710](https://github.com/yuzu-emu/yuzu/pull/2710)|[abb2c5f](https://github.com/yuzu-emu/yuzu/pull/2710/files/)|am/kernel: Fix various bugs related to applet signalling and software keyboard|[DarkLordZach](https://github.com/DarkLordZach)|Yes|
|[2576](https://github.com/yuzu-emu/yuzu/pull/2576)|[b957a48](https://github.com/yuzu-emu/yuzu/pull/2576/files/)|nsp: Fix various errors with loading and processing of extracted NSPs|[DarkLordZach](https://github.com/DarkLordZach)|Yes|
|[2574](https://github.com/yuzu-emu/yuzu/pull/2574)|[425cdf9](https://github.com/yuzu-emu/yuzu/pull/2574/files/)|arm_dynarmic: Check if jit is nullptr when preparing reschedule|[DarkLordZach](https://github.com/DarkLordZach)|Yes|
|[2542](https://github.com/yuzu-emu/yuzu/pull/2542)|[7aeb676](https://github.com/yuzu-emu/yuzu/pull/2542/files/)|lbl: Implement brightness and backlight services|[DarkLordZach](https://github.com/DarkLordZach)|Yes|
|[2365](https://github.com/yuzu-emu/yuzu/pull/2365)|[4fe8093](https://github.com/yuzu-emu/yuzu/pull/2365/files/)|Workaround to Mutex Corruption|[FernandoS27](https://github.com/FernandoS27)|Yes|
|[1703](https://github.com/yuzu-emu/yuzu/pull/1703)|[09d8109](https://github.com/yuzu-emu/yuzu/pull/1703/files/)|nvdrv: Stub nvdec/vic ioctls to bypass nvdec movies|[DarkLordZach](https://github.com/DarkLordZach)|Yes|
|[1340](https://github.com/yuzu-emu/yuzu/pull/1340)|[c359c00](https://github.com/yuzu-emu/yuzu/pull/1340/files/)|Implement a Better Ignore Assert|[FernandoS27](https://github.com/FernandoS27)|Yes|
|[1012](https://github.com/yuzu-emu/yuzu/pull/1012)|[7b98ac7](https://github.com/yuzu-emu/yuzu/pull/1012/files/)|filesystem: Create directory if it dosen't exist on open|[DarkLordZach](https://github.com/DarkLordZach)|Yes|


End of merge log. You can find the original README.md below the break.

------

yuzu emulator
=============
[![Travis CI Build Status](https://travis-ci.org/yuzu-emu/yuzu.svg?branch=master)](https://travis-ci.org/yuzu-emu/yuzu)
[![AppVeyor CI Build Status](https://ci.appveyor.com/api/projects/status/77k97svb2usreu68?svg=true)](https://ci.appveyor.com/project/bunnei/yuzu)
[![Azure Mainline CI Build Status](https://dev.azure.com/yuzu-emu/yuzu/_apis/build/status/yuzu%20mainline?branchName=master)](https://dev.azure.com/yuzu-emu/yuzu/)

yuzu is an experimental open-source emulator for the Nintendo Switch from the creators of [Citra](https://citra-emu.org/).

It is written in C++ with portability in mind, with builds actively maintained for Windows, Linux and macOS. The emulator is currently only useful for homebrew development and research purposes.

yuzu only emulates a subset of Switch hardware and therefore is generally only useful for running/debugging homebrew applications. yuzu can boot some games, to varying degrees of success.

yuzu is licensed under the GPLv2 (or any later version). Refer to the license.txt file included.

Check out our [website](https://yuzu-emu.org/)!

For development discussion, please join us on [Discord](https://discord.gg/XQV6dn9).

### Development

Most of the development happens on GitHub. It's also where [our central repository](https://github.com/yuzu-emu/yuzu) is hosted.

If you want to contribute please take a look at the [Contributor's Guide](CONTRIBUTING.md) and [Developer Information](https://github.com/yuzu-emu/yuzu/wiki/Developer-Information). You should as well contact any of the developers on Discord in order to know about the current state of the emulator.

### Building

* __Windows__: [Windows Build](https://github.com/yuzu-emu/yuzu/wiki/Building-For-Windows)
* __Linux__: [Linux Build](https://github.com/yuzu-emu/yuzu/wiki/Building-For-Linux)
* __macOS__: [macOS Build](https://github.com/yuzu-emu/yuzu/wiki/Building-for-macOS)


### Support
We happily accept monetary donations or donated games and hardware. Please see our [donations page](https://yuzu-emu.org/donate/) for more information on how you can contribute to yuzu. Any donations received will go towards things like:
* Switch consoles to explore and reverse-engineer the hardware
* Switch games for testing, reverse-engineering, and implementing new features
* Web hosting and infrastructure setup
* Software licenses (e.g. Visual Studio, IDA Pro, etc.)
* Additional hardware (e.g. GPUs as-needed to improve rendering support, other peripherals to add support for, etc.)

We also more than gladly accept used Switch consoles, preferably ones with firmware 3.0.0 or lower! If you would like to give yours away, don't hesitate to join our [Discord](https://discord.gg/VXqngT3) and talk to bunnei. You may also contact: donations@yuzu-emu.org.
