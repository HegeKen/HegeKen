# HelilAb — 合理实验室 by HegeKen

独立开发者 [HegeKen](https://github.com/HegeKen) 的技术作品集网站。每一行代码、每一个架构决策都经得起推敲，在复杂度与简洁之间找到合理的平衡点。

**[www.helilab.cn](https://www.helilab.cn)**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-222222?style=flat-square&logo=githubpages)

## 项目概览

围绕小米 ROM 数据生态与跨平台应用开发，我维护着 9 个核心项目：ROM 追踪站点、数据仓库与自动化采集管道、本地文件全文搜索工具、AI 小说校对应用、macOS 原生工具等；MIUIROMS、MRCI 两个早期项目收录于[其他项目](#其他项目)。

## 展示项目

| # | 项目 | 描述 | 技术栈 | 链接 |
|---|------|------|--------|------|
| 01 | **HyperOS.fans** | 小米 HyperOS 非官方爱好者网站，追踪 180+ 设备 ROM 更新 | Nuxt 4, Vue 3, Vuetify 4, Python | [hyperos.fans](https://hyperos.fans) |
| 02 | **HyperData** | HyperOS 核心数据层，自动化采集管道与静态 JSON 数据仓库 | Python, AES Crypto, MySQL, Selenium | [data.hyperos.fans](https://data.hyperos.fans) |
| 03 | **NuxtMR** | MIUI 官方 ROM 下载聚合平台，数据驱动的静态内容架构 | Nuxt 4, Vue 3, TypeScript, Python | [roms.miuier.com](https://roms.miuier.com) |
| 04 | **MRData** | MIUI ROM 数据仓库，200+ 设备数据与 20+ 爬虫脚本 | Python, AES Crypto, Cloudflare Pages | [data.miuier.com](https://data.miuier.com) |
| 05 | **MiROMs HUB** | 小米 ROM 数据平台 monorepo：多语言站点查询 MIUI / HyperOS 全量固件、管理后台直连 MySQL，另含 Android 客户端 | Nuxt 4, Vue 3, TypeScript, Tailwind CSS, MySQL, Kotlin | [hub.miuier.com](https://hub.miuier.com) |
| 06 | **miroms** | MiROMs HUB 数据引擎，326 台设备全量 ROM 数据与零依赖采集管道 | Python 3, AES Crypto, MySQL, JSON API, GitHub Pages | [api.miuier.com](https://api.miuier.com) |
| 07 | **novel-proofreader** | AI 小说校对桌面/移动应用，百万字级文本处理 | Tauri 2, React 19, TypeScript, Zustand | [proofreader.helilab.cn](https://proofreader.helilab.cn) |
| 08 | **QuarantineRemover** | macOS 隔离属性移除工具，Liquid Glass 视觉效果 | Swift, SwiftUI, macOS | [GitHub](https://github.com/HegeKen/QuarantineRemover) |
| 09 | **DocSniffer** | 基于 Tauri 2 + Rust + Tantivy 的本地文件全文搜索桌面应用 | Tauri 2, Rust, Tantivy, React 18, TypeScript | [GitHub](https://github.com/HegeKen/DocSniffer) |

### 其他项目

未在网站上展示的早期项目：

| 项目 | 描述 | 技术栈 | 链接 |
|------|------|--------|------|
| **MIUIROMS** | MIUI 官方 ROM 仓库原版（2019–2024），NuxtMR 的前身，部署于 old.miuier.com | HTML, PHP | [GitHub](https://github.com/HegeKen/MIUIROMS) |
| **MRCI** | 基于 CodeIgniter 4 的 PHP 后端项目，含多语言切换等模块 | PHP, CodeIgniter 4 | [GitHub](https://github.com/HegeKen/MRCI) |

## 项目数据

以下为各项目在 GitHub 上的社区数据（截至 2026 年 09 月）：

| 项目 | Stars | Forks | Open Issues | Commits | 语言 |
|------|-------|-------|-------------|---------|------|
| [HyperOS.fans](https://github.com/HegeKen/HyperOS.fans) | ![](https://img.shields.io/github/stars/HegeKen/HyperOS.fans?style=social) | ![](https://img.shields.io/github/forks/HegeKen/HyperOS.fans?style=social) | ![](https://img.shields.io/github/issues/HegeKen/HyperOS.fans) | 384+ | Vue |
| [HyperData](https://github.com/HegeKen/HyperData) | ![](https://img.shields.io/github/stars/HegeKen/HyperData?style=social) | ![](https://img.shields.io/github/forks/HegeKen/HyperData?style=social) | ![](https://img.shields.io/github/issues/HegeKen/HyperData) | 3265+ | Python |
| [NuxtMR](https://github.com/HegeKen/NuxtMR) | ![](https://img.shields.io/github/stars/HegeKen/NuxtMR?style=social) | ![](https://img.shields.io/github/forks/HegeKen/NuxtMR?style=social) | ![](https://img.shields.io/github/issues/HegeKen/NuxtMR) | 1179+ | Vue |
| [MRData](https://github.com/HegeKen/MRData) | ![](https://img.shields.io/github/stars/HegeKen/MRData?style=social) | ![](https://img.shields.io/github/forks/HegeKen/MRData?style=social) | ![](https://img.shields.io/github/issues/HegeKen/MRData) | 1773+ | Python |
| [hub.miuier.com](https://github.com/HegeKen/hub.miuier.com) | ![](https://img.shields.io/github/stars/HegeKen/hub.miuier.com?style=social) | ![](https://img.shields.io/github/forks/HegeKen/hub.miuier.com?style=social) | ![](https://img.shields.io/github/issues/HegeKen/hub.miuier.com) | 35+ | Vue |
| [miroms](https://github.com/HegeKen/miroms) | ![](https://img.shields.io/github/stars/HegeKen/miroms?style=social) | ![](https://img.shields.io/github/forks/HegeKen/miroms?style=social) | ![](https://img.shields.io/github/issues/HegeKen/miroms) | 72+ | Python |
| [MIUIROMS](https://github.com/HegeKen/MIUIROMS) | ![](https://img.shields.io/github/stars/HegeKen/MIUIROMS?style=social) | ![](https://img.shields.io/github/forks/HegeKen/MIUIROMS?style=social) | ![](https://img.shields.io/github/issues/HegeKen/MIUIROMS) | 207+ | HTML |
| [MRCI](https://github.com/HegeKen/MRCI) | ![](https://img.shields.io/github/stars/HegeKen/MRCI?style=social) | ![](https://img.shields.io/github/forks/HegeKen/MRCI?style=social) | ![](https://img.shields.io/github/issues/HegeKen/MRCI) | 5+ | PHP |
| [novel-proofreader](https://github.com/HegeKen/novel-proofreader) | ![](https://img.shields.io/github/stars/HegeKen/novel-proofreader?style=social) | ![](https://img.shields.io/github/forks/HegeKen/novel-proofreader?style=social) | ![](https://img.shields.io/github/issues/HegeKen/novel-proofreader) | 109+ | TypeScript |
| [QuarantineRemover](https://github.com/HegeKen/QuarantineRemover) | ![](https://img.shields.io/github/stars/HegeKen/QuarantineRemover?style=social) | ![](https://img.shields.io/github/forks/HegeKen/QuarantineRemover?style=social) | ![](https://img.shields.io/github/issues/HegeKen/QuarantineRemover) | 9+ | Swift |
| [DocSniffer](https://github.com/HegeKen/DocSniffer) | ![](https://img.shields.io/github/stars/HegeKen/DocSniffer?style=social) | ![](https://img.shields.io/github/forks/HegeKen/DocSniffer?style=social) | ![](https://img.shields.io/github/issues/HegeKen/DocSniffer) | 9+ | Rust |
