# SnoozeBook · App Store Connect 完整上架提审资料包（方案 B：纯本地音频播放工具合规版）

本文档已按照 **中国大陆区无出版物资质合规方案（方案 B）** 全面更新：
- 将主类别调整为 **工具 (Utilities)**、次类别为 **音乐 (Music)**（严禁选择 `图书 Books`）；
- 移除全部文学/图书样书，替换为中英文两段内嵌 4 个章节的 **《SnoozeBook 睡前盲操与声效体验引导》** 语音指南；
- 文案与关键词突出 **「纯离线本地音频播放器 · 睡前盲操手势 · 助眠白噪音与人声增强工具」** 定位，不涉及任何在线书城或电子出版物分发。

---

## 1. App 基本信息 (Basic Information)

| 字段 (Field) | 填写内容 (Value) | 字符上限要求 |
| :--- | :--- | :--- |
| **App 名称 (Name - 简体中文)** | `SnoozeBook - 睡前盲操本地音频播放器` | ≤ 30 字符 |
| **App 名称 (Name - 繁體中文)** | `SnoozeBook - 睡前盲控本機音訊播放器` | ≤ 30 字符 |
| **英文名称 (Name - English)** | `SnoozeBook - Bedtime Audio` | ≤ 30 字符 |
| **副标题 (Subtitle - 简体中文)** | `闭眼全屏手势 · 智能入睡定时与白噪音` | ≤ 30 字符 |
| **副标题 (Subtitle - 繁體中文)** | `閉眼全螢幕手勢 · 智能入睡定時與白噪音` | ≤ 30 字符 |
| **副标题 (Subtitle - English)** | `Eyes-Free Local Audio Player` | ≤ 30 字符 |
| **主类别 (Primary Category)** | **工具 (Utilities)** *(切勿选“图书 Books”)* | - |
| **次类别 (Secondary Category)** | **音乐 (Music)** 或 **健康与健美 (Health & Fitness)** | - |
| **内容分级 (Age Rating)** | **4+** (纯本地音频播放工具，无任何内置出版物或联网内容) | - |
| **版权信息 (Copyright)** | `2026 Kinson. All rights reserved.` | - |
| **SKU** | `SnoozeBook-iOS` | 唯一标识符 |
| **Bundle ID** | `com.kinson.AudiobookPlayer` | 与 Xcode 工程一致 |
| **构建版本 (Build)** | `1.0 (3)` | 已升级至 Build 3 |

---

## 2. 搜索关键词 (Keywords)

> **苹果规则**：上限 100 字符，词与词之间使用半角英文逗号 `,` 分隔，**不要**包含空格。

### 简体中文 (Simplified Chinese)
```text
本地播放器,音频播放器,睡前,助眠,白噪音,睡眠定时,手势,盲操,离线播放,人声增强,播客,M4B,MP3,章节跳转,极暗模式
```

### 繁體中文 (Traditional Chinese)
```text
本機播放器,音訊播放器,睡前,助眠,白噪音,睡眠定時,手勢,盲控,離線播放,人聲增強,播客,M4B,MP3,章節跳轉,極暗模式
```

### English (United States & Global)
```text
audio player,bedtime,sleep timer,eyes free,gestures,night mode,voice boost,offline,mp3,m4b,chapters
```

---

## 3. 宣传文本 (Promotional Text)

### 简体中文
```text
专为关灯闭眼与不便看屏场景打造的纯本地离线音频播放器。支持全屏大触控盲操手势、MP3/M4B章节目录跳转、智能体动入睡检测、录音人声增强与自然助眠白噪音混音。
```

### 繁體中文
```text
專為關燈閉眼與不便看螢幕場景打造的純本機離線音訊播放器。支援全螢幕大觸控盲控手勢、MP3/M4B章節跳轉、智能體動入睡偵測、人聲增強與自然助眠白噪音混音。
```

### English
```text
A local offline audio player built for bedtime and eyes-free moments. Enjoy full-screen blind gestures, MP3/M4B chapter navigation, smart sleep auto-pause, voice boost, and calming soundscapes.
```

---

## 4. 应用详细描述 (Description)

### 简体中文版 (Simplified Chinese)

