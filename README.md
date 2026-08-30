<div id="vscodium-logo" align="center">
    <br />
    <img src="./icons/stable/codium_cnl.svg" alt="VSCodium Logo" width="200"/>
    <h1>myspace</h1>
    <h3>C++ designed fork of VSCodium</h3>
</div>

<div id="badges" align="center">

[![current release](https://img.shields.io/github/release/ntcd-lol/myspace.svg)](https://github.com/ntcd-lol/myspace/releases)
[![license](https://img.shields.io/github/license/ntcd-lol/myspace.svg)](https://github.com/ntcd-lol/myspace/blob/master/LICENSE)

</div>

**This is a fork. This is a repository fork of VSCodium - that NOT a fork of VSCode.**

> [!WARNING]
> myspace - unstable project, but you can say about [bugs today!](https://github.com/ntcd-lol/myspace/issues)

## Table of Contents

- [Download/Install](#download-install)
- [Build](#build)
- [Supported Platforms](#supported-platforms)
- [Previously Supported Platforms](#previously-supported-platforms)

## <a id="download-install"></a>Download/Install

:tada: :tada:
Download latest release here:
[stable](https://github.com/ntcd-lol/myspace/releases/latest) or
[insiders](https://github.com/ntcd-lol/myspace/releases?q=prerelease:true)
:tada: :tada:

[More info / helpful tips are here.](https://github.com/ntcd-lol/myspace/blob/master/docs/index.md)

## <a id="build"></a>Build

Build instructions can be found [here](https://github.com/ntcd-lol/myspace/blob/master/docs/howto-build.md)

### Documentation

For more information on getting all the telemetry disabled, tips for migrating from Visual Studio Code to VSCodium and more, have a look at [the Docs page](https://github.com/ntcd-lol/myspace/blob/master/docs/index.md) page.

### Troubleshooting

If you have any issue, please check [the Troubleshooting page](https://github.com/ntcd-lol/myspace/blob/master/docs/troubleshooting.md) or the existing issues.

### Extensions and the Marketplace

According to the Visual Studio Marketplace [Terms of Use](https://aka.ms/vsmarketplace-ToU), _you may only install and use Marketplace Offerings with Visual Studio Products and Services._ For this reason, VSCodium uses [open-vsx.org](https://open-vsx.org/), an open source registry for Visual Studio Code extensions. See the [Extensions + Marketplace](https://github.com/VSCodium/vscodium/blob/master/docs/index.md#extensions-marketplace) section on the Docs page for more details.

Please note that some Visual Studio Code extensions have licenses that restrict their use to the official Visual Studio Code builds and therefore do not work with VSCodium. See [this note](https://github.com/VSCodium/vscodium/blob/master/docs/extensions.md#proprietary-debugging-tools) on the Docs page for what's been found so far and possible workarounds.

### How are the VSCodium binaries built?

If you would like to see the commands we run to build `vscode` into VSCodium binaries, have a look at the workflow files in `.github/workflows` for Windows, GNU/Linux and macOS. These build files call all the other scripts in the repo. If you find something that doesn't make sense, feel free to ask about it [on Gitter](https://gitter.im/VSCodium/Lobby).

The builds are run every day, but exit early if there isn't a new release from Microsoft.

## <a id="supported-platforms"></a>Supported Platforms

The minimal version is limited by the core component Electron, you may want to check its [platform prerequisites](https://www.electronjs.org/docs/latest/development/build-instructions-gn#platform-prerequisites).

- [x] macOS (`zip`, `dmg`) macOS 12 or newer x64
- [x] macOS (`zip`, `dmg`) macOS 12 or newer arm64
- [x] GNU/Linux x64 (`deb`, `rpm`, `AppImage`, `snap`, `tar.gz`)
- [x] GNU/Linux arm64 (`deb`, `rpm`, `snap`, `tar.gz`)
- [x] GNU/Linux riscv64 (`tar.gz`)
- [x] GNU/Linux loong64 (`tar.gz`)
- [x] GNU/Linux ppc64le (`tar.gz`)
- [x] Windows 10 / Server 2012 R2 or newer x64
- [x] Windows 10 / Server 2012 R2 or newer arm64

## <a id="previously-supported-platforms"></a>Previously Supported Platforms

- GNU/Linux armhf:
  - Latest available: [v1.121.03429](https://github.com/VSCodium/vscodium/releases/tag/1.121.03429).
  - Breaking point: `node-v24`.

## <a id="thanks"></a>Special thanks

<table>
  <tr>
    <td><a href="https://github.com/jaredreich" target="_blank">@jaredreich</a></td>
    <td>for the logo</td>
  </tr>
  <tr>
    <td><a href="https://github.com/PalinuroSec" target="_blank">@PalinuroSec</a></td>
    <td>for CDN and domain name</td>
  </tr>
  <tr>
    <td><a href="https://www.macstadium.com" target="_blank"><img src="https://images.prismic.io/macstadium/66fbce64-707e-41f3-b547-241908884716_MacStadium_Logo.png?w=128&q=75" width="128" height="49" alt="MacStadium logo" /></a></td>
    <td>for providing a Mac mini M1</td>
  </tr>
  <tr>
    <td><a href="https://github.com/daiyam" target="_blank">@daiyam</a></td>
    <td>for macOS certificate</td>
  </tr>
  <tr>
    <td><a href="https://signpath.org/" target="_blank"><img src="https://avatars.githubusercontent.com/u/34448643" height="30" alt="SignPath logo" /></a></td>
    <td>free code signing on Windows provided by <a href="https://signpath.io/" target="_blank">SignPath.io</a>, certificate by <a href="https://signpath.org/" target="_blank">SignPath Foundation</a></td>
  </tr>
</table>

## <a id="license"></a>License

[MIT](https://github.com/VSCodium/vscodium/blob/master/LICENSE)
