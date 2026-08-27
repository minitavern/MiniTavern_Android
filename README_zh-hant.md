# MiniTavern Android 用戶端 | 安卓酒館 | Silly Tavern Android | Google Play 正式版 | GitHub 官方追蹤版 | 角色卡 | 本機模型 | 酒館 AI | 行動端聊天

<time datetime="2026-08-27">更新於 2026 年 8 月 27 日</time> · Android v1.5.4

![the_best_sillytavern_alternative_android.webp](the_best_sillytavern_alternative_android.webp)

[English](./README.md) | [日本語](./README_jp.md) | [简体中文](./README_zh-hans.md) | [Русский](./README_ru.md)

**MiniTavern** 是一款免費的行動端伴侶應用程式，專為 **SillyTavern** 愛好者打造。  
它將你喜愛的沉浸式 AI 角色扮演與角色對話體驗直接帶到你的 Android 手機——隨時隨地，無需電腦、複雜設定或任何技術知識。

可接入 OpenAI、Anthropic（Claude）、Google Gemini、DeepSeek、Kimi、SpaceXAI 等主流服務；會員持續獲得專屬模型升級。也支援 OpenRouter，以及 Ollama / KoboldCpp / LM Studio 本機模型。

## 下載與更新渠道

- **Google Play（正式渠道 / 建議優先）：**  
  [https://play.google.com/store/apps/details?id=com.kongyouwangluo.minitavern](https://play.google.com/store/apps/details?id=com.kongyouwangluo.minitavern)

<p align="center">
  <img src="MiniTavern_on_Google_Play1_.webp" alt="MiniTavern on Google Play" width="360">
</p>

- **APKPure（無 Google Play 時）：**  
  [https://apkpure.com/minitavern/com.kongyouwangluo.minitavern](https://apkpure.com/minitavern/com.kongyouwangluo.minitavern)

<p align="center">
  <img src="MiniTavern_on_APKPure_2.png" alt="MiniTavern on APKPure" width="360">
</p>

- **GitHub 官方追蹤版（商店審核存在時間差時）：**  
  [https://github.com/minitavern/MiniTavern_Android/releases](https://github.com/minitavern/MiniTavern_Android/releases)

> **更新說明：** 長期安裝與更新請以 **Google Play** 為主。  
> 沒有 Google Play 時，可使用 APKPure。  
> 當商店審核節奏不穩定時，GitHub 官方追蹤版用於同步目前可用的最新版。

無論你熱衷於深度角色扮演、練習約會對話、透過沉浸式聊天學習語言，還是只想與 AI 角色尋求情感陪伴，MiniTavern 都能帶來流暢愉快的行動體驗。

## 近期重大更新

- **v1.5.4（目前）：** 修復開啟串流後聊天無法使用；修復角色卡與歷史紀錄匯出、跨裝置匯入。[更新說明](https://mini-tavern.com/blog/zh-tw/silly-tavern-app/minitavern-android-v1-5-4-update)
- **v1.5.2 / v1.5.3：** 會員隨想（本機筆記，會員 AI 圍繞隨想回覆且不扣 App 額度）；對話存檔點（匯出含聊天紀錄的 PNG）；聊天中改卡立即生效並保留歷史；支援帶多模態標記的模型發圖。[更新說明](https://mini-tavern.com/blog/zh-tw/silly-tavern-app/minitavern-v1-5-3-ios-android-update)
- **v1.5.0 / v1.5.1：** 全域模型設定（不再依角色卡各配一套）；Kimi / OpenRouter 專用入口；KoboldCpp / LM Studio 走 OpenAI 協定；會員模型升級到 GPT-5.5、Claude Fable 5；對話頁快速切換模型。[更新說明](https://mini-tavern.com/blog/zh-tw/silly-tavern-app/minitavern-v1-5-1-ios-android-update)

## 核心功能

- **完整支援 SillyTavern 角色卡**  
  輕鬆匯入 SillyTavern 的 .png 或 .json 角色卡（含內建範例、社群分享，支援圖片/URL 匯入）。

- **廣泛相容 AI 服務**  
  可連接主流服務商，包括：  
  - OpenAI  
  - Anthropic（Claude）  
  - Google Gemini  
  - DeepSeek  
  - Kimi  
  - SpaceXAI  
  - Nvidia  
  - OpenRouter（聚合多模型）  
  - Ollama、KoboldCpp、LM Studio（本機模型）  
  - 及其他相容 OpenAI 介面的端點

- **行動優先設計**  
  介面簡潔直觀，專為觸控螢幕從零構建——無桌面端的笨重感，文字清晰易讀。

- **注重隱私，本機儲存**  
  你的角色卡、API 金鑰、聊天紀錄及設定**僅儲存於本裝置上**。  
  我們的伺服器不會接收任何上傳資料。解除安裝應用程式後所有資料隨之刪除。

- **核心體驗完全免費**  
  基本聊天、匯入角色以及使用自有 API 金鑰均無需付費。

- **離線支援**  
  使用本機模型（Ollama、KoboldCpp 或 LM Studio）可實現完全私密、無需連網的聊天。

## 為什麼選擇 MiniTavern Android 版？

傳統 SillyTavern 設定功能強大，但以桌面端為主，通常需要繁瑣的技術配置。  
MiniTavern 消除了這些門檻——無需 Root、無需 Termux、無需 Linux 模擬器、無需埠轉發。  
只需安裝、匯入角色（或使用內建範例）、填入 API 金鑰（或使用免費額度），即可開始聊天。

若你只透過官方商店更新，按 Google Play 流程使用即可。  
若沒有 Google Play，可使用上方 APKPure。  
若希望在審核排隊期間先取得目前可用最新版，可使用上方 GitHub 官方追蹤版。

**官方網站：** [https://mini-tavern.com](https://mini-tavern.com)