```text
SnoozeBook 是一款专为「睡前熄灯好眠」与「视线不便看屏（跑步、驾车、做家务）」深度定制的纯本地离线音频播放工具。

本应用为纯粹的本地音频播放工具，不提供、不分发任何在线内容。您可以将自己设备中的 MP3、M4A、M4B、AAC、WAV、FLAC 音频文件导入本地沙盒，在黑暗与闭眼中无需辨认微小按钮，通过全屏触控手势轻松掌控播放。

【解决三大夜间音频播放痛点】
1. 睡前关灯摸索屏幕易被强光刺眼？
➔ 「全屏盲操手势模式」：无需注视屏幕，轻触任意位置即播放/暂停，左右滑动快退快进 15 秒，上下滑动平滑调节系统音量，躺平盲控舒适自如。
2. 听着音频睡着了，第二天醒来找不到上次听到哪里？
➔ 「智能入睡守护 (Smart Sleep)」：利用内置加速度传感器感知身体静止状态。判定入睡后，音量先柔和淡出（轻摇手机即可续播），确认入睡后自动回退 2 分钟并记录播放断点。
3. 本地录音底噪大、声音忽大忽小？
➔ 「睡前人声增强 (Voice Boost)」与「双轨白噪音混音」：提供 0dB / +6dB / +12dB 多级人声动态增强；更可叠加细雨、壁炉、海浪白噪音与舒缓钢琴伴奏，独立调节音量。

【核心功能亮点】
• 📑 MP3 / M4B 章节目录跳转：自动解析音频内嵌章节轨与 ID3 章节标签，支持目录列表预览、当前章节高亮与一键切章。
• 🌙 睡前快捷定时胶囊：主界面与极暗模式均可一键开启智能入睡检测、15/30/45 分钟定时或播完当前音频自动停止。
• 🔢 智能连播与最近播放排序：音频库按最近播放时间自动置顶排序；播放结束后可按文件名编号顺序自动连播下一首（定时到点除外）。
• 🕯️ 极暗护眼光谱模式：深红夜视 (650nm)、暖琥珀 (590nm)、暗月光三种护眼配色，呵护暗视觉。
• ⚡ 100% 本地优先架构：支持通过系统「文件」App、隔空投送 (AirDrop)、电脑访达/iTunes 文件共享导入本地音频，离线秒开，零网络流量依赖。
• ☁️ iCloud 进度接力 (Pro)：在 iPhone / iPad / Mac 之间无缝同步播放断点与设置。
• 💎 一次性买断无广告：无订阅陷阱、零第三方广告、绝不收集个人隐私。
```

### 繁體中文版 (Traditional Chinese)

```text
SnoozeBook 是一款專為「睡前熄燈好眠」與「視線不便看螢幕（跑步、駕車、做家務）」深度打造的純本機離線音訊播放工具。

本應用為純粹的本機音訊播放工具，不提供、不散佈任何線上內容。您可以將自己裝置中的 MP3、M4A、M4B、AAC、WAV、FLAC 音訊檔案匯入本機沙盒，在黑暗與閉眼中透過全螢幕手勢輕鬆掌控播放。

【解決三大夜間音訊播放痛點】
1. 睡前關燈摸索螢幕容易被強光刺眼？
➔ 「全螢幕盲控手勢模式」：無需注視螢幕，輕觸任意位置即播放/暫停，左右滑動快退快進 15 秒，上下滑動微調音量。
2. 聽著音訊睡著了，隔天醒來找不到進度位置？
➔ 「智能入睡守護」：透過機身加速度感測器感知靜止狀態。判定入睡後音量柔和淡出（輕搖手機即可續播），確認入睡後自動回退 2 分鐘並記錄斷點。
3. 本機錄音品質參差、聲音忽大忽小？
➔ 「睡前人聲增強」與「雙軌白噪音混音」：突顯人聲清晰度，並可疊加細雨、壁爐、海浪白噪音與舒緩鋼琴伴奏。

【核心特色】
• 📑 MP3 / M4B 章節跳轉：自動解析音訊內嵌章節，支援目錄預覽與一鍵跳轉。
• 🌙 睡前快捷定時膠囊：主頁與極暗模式皆可 1 秒開啟智能入睡偵測或 15/30/45 分鐘定時。
• 🔢 智慧連播與最近播放排序：音訊庫依最近播放時間排序，並支援依檔名編號順序自動連播。
• 🕯️ 極暗視覺護眼模式：深紅夜視、暖琥珀、暗月光三種低光光譜。
• ⚡ 本機優先架構：支援檔案 App、AirDrop、Finder 匯入 MP3/M4A/M4B，離線秒開。
• ☁️ iCloud 進度接力 (Pro)：跨裝置同步播放斷點。
• 💎 一次性買斷零廣告：無訂閱陷阱、零廣告打擾、絕不收集個人隱私。
```

### English Version (United States & Global Default)

