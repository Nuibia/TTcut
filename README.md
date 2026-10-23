<p align="center"><img src="public/ttcut-icon.png" alt="TTcut" width="88"></p>

<h1 align="center">TTcut</h1>

<p align="center"><strong>把时间留给打球，把剪辑交给 TTcut。</strong></p>

<p align="center">自动整理乒乓球比赛回合，留下每一个值得回看的好球。</p>

<p align="center"><strong>简体中文</strong> · <a href="README.zh-Hant.md">繁體中文</a> · <a href="README.en.md">English</a></p>

<p align="center">
  <a href="https://github.com/WeiyePlayer/TTcut/releases/latest">Windows / macOS 下载</a> ·
  <a href="https://github.com/WeiyePlayer/TTcut-Mobile-Releases/releases">Android 下载</a> ·
  <a href="https://apps.apple.com/us/app/pingduo/id6818115664">iPhone / iPad 下载</a>
</p>

![TTcut 自定义剪辑：回合列表、视频预览、比分牌与时间轴](docs/images/readme/desktop-editor-zh.png)

<p align="center"><sub>桌面版真实应用截图，预览画面使用演示素材。</sub></p>

## 从整场比赛，到你的精彩集锦

TTcut 是面向乒乓球爱好者的视频剪辑工具。导入比赛视频，识别有效回合，再选择全部保留、筛选精彩或逐段精修，省去反复拖动长视频寻找好球的时间。

| 想做什么 | TTcut 可以帮你 |
| --- | --- |
| 快速整理比赛 | 自动识别回合，支持自动球桌标定，也可手动调整球桌四角。 |
| 只留下精彩 | 导出全部回合，或按板数、时长筛选精彩回合，筛选方式随识别模式而定。 |
| 精修每个片段 | 在回合列表与时间轴中预览、勾选、拆分、新增和删除片段，调整起止位置，支持撤销与重做。 |
| 给比赛加比分 | 设置选手姓名、局分与比分，选择比分牌样式和位置，并随视频一起导出。 |
| 一次整理多场 | 批量添加视频、分析与剪辑，也可将多个视频的剪辑结果合并成片。 |
| 继续编辑或分享 | 导出合并视频、每回合的独立视频，或可导入 Premiere 的剪辑文件。 |

**视频留在自己的电脑里。** 桌面版无需登录，视频与分析记录保存在本机，不上传视频。安装完成后可以离线分析、预览和剪辑；从“历史剪辑”再次打开已分析的视频，可继续整理，无需重复分析。

## 下载与安装

| 设备 | 下载入口 | 选择哪个 |
| --- | --- | --- |
| Windows x64 | [下载桌面版](https://github.com/WeiyePlayer/TTcut/releases/latest) | 选择文件名以 `x64-Setup.exe` 结尾的完整安装包。 |
| macOS 15 及以上 · Apple Silicon | [下载 Mac 版](https://github.com/WeiyePlayer/TTcut/releases/latest) | 推荐 DMG，打开后将 TTcut 拖入“应用程序”；也提供 ZIP。不支持 Intel Mac。 |
| Android | [前往安卓下载页面](https://github.com/WeiyePlayer/TTcut-Mobile-Releases/releases) | 按发布页说明下载并安装 APK。 |
| iPhone / iPad | [在 App Store 获取乒乓拍档](https://apps.apple.com/us/app/pingduo/id6818115664) | iOS / iPadOS 18 及以上，功能介绍见下方。 |

桌面完整安装包已包含运行所需资源，安装后即可使用。版本更新内容请查看[发布说明](https://github.com/WeiyePlayer/TTcut/releases/latest)。

<details>
<summary>macOS 首次打开提示</summary>

当前 Mac 版尚未公证，首次打开可能被系统拦截。确认安装包来自本仓库后，可在“系统设置 → 隐私与安全性”中允许打开。具体安装提示以对应版本的发布说明为准。

</details>

## 三步完成一段剪辑

1. **导入比赛。** 选择或拖入 MP4 / MOV 视频，使用自动标定；需要修正时，手动点选球桌四角。
2. **选择回合。** 分析完成后，选择“所有回合”“精彩回合”或“自定义”。自定义模式可逐段预览并调整边界，也可添加比分牌。
3. **导出成片。** 设置回合前后的保留时间，开始剪辑。完成后直接播放，或打开输出文件夹。

建议使用机位稳定、球桌完整可见的视频。自动识别结果可以手动修正；请保留原始视频，方便日后继续编辑。

## iPhone 与 iPad：乒乓拍档

![尽管记录每一拍，其余交给乒乓拍档](docs/images/readme/ios-header-zh.png)

想在手机或平板上整理比赛，推荐使用 **乒乓拍档（PingDuo）**。从照片中选择视频，就能在设备上整理回合、回看比赛、制作集锦。

<table>
  <tr>
    <th>整理片库</th>
    <th>滑动回看</th>
    <th>制作集锦</th>
  </tr>
  <tr>
    <td><img src="docs/images/readme/ios-library-zh.png" alt="乒乓拍档片库：管理比赛视频" width="260"></td>
    <td><img src="docs/images/readme/ios-hero-zh.png" alt="乒乓拍档英雄页：滑动浏览回合" width="260"></td>
    <td><img src="docs/images/readme/ios-basket-zh.png" alt="乒乓拍档集锦：调整回合顺序并导出" width="260"></td>
  </tr>
</table>

- **导入与识别：** 从照片选择比赛视频，在设备上分析；球追踪可标定球桌四角，动作识别无需标定。
- **回合回看：** 在“英雄”中上下滑动浏览，收藏好球、排除不需要的回合，调整片段起止位置。
- **集锦剪辑：** 将多个视频里的回合加入集锦、调整顺序、预览并导出，也可一键导出单个视频的全部或精彩回合。
- **球友与时光机：** 记录球友的球拍配置和便签，关联比赛视频，按球友或日期重温比赛。
- **本地保存：** 视频、识别结果和编辑记录保存在设备上，不上传这些资料。

每台设备可完成 **5 次免费分析**，失败或取消不扣次数；需要更多分析时，可在应用内了解会员。价格与订阅信息以 App Store 购买页面为准；下载可用性以 Apple ID 所在地区为准。

**[在 App Store 获取乒乓拍档 →](https://apps.apple.com/us/app/pingduo/id6818115664)**

## 交流与反馈

遇到问题或有新功能建议，欢迎[提交反馈](https://github.com/WeiyePlayer/TTcut/issues)，也可以添加作者微信：**m2924931661**。反馈时附上系统、应用版本和操作步骤，有助于更快定位问题。

## 打赏支持

如果 TTcut 帮你省下了剪辑时间，欢迎通过爱发电支持作者，让这个小工具继续打磨。每一份支持，都是继续维护和改进的动力。谢谢！

<p align="center"><a href="https://ifdian.net/a/weiye"><img src="docs/images/readme/support-afdian.svg" alt="在爱发电支持 TTcut" width="208" height="48"></a></p>

<p align="center"><a href="https://ifdian.net/a/weiye">爱发电 · weiye</a></p>
