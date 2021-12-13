# Actions-ImmortalWrt-R1S-H5

[![LICENSE](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square&label=LICENSE)](https://github.com/F-T-Otaku/Actions-ImmortalWrt-R1S-H5/blob/main/LICENSE)
![GitHub Stars](https://img.shields.io/github/stars/F-T-Otaku/Actions-ImmortalWrt-R1S-H5.svg?style=flat-square&label=Stars&logo=github)
![GitHub Forks](https://img.shields.io/github/forks/F-T-Otaku/Actions-ImmortalWrt-R1S-H5.svg?style=flat-square&label=Forks&logo=github)

Build ImmortalWrt for R1S-H5 using GitHub Actions

## Usage

- Click the [Use this template](https://github.com/F-T-Otaku/Actions-ImmortalWrt-R1S-H5/generate) button to create a new repository.
- Generate `.config` files using [ImmortalWrt](https://github.com/immortalwrt/immortalwrt/tree/openwrt-18.06-k5.4) source code. ( You can change it through environment variables in the workflow file. )
- Add your own `seed.config` to `SEED` folder.
- Select `Build OpenWrt` on the Actions page.
- Click the `Run workflow` button.
- When the build is complete, click the `Artifacts` button in the upper right corner of the Actions page to download the binaries.

## Tips

- Default login address: [192.168.233.1](http://192.168.233.1), username is **root** and password is **password**.
- You can also use [immortalwrt.lan](http://immortalwrt.lan) to login.
- My version of ImmortalWrt is very simple.It only has ssrp, cpufreq, turboacc and unblockmusic.
- Stable's kernel version is 4.19 and normal's kernel version is 5.4.
- If you don't know how to generate `seed.config`, please look this page: <https://github.com/coolsnowwolf/lede/issues/2288>.

## Acknowledgments

- [ImmortalWrt](https://github.com/immortalwrt/immortalwrt/tree/openwrt-18.06-k5.4)
- [P3TERX's Actions](https://github.com/P3TERX/Actions-OpenWrt)
- [Microsoft Azure](https://azure.microsoft.com)
- [GitHub Actions](https://github.com/features/actions)
- [OpenWrt](https://github.com/openwrt/openwrt)
- [Lean's OpenWrt](https://github.com/coolsnowwolf/lede)
- [QiuSimons's YAOF](https://github.com/QiuSimons/YAOF)

## License

[MIT](https://github.com/F-T-Otaku/Actions-ImmortalWrt-R1S-H5/blob/main/LICENSE) © F-T-Otaku
