# AutoBuild-OpenWrt
[![LICENSE](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat&logo=github&label=LICENSE)](https://github.com/vasewa/AutoBuild-OpenWrt/blob/master/LICENSE)
![GitHub Stars](https://img.shields.io/github/stars/vasewa/AutoBuild-OpenWrt.svg?style=flat&logo=appveyor&label=Stars&logo=github)
![GitHub Forks](https://img.shields.io/github/forks/vasewa/AutoBuild-OpenWrt.svg?style=flat&logo=appveyor&label=Forks&logo=github)
![GitHub last commit](https://img.shields.io/github/last-commit/vasewa/AutoBuild-OpenWrt?label=Latest%20Commit&logo=github)
[![Contact Me](https://img.shields.io/badge/Contact-telegram-blue)](https://t.me/vasewa)

- Build OpenWrt firware [Lean's OpenWrt](https://github.com/coolsnowwolf/lede) using GitHub Actions.
- Forked from [esirplayground/AutoBuild-OpenWrt](https://github.com/esirplayground/AutoBuild-OpenWrt)
- Hereby thank eSir for his amazing job!

## Usage

1. Sign up for [GitHub Actions](https://github.com/features/actions/signup)
2. Fork [this GitHub repository](https://github.com/vasewa/AutoBuild-OpenWrt)
3. Click [.github/workflows] folder on the top of repo and you could see few workflow files, Each for one particular architecture(device).
4. Edit the workflow file you desire，uncomment push section 3 lines together and submit the commit.(Other 2 methods wait you to discover)
5. Edit the Wiki page. Once you saved the page, the build starts automatically. Progress can be viewed on the Actions page.
6. When the build is complete, click the `Artifacts` button in the upper right corner of the Actions page to download the binaries.
7. Default Web Admin IP: `192.168.50.1`, username `root`，password `password`
8. For other details please visit [eSir's Y2B Channel (in Chinese) | 视频教程](https://www.youtube.com/c/esirplayground)