```text
SnoozeBook is a local-first, offline audio player utility purpose-built for bedtime relaxation and eyes-free environments (falling asleep, running, cycling, driving, and doing chores).

SnoozeBook is strictly a local audio playback tool and does not provide or distribute any online content. Import your own MP3, M4A, M4B, AAC, WAV, or FLAC audio files from your device and control everything with full-screen blind gestures.

【SOLVING THREE CORE NIGHTTIME AUDIO PAIN POINTS】
1. Fumbling with tiny buttons in a dark room blinds your eyes?
➔ Full-Screen Blind Gestures: Control playback without looking. Tap anywhere to Play/Pause, swipe horizontally to skip backward or forward 15 seconds, and swipe vertically to smoothly adjust volume.
2. Fallen asleep and lost your playback position until morning?
➔ Smart Sleep Detection: Uses the built-in accelerometer to sense stillness. When you fall asleep, volume gently fades out over 60 seconds (a gentle shake extends playback). Once asleep, it automatically pauses and rewinds 2 minutes.
3. Quiet recordings or harsh volume spikes at night?
➔ Bedtime Voice Boost & Soundscapes: Enhances vocal clarity at whisper volumes (+0dB, +6dB, +12dB) and mixes built-in rain, fireplace, ocean waves, and relaxing piano tracks with independent volume sliders.

【KEY HIGHLIGHTS】
• 📑 MP3 & M4B Chapter Navigation: Automatically parses embedded chapter tracks and ID3 CHAP tags for instant chapter jumping.
• 🌙 Bedtime 1-Tap Sleep Capsule: Quick access to Smart Sleep, 15/30/45 min timers, or End of Track pause on both main and Night screens.
• 🔢 Sequential Auto-Play & Recent Sort: Automatically sorts your library by recently played and auto-advances to the next numbered file.
• 🕯️ Ultra-Dark Night Spectrums: Red Night Vision (650nm) and Amber Glow (590nm) modes protect your eyes in the dark.
• ⚡ 100% Local & Offline: Import audio via the iOS Files app, AirDrop, or Finder File Sharing.
• ☁️ iCloud Progress Sync (Pro): Sync playback positions across iPhone, iPad, and Mac.
• 💎 One-Time Buyout: No subscriptions, no ads, no trackers, and 100% offline privacy.
```

---

## 5. 解决中心直接回复内容 + App 审核备注 (App Review Notes)

### 审核备注与回复 (Notes for Apple Reviewer / Resolution Center Reply)
```text
Dear Apple Review Team,

SnoozeBook is a local-first offline audio file player utility tailored for bedtime listening, screen-free blind gestures, and eyes-free environments (such as falling asleep, running, driving, and doing chores).

Note Regarding Guideline 2.1 (No Book or Magazine Content):
- SnoozeBook is strictly a pure local offline audio player utility (for playing user-imported MP3, M4A, and M4B audio files). It does NOT provide, host, fetch, sell, or distribute any books, magazines, newspapers, or online publications, and has zero network content servers.
- We have removed the previous public-domain literary sample clips and updated our App Store category to "Utilities".

1. Testing Audio Playback, Chapters & Sample Audio Guides:
- Instant Out-of-the-Box Testing: The app comes pre-bundled with 2 self-produced voice-over feature tutorial audio guides (1 Chinese, 1 English) with embedded ID3 chapter tags (4 chapters each) and cover artwork. When opening SnoozeBook for the first time, these 2 audio guides are automatically ready in the library for immediate one-tap playback:
  • Track 1: SnoozeBook 睡前盲操与声效体验引导 (Chinese Audio Guide, 4 embedded chapters, ~2.6MB)
  • Track 2: SnoozeBook Bedtime Gestures & Audio Guide (English Audio Guide, 4 embedded chapters, ~2.2MB)
- Chapter Navigation (TOC): Tap the "目录 / TOC" button or the chapter pill on the main player card to view the 4 embedded chapters and jump directly to any section.
- You can also import any local MP3, M4A, or M4B audio file via the standard iOS Document Picker ("Files" App), Finder / iTunes File Sharing, or AirDrop:
  👉 Sample Audio Guides: https://github.com/kinson5/SnoozeBook/tree/main/samples

2. Full-Screen Gesture Mode:
- On the main player, tap the purple "Gestures (手势)" button.
- Tap anywhere on the black screen to Play/Pause.
- Swipe left/right to rewind/fast-forward 15 seconds.
- Swipe up/down to adjust hardware volume with instant HUD feedback.

3. Smart Sleep Detection & Night Mode:
- Tap "Smart Sleep (智能入睡)" or any preset timer (15/30/45 min) on the bedtime capsule bar (available on both the main player and Night Mode).
- Smart Sleep uses real-time accelerometer motion to sense stillness and gentle movements. When stillness duration is reached, the volume gently fades out over 60 seconds (a gentle shake extends playback). Once asleep, playback pauses and automatically rewinds 2 minutes.

4. In-App Purchase & Daily Free Trial:
- Users enjoy a 5-minute daily free trial of Pro features (Voice Boost +6dB/+12dB, Ultra-Dark Night Mode, and Full-Screen Gestures).
- We offer a one-time non-consumable buyout: "SnoozeBook Pro Lifetime" (Product ID: com.kinson.AudiobookPlayer.pro.lifetime), which unlocks unlimited access to Voice Boost, Night Mode, Full-Screen Gestures, and iCloud Progress Sync via NSUbiquitousKeyValueStore.
- A functional "Restore Purchases" button and clear EULA/Privacy Policy links are prominently included on the paywall.

5. Review Demo Video (Background Audio, Chapters, Motion Sensors & Gestures):
- We have prepared a complete demo video demonstrating chapter navigation, continuous playback, background audio lock-screen controls, full-screen gestures, and in-app purchase functionality:
  👉 Demo Video: https://raw.githubusercontent.com/kinson5/SnoozeBook/main/review_video/SnoozeBook_Review_Demo.mp4

All ambient music tracks included in the app are licensed under CC0 / CC-BY 4.0 Public Domain by Kevin MacLeod (incompetech.com), with complete attribution listed in the in-app "Licenses & Acknowledgments" page.

Thank you for your time and review!
```
