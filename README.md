# 澎湃First

> 面向小米澎湃 HyperOS / MIUI 生态的 Android 综合工具应用，致力于成为小米用户的"全能助手"。

🌐 **官网**：[mfskys.github.io/First](https://mfskys.github.io/First/)  
📦 **下载**：[最新版本](https://github.com/mfskys/First/releases)

---

## ✨ 核心功能

| 模块 | 说明 |
|------|------|
| **设备参数查询** | 全面查询硬件参数：CPU、GPU、显示、内存、存储、电池、相机、音频、网络、传感器、NFC、生物识别等 19+ 大类。实时监测电池电流/电压与应用耗电排行，支持能耗测试排行榜。 |
| **固件版本查询** | 查询 MIUI / HyperOS 内测固件，追踪穿戴设备更新，提取固件下载链接，版本演进时间线一览无余。 |
| **APK 安装接管** | 接管外部 APK/APKS 安装请求，支持 Shizuku 静默安装，显示应用信息、签名、权限等详细内容。 |
| **资讯与社区** | 聚合澎湃资讯，追踪社区动态，参与话题讨论，发布你的观点与发现。 |
| **系统工具集** | 日志解析、重启记录分析、终端命令执行（Shizuku 提权）、进程管理、应用管理、隐藏 Activity 页面、壁纸提取、相机参数预设、贴膜神器。 |
| **云盘与下载** | 内置蓝奏云支持，统一下载管理面板，文件管理清晰有序。 |
| **AI 大模型** | 接入 AI 大模型能力，对话式分析日志与设备数据，让 AI 成为你的设备诊断助手。 |
| **用户与协作** | 完善的用户系统：个人主页、积分体系、抽奖活动、捐赠会员。支持社区协作修订与审核。 |

## 📲 系统要求

- **最低系统**：Android 12（API 31）
- **目标系统**：HyperOS / MIUI 深度适配
- **高级功能**：需安装 [Shizuku](https://github.com/RikkaApps/Shizuku) 并授权（无需 Root）

## 🛠️ 技术栈

- Kotlin · Jetpack Compose · Material 3
- Shizuku（系统级操作授权）
- 无障碍服务（电池数据采集）
- targetSdk 37

## ❓ 常见问题

**Q：需要 Root 权限吗？**  
不需要。大部分功能无需 Root，高级系统工具依赖 Shizuku 服务，通过 ADB 激活即可。

**Q：澎湃First 是免费的吗？**  
完全免费下载和使用。提供捐赠会员体系作为可选支持方式，所有核心功能均对所有用户开放。

**Q：支持哪些设备？**  
支持所有运行 Android 12 及以上版本的设备，核心功能针对小米澎湃 HyperOS / MIUI 设备深度适配。

## 📋 更新日志

### v2.1.5（2026 年 6 月）
- 接管外部 APK 安装请求，支持 Shizuku 静默安装
- 深色模式下弹出菜单背景色优化
- 等级颜色体系与图标样式统一
- 修复 59 个编译器警告

完整更新日志请查看 [Releases](https://github.com/mfskys/First/releases)。

## 📎 链接

- 🌐 官网：[mfskys.github.io/First](https://mfskys.github.io/First/)
- 📦 下载：[Releases](https://github.com/mfskys/First/releases)
- 📧 反馈：通过应用内"提交反馈"或 GitHub Issues
