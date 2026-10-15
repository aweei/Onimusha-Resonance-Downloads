# Onimusha Resonance 鬼武者共鳴

《鬼武者 Way of the Sword》PC 版的非官方 DualSense 外掛。
 本外掛主要功能是可以讓使用 DualSense 控制器的玩家，將遊戲中招架、彈開、一閃、吸魂等動作，從 DualSense 控制器的喇叭發出相對應的音效，提高遊戲的沉浸感。

> 本外掛不會重現 PS5 版原生觸覺回饋，亦與 Capcom、Sony 或遊戲開發團隊無關。

## 下載

請到本專案的 [Releases](https://github.com/aweei/Onimusha-Resonance-Downloads/releases) 頁面，下載最新版本的 `Onimusha-Resonance-<版本>-win-x64.zip` 並解壓縮。

## 使用需求

- Windows 10/11 x64 與《鬼武者 Way of the Sword》PC 版。
- DualSense 控制器，使用 USB 連接。
- [.NET 10 Windows x64 執行階段](https://dotnet.microsoft.com/download/dotnet/10.0)，不需要安裝 SDK。
- 與目前遊戲版本相容的 [REFramework](https://github.com/praydog/REFramework)。
- 從 DualSense 喇叭播放互動音效需要使用 USB 連線，以及安裝 [DualSenseX／DSX](https://github.com/Paliverse/DualSenseX/releases)，並在 Windows 啟用 DualSense 音訊裝置。

## 安裝與啟動

1. 先將 REFramework 安裝到遊戲資料夾。
2. 解壓縮下載的外掛 ZIP。
3. 執行 `Setup.cmd`。如果程式詢問遊戲位置，請選擇包含 `OnimushaWotS.exe` 的資料夾。
4. 等待設定程式從你自己的遊戲檔案建立必要資料。首次設定需一些時間及約 2 GB 可用空間；遊戲音效檔不會隨外掛下載。
5. 連接 DualSense。以 USB 連接並啟動 DualSenseX／DSX，然後開啟 設置/控制器/控制器音訊系統(僅限使用USB)。
6. 執行 `Start-Mod.cmd` 後開始遊戲。外掛會在啟動視窗開啟期間運作；關閉視窗即可停止。

外掛只會把互動提示音送到 DualSense 喇叭；遊戲其他聲音仍可由電腦喇叭播放。無須將 DualSense 設為 Windows 預設播放裝置。

## 移除

關閉遊戲後執行 `Uninstall.cmd`。如不再需要，也可刪除解壓縮的外掛資料夾。

## 問題回報

請在 GitHub 的 [Issues](https://github.com/aweei/Onimusha-Resonance-Downloads/issues) 提供遊戲版本、問題描述與 `data/bridge.log`。分享記錄前請先檢查是否含有個人資訊。

外掛原始碼採 MIT 授權；發行 ZIP 內附授權與第三方元件聲明。遊戲素材由使用者本機遊戲檔案產生，不隨外掛發行。

本專案由 ChatGPT 100% 撰寫而成。


## 免責聲明 (Disclaimer)

1. 本作品為個人非營利性質之衍生創作，旨在優化個人遊戲沉浸體驗。
2. 本軟體係按「原樣」（AS IS）提供，不保證其相容性、穩定性或無特定瑕疵。
3. 作者對於因下載、安裝或使用本作品所引致之任何直接、間接損害（包括但不限於資料遺失、存檔毀損或帳號異常），均不負任何法律或賠償責任。玩家請自行評估風險並做好資料備份。
