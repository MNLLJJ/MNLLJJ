<div align="center">

# 嗨，我是 MNLLJJ 🔨

**铁砧音MAD 创作者 · 全栈折腾爱好者**

*把同一块铁砧，敲出九百种声音。*

[![Bilibili](https://img.shields.io/badge/Bilibili-MNLLJJ-FB7299?logo=bilibili&logoColor=white)](https://space.bilibili.com/3546619769260163)
[![GitHub](https://img.shields.io/badge/GitHub-MNLLJJ-181717?logo=github&logoColor=white)](https://github.com/MNLLJJ)

</div>

---

## 关于我

我在 B 站做**铁砧音MAD**——把各种旋律用 Minecraft 铁砧的敲击声重写一遍。

截至目前：**6.9 万关注 · 93 个投稿 · 累计 757 万播放**，拥有「知名偶像」稀有勋章（门槛是自制视频总播放破百万）。主页签名里那句「可以给 up 点歌」是真的，欢迎来点。

创作久了，就发现现成的工具不够用——于是我干脆自己做。围绕"铁砧"这一个音色，我把工具链从浏览器端 DAW 一路做到了 Minecraft 模组、桌面应用和 3D 建模。**创作驱动开发，开发反哺创作**，这就是我在做的事。

---

## 铁砧工具链：为一个音色造一整套工具

| 项目 | 是什么 | 技术 |
| :--- | :--- | :--- |
| **Anvil Music Maker**<br>`铁砧音乐制作器` | 浏览器端铁砧主题数字音频工作站（DAW）。Canvas 钢琴卷帘写音符、真实铁砧采样 + 六次谐波加法合成钢琴、多轨独立编辑、走带与节拍器、JSON 项目存取、WAV 离线渲染导出。约 3400 行单文件实现，**打开网页即用、零安装**；经九轮审计修复 55+ 问题，已提交 B 站 Toy 内测申请 | 原生 JS · Web Audio API |
| **Anvil MAD Creator Lite** | 上面的移动端友好轻量版。单 HTML 文件内嵌 38 个立式钢琴采样与铁砧合成音色，新增播放列表视图与 MIDI 导入导出 | 原生 JS · Git LFS |
| **Anvil Note Block** | Minecraft 模组，Fabric / NeoForge 双版本：音符盒正下方放置铁砧时，音符盒即演奏铁砧撞击声。以 F#4 为基准音，支持 F#3 ~ F#5 共 25 级半音变调，铁砧下再垫铁块可触发更深沉的共鸣；兼容 MC 1.21.0 ~ 1.21.11+ | Java · Fabric / NeoForge |

---

## 桌面应用：把网页装进原生壳

| 项目 | 是什么 | 技术 |
| :--- | :--- | :--- |
| [**DeepChat Desktop**](https://github.com/MNLLJJ/deepchat-desktop) | 把 chat.deepseek.com 打包为原生桌面应用，网页端功能全量保留。**双保险登录态持久化**：原生 WebView 存储 + 本地文件快照，另提供按需启用的 Cargo feature——全量 HttpOnly Cookie 原生读写、会话快照加密落盘（DPAPI / Keychain + AES-256-GCM）。处理了单实例保护、外链路由、桌面环境校验适配与跨平台编译差异 | Tauri 2 · Rust |
| [**DeepSeek Harness Desktop**](https://github.com/MNLLJJ/deepseek-harness-desktop) | 把 DeepSeek Harness（`dsh`）的 Web UI 打包为跨平台桌面应用。采用 **sidecar 模式**托管 Node 服务进程，端口就绪后导航到本地地址，后端功能原样保留。补齐原生菜单、系统托盘、快捷键桥、窗口状态记忆与明暗主题，CI 矩阵覆盖 6 个平台 × 变体组合 | Tauri 2 · Rust · Node |

---

## 其他折腾

| 项目 | 说明 |
| :--- | :--- |
| **τMeter** | 基于华为 τ 定律的 Windows 整机时间常数测量仪。以微秒级精度采集 CPU 缓存、访存、磁盘随机/顺序、网络、PCIe 与 GPU 共 8 个子系统的延迟，按可配置权重合成综合 τ 值，用于性能瓶颈诊断与趋势预测；v3.0 引入半导体器件级 RC 物理建模 |
| **MC LAN Scanner** | Minecraft 局域网房间实时监测工具。UDP 组播监听 + TCP 端口探测 + SLP 协议查询 + 超时监控四层架构，可显示房间 MOTD、MC 版本与在线玩家名单，新房间上线自动弹系统通知。**纯 Python 标准库、零外部依赖、内存占用 < 30MB** |
| **PakePlus** | 参与 Fork 维护，把任意网页 / HTML / Vue / React 项目打包为 < 5MB 的多端桌面与移动应用 |

---

## B 站创作

<div align="center">

[![粉丝](https://img.shields.io/badge/粉丝-6.9万-FB7299?style=flat-square)](#)
[![投稿](https://img.shields.io/badge/投稿-93-FB7299?style=flat-square)](#)
[![总播放](https://img.shields.io/badge/总播放-757万-FB7299?style=flat-square)](#)
[![弹幕](https://img.shields.io/badge/总弹幕-1.5万-FB7299?style=flat-square)](#)

</div>

**创作分布**（93 个投稿）：音MAD 75 · 单机游戏 11 · 翻唱 2 · 网络游戏 2 · 原创音乐 1 · 搞笑 1 · 日常 1
**播放成绩**：21 个视频破 10 万播放，其中 3 个破 50 万

### 代表作

| 播放 | 标题 | 发布 |
| ---: | :--- | :--- |
| **92.4 万** | “我来自那个铁锭如云的时代” | 2026-03 |
| **64.6 万** | 【音MAD】铁砧...还是那么可爱啊...... | 2026-06 |
| **54.5 万** | 【音MAD】雪地里传来了铁砧声 | 2026-03 |
| 43.6 万 | 【铁砧音MAD/原曲不使用】焊接遗憾 | 2026-08 |
| 41.3 万 | 【铁砧音MAD】一滴一滴刺痛我的心，但是铁砧 | 2026-08 |
| 35.0 万 | 【音MAD】人是铁(砧) | 2026-07 |
| 16.8 万 | 【MC音乐】拼接遗憾 | 2026-08 |

> 👉 完整作品见 [space.bilibili.com/3546619769260163](https://space.bilibili.com/3546619769260163)

---

## 工具箱

**开发**

![Rust](https://img.shields.io/badge/Rust-000000?logo=rust&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Tauri](https://img.shields.io/badge/Tauri_2-24C8DB?logo=tauri&logoColor=white)
![Minecraft](https://img.shields.io/badge/Minecraft_Modding-62B47A?logo=minecraft&logoColor=white)

**创作**

`Web Audio API` · `FL Studio` · `Blender` · `Photoshop` · `剪映`

---

## 一点想法

我挺喜欢"铁砧"这个意象的——它本来是 Minecraft 里最笨重、最容易被忽略的方块之一，只用来修装备。但当它被当作乐器，把每一段旋律都敲一遍，反而有了一种**笨拙又诚恳的生命力**。

做工具也是一样。市面上的 DAW 都很强大，但没有一个是为了"想用铁砧写歌"这个奇怪念头而存在的。所以我就自己写了一个。

> 如果你也想用铁砧敲点什么，欢迎来 [B 站](https://space.bilibili.com/3546619769260163) 点歌。

<div align="center">

*「我来自那个铁锭如云的时代。」*

</div>
