## expressvpn-share

## 目录结构

```
├── ExpressVPN
│   └── 20210124
│       ├── expressvpn_android_10.0.0.10000044.46337_release_website.apk
│       ├── expressvpn_centos_3.4.2.4-1.x86_64.rpm
│       └── expressvpn_windows_10.0.9.2_release.exe
├── 备用梯子
│   └── 20210124
│       ├── 老王VPN
│       │   └── com.sticktoit_60_apps.evozi.com.apk
│       └── 蓝灯
│           └── org.getlantern.lantern_356063892_apps.evozi.com.apk
└── 测速工具
    └── 20210124
        └── org.zwanoo.android.speedtest_119186_apps.evozi.com.apk
```

- `测速工具`：存放用于 Android 平台测试 ExpressVPN 连接速度的工具（SpeedTest）
- `ExpressVPN`：存放 ExpressVPN 官方最新的各平台的安装包（如 Android、Windows、CentOS）
- `备用梯子`：存放 Android 平台备用的免费 VPN 工具，主要作用是用于在线更新 ExpressVPN，因为 ExpressVPN 旧版本在未来一段的时间内可能不可用

## ExpressVPN 更新方式

- `ExpressVPN 官网`：从 [ExpressVPN 官网](https://www.expressvpn.com/)下载各个平台最新的安装包即可
- `Google Play 商店`：当国家/地区显示为中国时，在 Google Play 内是无法搜索到 ExpressVPN 应用的，必须手动切换到其他国家/地区（如美国）才能搜索到
- `Github 仓库`：当前的 Github 仓库会时不时 Push 最新的 ExpressVPN 安装包，当所有梯子都不可用时，可以直接从此 Github 仓库下载最新版的安装包

PS：上述前两种方法都依赖于有可用梯子的时候才能使用，而第三种方法不需要梯子，但不能保证安装包是最新的，毕竟是手动更新的

## ExpressVPN 使用说明

- ExpressVPN 官网默认是需要使用梯子才能访问
- 当无法连接 ExpressVPN 的服务器时，请尝试不同的 ExpressVPN 节点
- 建议优先使用速度较快的 lightway_udp 协议，其次才是 tcp、udp 协议
- ExpressVPN 支持在 Windows、Mac、Android 平台上使用隧道分流功能（即国内外流量分流）
- ExpressVPN 支持同一个账号最多 5 个设备同时连接，当第 6 个设备需要连接时，需要等某个设备断开连接后才能连接上
- Windows、Android 平台直接输入 ExpressVPN 的账号/密码就可以使用，而 Linux 平台则需要输入 ExpressVPN 的激活码

## ExpressVPN 官方教程

- [ExpressVPN 官网](https://www.expressvpn.com)
- [Android 平台使用说明](https://www.expressvpn.com/vpn-software/vpn-android)
- [Windows 平台设置隧道分流](https://www.expressvpn.com/support/troubleshooting/split-tunneling-desktop/#how-to-use-vpn-split-tunneling-windows)

## ExpressVPN 测速说明

- [SpeedTest 的 网页版](https://www.speedtest.net/)
- SpeedTest 的 Android 版直接从当前仓库下载安装即可
- ExpressVPN 的 Windows 版内置了测速功能，可以很方便地测试各个 VPN 节点的连接速度

## ExpressVPN 其他使用教程

- [Web 浏览器直接下载 Google 商店的 APP](https://apps.evozi.com/apk-downloader)
- [Google Play 无限制切换国家/地区教程（亲测可用）](https://blog.ichr.me/post/bypass-google-play-region-restrictions/)

## 更新日志

- 2021/01/24 更新
- 2021/04/06 更新
- 2021/07/04 更新
- 2021/09/03 更新
- 2021/11/01 更新
