# 拾光 (Raycall) 隐私政策 / Privacy Policy

**最后更新日期 / Last Updated**: 2026-10-16  
**应用名称 / App Name**: 拾光 · Raycall  
**Bundle Identifier**: `com.weifengluo.raycall`  
**项目主页 / GitHub**: [https://github.com/mapix/raycall](https://github.com/mapix/raycall)

---

## 中文版（Chinese）

### 1. 核心隐私原则：100% 纯本机处理
**拾光（Raycall）** 是一款完全在您的设备本地（On-Device）运行的相册记忆检索工具。
- **不联网、无服务器**：拾光不包含任何云端服务器，不发起任何外部互联网请求，也没有用户账号体系。
- **零数据收集**：我们不会收集、上传、存储、出售或向任何第三方共享您的照片、视频、位置信息、文字识别（OCR）内容、搜索历史或设备标识符。

### 2. 系统权限说明
- **照片图库访问权限（`NSPhotoLibraryUsageDescription`）**：
  - **用途**：仅用于在您的 iPhone / Mac 本机芯片上使用内置的端侧人工智能模型（Google EmbeddingGemma 2 LiteRT 与 Apple Vision）建立本地向量索引，以便您通过自然语言或画面文字快速搜索自己的照片与视频。
  - **存储位置**：生成的向量特征与索引数据库（SQLite）完全保存在您设备的应用沙盒目录内，永远不会离开您的设备。
  - **随时可控**：您可随时在系统“设置”中修改照片访问范围（支持“完全访问”或“有限访问”），也可在拾光应用内的“设置 → 清空并重新整理全部照片”一键销毁所有本地索引数据。
  - **私密隔离**：系统“已隐藏”与“最近删除”相簿中的内容永不读取、永不建立索引。

### 3. 第三方服务与追踪
- 本应用**不集成**任何第三方广告 SDK、统计分析 SDK 或崩溃追踪服务。
- 本应用**不进行**任何跨应用或跨网站追踪（`NSPrivacyTracking = false`）。

### 4. 联系我们
如果您对本隐私政策有任何疑问，请通过 GitHub 与我们联系：  
- Issues: [https://github.com/mapix/raycall/issues](https://github.com/mapix/raycall/issues)

---

## English Version

### 1. Core Principle: 100% On-Device Processing
**Raycall (拾光)** is a strictly on-device multimodal photo and video memory search application.
- **No Cloud, No Servers**: Raycall operates completely offline. It has no backend servers, requires no user accounts, and makes zero external network requests.
- **Zero Data Collection**: We do not collect, transmit, store, sell, or share any of your photos, videos, GPS locations, recognized text (OCR), search queries, or device identifiers.

### 2. Permissions We Request
- **Photo Library Access (`NSPhotoLibraryUsageDescription`)**:
  - **Purpose**: Used exclusively to analyze and index your selected photos and videos locally on your device using the bundled on-device EmbeddingGemma 2 model and Apple Vision framework.
  - **Storage**: All generated embeddings and search indices are stored strictly within your device's local app sandbox (`SQLite`) and never leave your device.
  - **User Control**: You can revoke photo permissions at any time in iOS Settings, or wipe the entire local index with one tap inside Raycall's Settings screen. Hidden and Recently Deleted albums are never accessed.

### 3. Third-Party SDKs & Tracking
- Raycall contains **no** third-party analytics, telemetry, or advertising SDKs.
- Raycall performs **no** tracking across apps or websites (`NSPrivacyTracking = false`).

### 4. Contact Us
If you have any questions regarding this Privacy Policy, please reach out via GitHub:  
- [https://github.com/mapix/raycall/issues](https://github.com/mapix/raycall/issues)
