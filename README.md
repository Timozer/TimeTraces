# 岁集 (TimeTraces)

[![Platform](https://img.shields.io/badge/Platform-iOS%2015.0%2B-blue.svg)](https://developer.apple.com/ios/)
[![License](https://img.shields.io/badge/License-Private-lightgrey.svg)](LICENSE)
[![Privacy](https://img.shields.io/badge/Privacy-Local%20First-green.svg)](PRIVACY.md)

**岁集 (TimeTraces)** 是一部伴随一生的数字生命档案。它不仅是一个记录工具，更是一个守护家庭记忆与数据主权的安全港湾。

---

## 🌟 核心理念 (Vision)

“生命是由无数个瞬间汇聚而成的长河。”

从第一声啼哭开始，岁集通过**插件化架构**，伴随被记录者从婴儿期、成长期直至成年，动态适配不同人生阶段的记录需求。我们坚信：**数据的主权应属于用户**。

---

## ✨ 核心特性 (Features)

### 👶 全场景育儿记录 (现阶段核心)
- **精细化录入**：涵盖喂奶（母乳/配方奶）、睡眠、洗澡、排泄（尿布）、体温、用药等。
- **健康监测**：内置 **WHO (世界卫生组织)** 标准生长曲线（身高、体重、头围），实时评估发育状态。
- **智能提醒**：个性化疫苗接种计划提醒，确保不遗漏每一份健康守护。

### 🛡 数据主权与隐私 (Privacy & Sovereignty)
- **本地优先 (Local-First)**：数据默认存储于设备本地 SQLite，不上传至任何第三方服务器。
- **私有云同步 (NAS/SMB)**：支持通过 **SMB/WebDAV** 协议同步至您的个人 NAS（如群晖、威联通），构建家庭私有云。
- **无痕体验**：无广告、无社交分享诱导、不采集任何个人身份信息。

### ⚙️ 技术亮点 (Technical Highlights)
- **生命阶段自适应 UI**：UI 风格与推荐工具随年龄自动切换。
- **插件化架构**：模块化设计，保持核心应用极致轻量。
- **专业导出**：支持一键生成 PDF/高清长图形式的就诊总结或成长报告。

---

## 📸 预览 (Screenshots)

*(待上传：时光轴、生长曲线、SMB 设置、记录面板等截图)*

---

## 🛠 开发与贡献 (Development)

本项目采用 **SwiftUI** 与 **Combine** 构建，遵循现代 iOS 开发最佳实践。

- **最低版本支持**：iOS 15.0+
- **核心依赖**：
  - `SMBClient` (用于私有云同步)
  - `SwiftCharts` (用于数据可视化)

---

## 📄 法律与隐私 (Legal)

- **隐私政策**：详情请参阅 [PRIVACY.md](PRIVACY.md)。
- **技术支持**：如有任何问题，请提交 [Issue](https://github.com/zhenyuwang/TimeTraces/issues) 或联系开发者。

---

© 2026 TimeTraces Team. All rights reserved.
