# MintPop Lane

**中文** | [English](#english)

> 官方 Claude Code，美国环境，本地运行。

MintPop Lane 提供官方 Claude 账号及订阅，配套**美国办公室固定 IP**出口，以美国企业商业信用卡支付。时区、网络与依赖已预配置，安装客户端、登录账号，挑个目录就能写代码。

- 🌐 官网：<https://lane.mintpop.ai>
- ⬇️ 下载客户端：<https://lane.mintpop.ai/#download>
- 💳 购买订阅：<https://console.lane.mintpop.ai/plans>
- ✉️ 联系我们：<https://mintpop.ai/zh/contact>

> 本仓库不含源代码，只用来介绍产品、收集问题反馈与功能建议。

## 为什么选 Lane

| 风险项 | 自行配置 / 第三方中转 | MintPop Lane |
|---|---|---|
| 网络出口 | 共享或机场 IP，多用户共用，地址频繁变动 | **美国办公室固定 IP**，出口地址恒定 |
| 支付方式 | 国内信用卡或虚拟卡，账单地址与使用地区不一致 | **美国企业商业信用卡**，账单主体与出口地区一致 |
| 使用环境 | 时区、语言、系统配置与 IP 所在地不匹配 | 时区、网络、依赖**预先配置**，与出口地区一致 |
| 服务来源 | 镜像或第三方接口，模型版本与限流不透明 | **100% 官方 Claude Code**，用量可在官方后台核验 |

## 客户端特性

- **内置终端**：首次使用自动完成安装，无需配置环境变量
- **无需密钥**：订阅授权自动接入，无需管理 API Key
- **多项目并行**：每个项目独立标签页，切换后仍在后台运行
- **零信息留存**：代码由 Claude Code 直连 Claude 官方服务，MintPop 不存储任何对话与文件内容

## 订阅

| 套餐 | 价格 | 用量规格 | 适用场景 |
|---|---|---|---|
| Standard | $40 / 月 | 1.25 倍 Pro | 单项目、常规频率的日常开发 |
| Premium | $160 / 月 | 6.25 倍 Pro（≈ 1.25 倍 Max 5x） | 高频调用、多项目并行的重度使用 |

倍数来自 Claude 官方企业版规格。价格以[官网](https://lane.mintpop.ai/#pricing)为准。

## 支持平台

| 平台 | 要求 |
|---|---|
| macOS | Apple 芯片（M 系列），macOS 12 及以上；不支持 Intel 芯片的 Mac |
| Windows | Windows 10 / 11，x64 |
| Linux | Ubuntu 22.04 及以上（`.deb`）；其他发行版用 `.AppImage` |

安装包请从[官网下载区](https://lane.mintpop.ai/#download)获取，本仓库不分发安装包。

## 反馈与支持

| 你想… | 去哪里 |
|---|---|
| 报告客户端、控制台或官网的 bug | [提交 Bug](../../issues/new?template=bug_report.yml) |
| 提功能建议 | [提交建议](../../issues/new?template=feature_request.yml) |
| 咨询用法、交流经验 | [Discussions](../../discussions) |
| 账号、订单、续费等**涉及个人信息**的问题 | [联系我们](https://mintpop.ai/zh/contact)（请勿发在公开 issue 里） |
| 报告安全漏洞 | 见 [SECURITY.md](SECURITY.md) |

> ⚠️ Issue 是公开的，**请勿**在其中粘贴账号邮箱、订单号、token、IP 地址等个人信息。

---

<a id="english"></a>

# MintPop Lane (English)

[中文](#mintpop-lane) | **English**

> Official Claude Code. US environment, runs locally.

MintPop Lane provides an official Claude account and subscription, paired with a **fixed IP at our US office** and paid with a US corporate business card. Time zone, network and dependencies are preconfigured: install the app, sign in, pick a folder and start coding.

- 🌐 Website: <https://lane.mintpop.ai/en/>
- ⬇️ Download: <https://lane.mintpop.ai/en/#download>
- 💳 Subscribe: <https://console.lane.mintpop.ai/plans>
- ✉️ Contact: <https://mintpop.ai/contact>

> This repository contains no source code. It exists to introduce the product and to collect bug reports and feature requests.

## Why Lane

| Risk | DIY setup / third-party relay | MintPop Lane |
|---|---|---|
| Network exit | Shared or proxy-pool IPs that change often | **Fixed IP at our US office** |
| Payment | Non-US or virtual cards whose billing region doesn't match usage | **US corporate business card**, matching the exit region |
| Environment | Time zone, locale and system settings don't match the IP | **Preconfigured** to match the exit region |
| Service source | Mirrors or third-party APIs with opaque models and limits | **100% official Claude Code**, usage verifiable in the official console |

## App features

- **Built-in terminal**: Claude Code is set up automatically on first launch, with no environment variables to configure
- **No API keys**: your subscription is connected automatically
- **Parallel projects**: each project gets its own tab and keeps running in the background
- **Nothing kept**: requests go straight from Claude Code to Claude's official service; MintPop stores no conversations or files

## Plans

| Plan | Price | Usage | Best for |
|---|---|---|---|
| Standard | $40 / mo | 1.25× Pro | Everyday development on a single project |
| Premium | $160 / mo | 6.25× Pro (≈ 1.25× Max 5x) | Heavy use across several projects |

Multipliers come from Claude's official enterprise plan specs. See the [website](https://lane.mintpop.ai/en/#pricing) for current prices.

## Platforms

| Platform | Requirements |
|---|---|
| macOS | Apple silicon (M series), macOS 12+; Intel Macs are not supported |
| Windows | Windows 10 / 11, x64 |
| Linux | Ubuntu 22.04+ (`.deb`); other distros use `.AppImage` |

Get installers from the [download section](https://lane.mintpop.ai/en/#download). This repository does not distribute builds.

## Feedback and support

| You want to… | Go to |
|---|---|
| Report a bug in the app, console or website | [Report a bug](../../issues/new?template=bug_report.yml) |
| Suggest a feature | [Request a feature](../../issues/new?template=feature_request.yml) |
| Ask questions or share tips | [Discussions](../../discussions) |
| Get help with your account, orders or renewals | [Contact us](https://mintpop.ai/contact) (please keep this out of public issues) |
| Report a security vulnerability | See [SECURITY.md](SECURITY.md) |

> ⚠️ Issues are public. **Do not** paste account emails, order numbers, tokens or IP addresses.
