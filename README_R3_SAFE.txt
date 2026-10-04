Junba AI Transcriber v3.8.2 APK R3 Safe
========================================

用途：Android APK 專用完整 GitHub 專案，不修改 Windows 版。

本版基底：
- 以 2026-10-04 實機曾成功開啟、Gemini 長音訊可執行的 1004-1 Android 程式為母版。
- 不延續 R1/R2/R2.1/R2.2 的 MainActivity 啟動結構。

R3 Safe 改善：
1. API Key 儲存後，第一個畫面建立完成才自動收折；需要修改可再展開。
2. Whisper / Gemini / 模型下載 / 存檔工作顯示進度、約略區間、已執行時間與「仍在執行」。
3. 逐字稿預覽框可上下完整捲動，提供「最前 / 最後」按鈕；有時間標記時依時間順序整理。
4. 「儲存本次」會建立 Documents/Junba AI Transcriber/YYYY-MM-DD/YYYY-MM-DD_HHmmss/。
5. 以上資料夾保留原始音檔原檔名，另存同名 TXT / Markdown。
6. 啟動保護：若特定手機在新增介面元件發生例外，App 會顯示 R3 Safe 啟動錯誤，而不是直接閃退回桌面。

GitHub：
- 解壓後把第一層全部上傳到新的 Repository 根目錄。
- Actions 執行：Build Junba Android APK v3.8.2 R3 Safe
- Artifact：Junba-v382-APK-R3-Safe
- APK：Junba-R3-Safe.apk

版本：
- versionCode 387
- versionName 3.8.2-apk-r3-safe
