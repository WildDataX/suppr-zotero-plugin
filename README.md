# 🔥 Suppr Zotero Plugin

<div align="center">

![GitHub release (latest by date)](https://img.shields.io/github/v/release/WildDataX/suppr-zotero-plugin)
![GitHub all releases](https://img.shields.io/github/downloads/WildDataX/suppr-zotero-plugin/total)
![GitHub](https://img.shields.io/github/license/WildDataX/suppr-zotero-plugin)
![GitHub stars](https://img.shields.io/github/stars/WildDataX/suppr-zotero-plugin)

**超能文献 Zotero 文档翻译插件**

*一键翻译学术文献，让语言不再成为知识获取的障碍*

[📥 下载插件](#安装指南) | [📖 使用教程](#使用方法) | [🌐 官方网站](https://suppr.wilddata.cn) | [❓ 常见问题](#常见问题)

</div>

---

## 📺 演示视频

https://player.bilibili.com/player.html?isOutside=true&aid=114880577273944&bvid=BV1t4udzyEqo&cid=31153718008&p=1

## ✨ 主要特性

- 🚀 **右键翻译**：在 Zotero 中直接翻译 PDF 文档
- 🎯 **精准翻译**：专为学术文献优化的 AI 翻译引擎
- 📄 **格式保持**：完美保持原文档的排版和格式
- ⚡ **高效便捷**：无需离开 Zotero 环境
- 🔒 **隐私保护**：文档翻译过程安全可靠
- 🌍 **多语言支持**：支持多种语言互译
- 📚 **批量处理**：支持多文档批量翻译

## 🚀 快速开始

### 系统要求

- Zotero 6.0 或更高版本
- 网络连接
- 超能文献账户（可免费注册）

### 安装指南

#### 方法一：自动安装（推荐）

1. 打开 Zotero
2. 点击 `工具` → `插件`
3. 点击齿轮图标 → `从文件安装插件`
4. 选择下载的 `.xpi` 文件
5. 重启 Zotero

#### 方法二：手动安装

1. 前往 [Releases 页面](https://github.com/WildDataX/suppr-zotero-plugin/releases)
2. 下载最新版本的 `.xpi` 文件
3. 拖拽文件到 Zotero 主窗口
4. 确认安装并重启

## 📖 使用方法

### 基本操作

1. **选择文档**：在 Zotero 文库中选择需要翻译的 PDF 文档
2. **启动翻译**：右键点击文档，选择"超能文献翻译"
3. **等待处理**：系统将自动上传并处理文档
4. **查看结果**：翻译完成后自动下载并附加到原条目
<img width="865" height="696" alt="8232fd3e74bc79c36b5f4fd077943651" src="https://github.com/user-attachments/assets/4ebb2e06-358c-4701-b1bc-ebce27c6a8dd" />

### 高级功能

- **批量翻译**：选择多个文档进行批量翻译
- **翻译设置**：自定义翻译语言对和质量设置
- **进度监控**：实时查看翻译进度和状态

## 🔗 相关服务

超能文献提供全方位的文档翻译服务：

| 服务类型 | 链接 | 描述 |
|---------|------|------|
| 📄 PDF翻译 | [PDF文档翻译](https://suppr.wilddata.cn/translate/landing/pdf) | 专业PDF文档翻译 |
| 📝 Word翻译 | [WORD文档翻译](https://suppr.wilddata.cn/translate/landing/docx) | Word文档格式翻译 |
| 📊 Excel翻译 | [EXCEL文档翻译](https://suppr.wilddata.cn/translate/landing/xlsx) | 表格数据翻译 |
| 🎯 PPT翻译 | [PPT文档翻译](https://suppr.wilddata.cn/translate/landing/pptx) | 演示文稿翻译 |
| 🌐 网页翻译 | [网页翻译](https://suppr.wilddata.cn/translate/landing/html) | 在线网页内容翻译 |
| 📤 在线上传 | [文档上传翻译](https://suppr.wilddata.cn/translate/upload) | 通用文档上传翻译 |

## 🛠️ 技术架构

### 项目结构

本项目基于开源模板构建，采用现代化的插件开发架构：

- **基础模板**：[Zotero Plugin Template](https://github.com/windingwind/zotero-plugin-template)
- **授权状态**：已获得原作者 [@windingwind](https://github.com/windingwind) 授权
- **开发框架**：TypeScript + React
- **构建工具**：Webpack + ESLint

# 📱 社区认可

本插件已被 **Zotero 中文社区** 正式收录：

- 🏆 [Zotero 中文社区插件库](https://zotero-chinese.com/plugins/#search=%E8%B6%85%E8%83%BD%E6%96%87%E7%8C%AE)
- 📋 [官方 PR 记录](https://github.com/zotero-chinese/zotero-plugins/pull/189)

## ❓ 常见问题

<details>
<summary><strong>Q: 插件安装后找不到翻译选项？</strong></summary>

A: 请确保：
1. Zotero 版本为 6.0 或以上
2. 插件已正确安装并启用
3. 重启 Zotero 后再尝试
4. 在文档条目上右键查看菜单选项
</details>

<details>
<summary><strong>Q: 翻译速度很慢怎么办？</strong></summary>

A: 翻译速度取决于：
1. 文档大小和页数
2. 网络连接质量
3. 服务器负载情况
4. 建议在网络状况良好时使用
</details>

<details>
<summary><strong>Q: 支持哪些文档格式？</strong></summary>

A: 目前支持：
- PDF 文档（推荐）
- 图片格式的PDF
- 扫描版PDF（OCR识别）
</details>

<details>
<summary><strong>Q: 翻译质量如何保证？</strong></summary>

A: 我们采用：
- 专门针对学术文献训练的AI模型
- 术语库和专业词汇优化
- 上下文感知翻译技术
- 格式和排版保持算法
</details>

## 🤝 贡献指南

我们欢迎社区贡献！


