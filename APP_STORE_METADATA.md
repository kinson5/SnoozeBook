# SnoozeBook · App Store Connect 完整上架提审资料包

本文档汇总了在 **Apple App Store Connect** 提交审核时所需填写的全部元数据、文本描述、分级信息、审核员测试指引与内购配置，支持直接复制粘贴使用。

---

## 1. App 基本信息 (Basic Information)

| 字段 (Field) | 填写内容 (Value) | 字符上限要求 |
| :--- | :--- | :--- |
| **App 名称 (Name)** | `SnoozeBook - 睡前听书与手势盲听` | ≤ 30 字符 |
| **英文名称 (Name - English)** | `SnoozeBook - Bedtime Audiobooks` | ≤ 30 字符 |
| **副标题 (Subtitle - 简体中文)** | `闭眼全屏盲控 · 智能入睡守护` | ≤ 30 字符 |
| **副标题 (Subtitle - 繁體中文)** | `閉眼全螢幕盲控 · 智能入睡守護` | ≤ 30 字符 |
| **副标题 (Subtitle - English)** | `Eyes-Free Bedtime Audiobooks` | ≤ 30 字符 |
| **主类别 (Primary Category)** | **图书 (Books)** | - |
| **次类别 (Secondary Category)** | **健康与健美 (Health & Fitness)** 或 **工具 (Utilities)** | - |
| **内容分级 (Age Rating)** | **4+** (无任何暴力、成人、赌博或医疗限制内容，纯本地播放器) | - |
| **版权信息 (Copyright)** | `2026 Kinson. All rights reserved.` | - |
| **SKU** | `SnoozeBook-iOS` | 唯一标识符 |
| **Bundle ID** | `com.kinson.AudiobookPlayer` | 与 Xcode 工程一致 |

---

## 2. 搜索关键词 (Keywords)

> **苹果规则**：上限 100 字符，词与词之间使用半角英文逗号 `,` 分隔，**不要**包含空格。

### 简体中文 (Simplified Chinese)
```text
睡前听书,有声书,听书,助眠,白噪音,睡眠定时,手势,盲操,本地播放器,音频书,夜读,伴奏
```

### 繁體中文 (Traditional Chinese)
```text
睡前聽書,有聲書,聽書,助眠,白噪音,睡眠定時,手勢,盲控,本機播放器,音訊書,夜讀,伴奏
```

### English (United States & Global)
```text
audiobook,bedtime,sleep timer,eyes free,gestures,night reading,voice boost,offline,books
```

---

## 3. 宣传文本 (Promotional Text)

> **特点**：显示在 App Store 描述上方，上限 170 字符，可随时修改且无需重新提交版本审核。

### 简体中文
```text
专为关灯闭眼与不便看屏场景打造。全屏大触控极简手势、智能体动入睡检测、录音人声增强与自然伴读音景，让每晚听书成为舒适入眠的享受。
```

### 繁體中文
```text
專為關燈閉眼與不便看螢幕場景打造。全螢幕大觸控極簡手勢、智能體動入睡偵測、人聲音訊增強與自然伴讀音景，讓每晚聽書成為舒適入眠的享受。
```

### English
```text
Designed for bedtime, running, and eyes-free chores. Enjoy full-screen blind gestures, smart sleep auto-pause, voice booster, and calming ambient soundscapes.
```

---

## 4. 应用详细描述 (Description)

### 简体中文版 (Simplified Chinese)

