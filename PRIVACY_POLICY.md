# SnoozeBook · 隐私政策 (Privacy Policy)

**生效日期 (Effective Date)**: 2026年10月31日 / October 31, 2026

SnoozeBook（以下简称“我们”或“本应用”）高度尊重并坚决保护所有用户的个人隐私与数据安全。本隐私政策旨在向您说明我们在您使用 SnoozeBook 时如何处理您的数据。

**核心承诺**：SnoozeBook 是一款**完全本地优先（Local-First）**的有声书播放工具。**我们不收集、不存储、不分享您的个人身份信息，亦不包含任何第三方广告或遥测追踪 SDK。**

---

## 1. 简要概览 (Summary)

- **无账号系统**：无需注册、无需手机号、邮箱或任何第三方社交账号即可完整使用全部功能。
- **本地存储**：您的有声书音频文件、个人书单、书签及进度记录完全保留在您本地设备的沙盒中，零服务器上传。
- **传感器仅短时运算**：智能入睡检测所需的加速度传感器数据仅在设备内存中实时运算，绝不写入磁盘或对外传输。
- **iCloud 进度接力**：若开启 Pro 的 iCloud 功能，进度数据仅通过您私人的 Apple iCloud Key-Value 存储端到端同步，开发者无权访问。
- **无追踪/无广告**：不请求 IDFA（广告标识符），不嵌入任何第三方广告或分析类 SDK。

---

## 2. 详细条款 (Detailed Terms)

### 2.1 音频文件与书库数据 (Audio Files & Library)
- **存储位置**：您通过系统「文件」App、隔空投送 (AirDrop) 或电脑访达 (Finder) 导入的所有音频文件，均仅保存在 iOS 系统的安全沙盒目录中。
- **访问权限**：本应用仅在获得您明确授权后访问您选定的音频文件，不会扫描您设备中的其他任何个人文件或照片。
- **所有权**：音频文件始终为您本地私有资产，我们不对其进行任何转存或上传。

### 2.2 传感器与运动数据 (CoreMotion & Sensor Data)
- **使用目的**：当您在播放时启用「智能睡眠检测」功能，应用会调用设备的加速度传感器感知身体翻动与静止。
- **数据处理**：加速度扰动幅度仅在设备内存中瞬时计算（用于判断是否柔和降低音量及暂停），不进行长期记录，不写入本地数据库，亦绝不会通过网络上传。

### 2.3 iCloud Key-Value 进度同步 (iCloud Sync for Pro)
- **使用范围**：仅供 Pro 用户在名下多台 Apple 设备（如 iPhone、iPad、Mac）之间自动接力播放断点。
- **同步内容**：仅包含纯文本键值对（书籍标识码、播放秒数时间戳、听完标记）。
- **加密与安全**：该功能基于 Apple 原生 `NSUbiquitousKeyValueStore` 架构，全部数据直接由 Apple 的 iCloud 服务安全加密托管。我们作为开发者无法获取亦无法查看您的 iCloud 数据。

### 2.4 应用内购买 (In-App Purchases)
- **交易处理**：SnoozeBook Pro 采用一次性终身买断制，所有支付交易均由 Apple App Store 官方 StoreKit 2 接口安全完成。
- **支付凭据**：我们不会获得、处理或储存您的银行卡号、信用卡信息、真实姓名或账单地址。交易凭证全部由 Apple 进行安全验证。

### 2.5 第三方 SDK 与分析工具 (Third-Party SDKs)
- 本应用**坚决不集成**任何第三方商业化广告 SDK、追踪代码、用户行为分析套件或未经您同意的外部网络请求。

---

## 3. 儿童隐私保护 (Children's Privacy)

SnoozeBook 适合所有年龄段（包括 4 岁以上儿童及青少年）安全使用。我们不收集任何儿童的个人可识别信息。

---

## 4. 政策更新与联系方式 (Updates & Contact)

我们可能会根据功能迭代或法律法规要求适时更新本隐私政策。任何重大变更均会在应用更新日志或此页面显著公示。

如果您对本隐私政策有任何疑问、意见或反馈，欢迎通过以下途径与我们联系：
- **GitHub Issues 专区**: [https://github.com/kinson5/SnoozeBook/issues](https://github.com/kinson5/SnoozeBook/issues)
- **技术支持页面**: [https://github.com/kinson5/SnoozeBook/blob/main/SUPPORT.md](https://github.com/kinson5/SnoozeBook/blob/main/SUPPORT.md)

---

# Privacy Policy (English Version)

**Effective Date**: October 31, 2026

SnoozeBook ("we", "our", or "the App") respects and protects the personal privacy and data security of all users.

**Our Core Commitment**: SnoozeBook is a **100% Local-First** audiobook player. **We do not collect, store, or share your personal data, nor do we include any third-party ads or tracking SDKs.**

### 1. Data Collection & Local Storage
- **Local Sandbox**: All imported audio files (MP3, M4A, M4B), metadata, and playback history remain strictly on your local device within the secure iOS sandbox.
- **No User Accounts**: The App operates completely without registration or cloud user profiles.
- **Zero Telemetry**: No third-party analytics, diagnostic tracking, or ad libraries are present in SnoozeBook.

### 2. Sensor Usage (CoreMotion)
- When "Smart Sleep Detection" is active during playback, SnoozeBook accesses the device's accelerometer to estimate stillness and body movement.
- All motion calculations occur solely in temporary volatile device memory. Sensor data is never saved to disk and never transmitted over the internet.

### 3. iCloud Progress Sync (Pro)
- For Pro users, playback timestamps and completion status synchronize across your Apple devices using Apple's native `NSUbiquitousKeyValueStore`.
- This sync is end-to-end handled and encrypted by Apple. The developer has zero access to your Apple ID, files, or progress.

### 4. In-App Purchases
- All transactions for "SnoozeBook Pro Lifetime" are processed exclusively through Apple App Store (StoreKit 2). We never receive or store your financial information.

### 5. Contact Us
For questions or inquiries regarding our privacy policy, please open an issue at:
[https://github.com/kinson5/SnoozeBook/issues](https://github.com/kinson5/SnoozeBook/issues)