```text
SnoozeBook 是一款专为「睡前熄灯好眠」与「视线不便看屏（跑步、驾车、做家务）」深度定制的有声书播放器。

我们重新思考了人与声音的交互方式——在黑暗与闭眼中，您不再需要费力辨认屏幕上的微小按键，一切操作皆在全屏触控与呼吸起伏之间自然发生。

【告别三大听书痛点】
1. 睡前关灯摸索屏幕易被强光刺眼，甚至手机砸脸？
➔ SnoozeBook 带来「全屏手势模式」：无需注视屏幕，轻触任意位置即播放/暂停，左右扫动快退快进，上下滑动调节系统音量，躺平盲控舒适自如。
2. 听着听着睡着了，第二天醒来不知道播到哪里？
➔ 独创「智能入睡守护 (Smart Sleep)」：利用内置加速度传感器感知身体翻动与静止。当判定您安然入睡后，音量先柔和淡出（轻摇手机即可续播），确认入睡后自动贴心回退 2 分钟并记录断点，第二天醒来进度丝毫不乱。
3. 有声书录音嘈杂、声音忽大忽小，夜间听得耳神经紧绷？
➔ 专研「睡前人声增强 (Voice Boost)」与「混音伴读音景」：突显对白清晰度，滤除底噪轰鸣；更可叠加雨声、壁炉、海浪白噪音与舒缓钢琴曲，构筑温馨静谧的安睡氛围。

【核心功能亮点】
• 🌙 睡前 1-Tap 快捷胶囊：主屏 1 秒直达智能睡眠检测、15/30/45 分钟定时或播完本章停播。
• 📱 全屏盲操手势：触碰任意位置即时响应，伴随细腻触感震动反馈，闭眼入睡、跑步健身、车上骑行两不误。
• 🕯️ 极暗视觉夜读模式：深红夜视 (650nm)、暖琥珀 (590nm)、暗月光三种护眼光谱，对视网膜视紫红质零漂白，完全不抑制褪黑素分泌。
• 🔊 人声强化与多级增益：原声标准、+6dB 增强、+12dB 极强放大，微弱老磁带录音也能清晰入耳。
• 🌧️ 自然白噪音与 CC0 舒缓伴奏：淅沥细雨、温暖壁炉、静谧海浪、轻柔慢板钢琴，支持与有声书双轨独立音量混音。
• ⚡ 本地优先架构：支持通过隔空投送 (AirDrop)、电脑访达/iTunes 文件共享、系统「文件」App 导入任意 MP3、M4A、M4B，离线秒开，零网络流量依赖。
• ☁️ iCloud 进度轻量接力 (Pro)：在 iPhone / iPad / Mac 之间无缝实时同步断点与听完标记。
• 💎 一次性买断无广告：无订阅陷阱、零第三方广告、绝不收集个人隐私。
```

### 繁體中文版 (Traditional Chinese)

```text
SnoozeBook 是一款專為「睡前熄燈好眠」與「視線不便看螢幕（跑步、駕車、做家務）」深度打造的有聲書播放器。

我們重新構想了人與音訊的互動方式——在黑暗與閉眼中，您不再需要費力摸索微小按鍵，一切操作皆在全螢幕觸控與呼吸起伏間自然完成。

【告別三大聽書痛點】
1. 睡前關燈摸索螢幕容易被強光刺眼，甚至手機砸臉？
➔ SnoozeBook 帶來「全螢幕手勢模式」：無需注視螢幕，輕觸任意位置即播放/暫停，左右掃動快退快進，上下滑動微調音量，躺平盲控自在舒坦。
2. 聽著聽著睡著了，隔天醒來找不到進度位置？
➔ 獨家「智能入睡守護」：透過機身加速度感測器感知身體翻動與靜止。判定您安然入睡後，音量柔和淡出（輕搖手機即可續播），確認入睡後自動貼心回退 2 分鐘並記錄斷點，隔天醒來進度絲毫不亂。
3. 錄音品質參差、聲音忽大忽小，夜間聽得神經緊繃？
➔ 專研「睡前人聲增強」與「混音伴讀音景」：突顯對白清晰度，撫平底噪雜音；更可疊加細雨、壁爐、海浪白噪音與慢板鋼琴曲，營造安寧靜謐的睡眠氛圍。

【核心特色】
• 🌙 睡前 1-Tap 快捷膠囊：主頁 1 秒直達智能入睡偵測、15/30/45 分鐘定時或播完本章停播。
• 📱 全螢幕手勢盲控：觸碰任意位置即時響應，細膩觸感震動回饋，閉眼入睡、跑步健身、駕車騎行皆適用。
• 🕯️ 極暗視覺夜讀模式：深紅夜視、暖琥珀、暗月光三種護眼光譜，不抑制褪黑素分泌。
• 🔊 人聲強化與多級放大：原聲標準、+6dB 增強、+12dB 極強放大，微弱音訊也能清晰入耳。
• 🌧️ 自然白噪音與舒緩樂曲：支援與有聲書雙軌獨立音量即時混音伴讀。
• ⚡ 本機優先架構：支援 AirDrop、Finder / 檔案 App 匯入 MP3/M4A/M4B，離線秒開，零流量負擔。
• ☁️ iCloud 進度接力 (Pro)：在 iPhone / iPad / Mac 之間跨裝置無縫同步播放斷點。
• 💎 一次性買斷零廣告：無訂閱陷阱、零廣告打擾、絕不收集個人隱私。
```

---

## 5. 合规网址 (Required App Store URLs)

在 App Store Connect 中填写以下官方公开链接：

| 网址类型 | App Store Connect 填写字段 | 官方公开 URL |
| :--- | :--- | :--- |
| **隐私政策网址** | `Privacy Policy URL` (**必填**) | `https://github.com/kinson5/SnoozeBook/blob/main/PRIVACY_POLICY.md` |
| **技术支持网址** | `Support URL` (**必填**) | `https://github.com/kinson5/SnoozeBook/blob/main/SUPPORT.md` |
| **营销网址** | `Marketing URL` (*选填*) | `https://github.com/kinson5/SnoozeBook` |

---

## 6. App 审核信息 (App Review Information)

在 App Store Connect 的「**App 审核信息 (App Review Information)**」栏目填写以下内容供苹果审核团队查阅：

### 登录信息 (Sign-In Information)
- **需要登录？**：**否 (Unchecked)**
- **说明**：本应用属于纯本地优先有声书工具，无需注册或登录账号，打开即可立即完整体验。

### 审核备注 (Notes for Apple Reviewer)
```text
Dear Apple Review Team,

SnoozeBook is a local-first audiobook player tailored for bedtime listening, screen-free gestures, and eyes-free environments (such as driving, running, and falling asleep).

1. Testing Audio Playback & Sample Audio:
- The app supports importing audio via the standard iOS Document Picker ("文件" App), iTunes / Finder File Sharing, and AirDrop.
- We have prepared 3 public-domain sample audiobook clips (2 English, 1 Chinese) with embedded cover art and ID3 metadata for your testing:
  👉 Sample Audiobooks: https://github.com/kinson5/SnoozeBook/tree/main/samples
  • Track 1: The Little Prince - Chapter 1 (English, ~1.4MB)
  • Track 2: Alice's Adventures in Wonderland - Chapter 1 (English, ~1.2MB)
  • Track 3: Dao De Jing - Classical Reading (Chinese, ~980KB)
- You can also import any common MP3, M4A, or M4B audio file from the Files app by tapping the "导入音频文件" button on the empty state screen or top-right library menu.

2. Full-Screen Gesture Mode:
- On the main player, tap the purple "手势 (Gestures)" button.
- Tap anywhere on the black screen to Play/Pause.
- Swipe left/right to rewind/fast-forward 15 seconds.
- Swipe up/down to adjust hardware volume with instant HUD feedback.

3. Smart Sleep Detection:
- Tap "智能入睡" on the bedtime capsule bar or inside Settings.
- The app uses real-time accelerometer motion to sense stillness and gentle movements.
- When stillness duration is reached, the volume gently fades out over 60 seconds. A gentle shake of the device extends playback. Once asleep, playback pauses and automatically rewinds 2 minutes.

4. In-App Purchase:
- We offer a one-time non-consumable buyout: "SnoozeBook Pro Lifetime" (Product ID: com.kinson.AudiobookPlayer.pro.lifetime).
- It unlocks unlimited Voice Boost, Night Reading Mode, Full-Screen Gestures, and iCloud Progress Sync via NSUbiquitousKeyValueStore.
- A functional "Restore Purchases" button and clear EULA/Privacy Policy links are prominently included on the paywall.

All ambient music tracks included in the app are licensed under CC0 / CC-BY 4.0 Public Domain by Kevin MacLeod (incompetech.com), with complete attribution listed in the in-app "Licenses & Acknowledgments" page.

Thank you for your time and review!
```

---

## 7. App 内购买项目配置 (In-App Purchase Setup)

在 App Store Connect ➜ **功能 (Features)** ➜ **App 内购买项目 (In-App Purchases)** 中添加：

| 配置项 | 设定值 | 说明 |
| :--- | :--- | :--- |
| **类型 (Type)** | **非消耗型 (Non-Consumable)** | 一次性买断，终身可用 |
| **参考名称 (Reference Name)** | `SnoozeBook Pro Lifetime` | 内部管理名称 |
| **产品 ID (Product ID)** | `com.kinson.AudiobookPlayer.pro.lifetime` | **必须完全一致** |
| **定价等级 (Price Tier)** | **Tier 2** | 国内: `¥18.00` / 海外: `$1.99` |
| **显示名称 (zh-Hans)** | `SnoozeBook Pro 终身会员` | 购买弹窗展示 |
| **描述 (zh-Hans)** | `解锁无限睡前人声增强、极暗夜读、全屏手势与多设备 iCloud 进度接力` | 审核展示 |
| **显示名称 (en-US)** | `SnoozeBook Pro Lifetime` | 英文展示 |
| **描述 (en-US)** | `Lifetime access to unlimited Voice Boost, Night Reading, Gestures, and iCloud sync.` | 英文展示 |
| **审核备注** | `SnoozeBook Pro provides lifetime access with no recurring subscription fees.` | 审核员参考 |
| **审核截屏** | 截取应用内 `ProPaywallSheet` 界面上传 (1290 x 2796 或 1242 x 2688) | 必须包含价格与权益 |
