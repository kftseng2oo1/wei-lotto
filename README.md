# AI 歷史權重分析預測系統

匯入大樂透歷史開獎資料，做頻率、冷熱、奇偶、遺漏值、連號分析，用權重模擬選號並輸出簽注單。

**線上使用**：https://kftseng2oo1.github.io/wei-lotto/

## 主要功能
- 資料匯入：Excel、CSV／文字、ZIP（自動偵測台灣彩券官方欄位格式），或手動輸入熱門號碼與比例
- 分析：📊 頻率排行、❄️ 冷熱、⚖️ 奇偶大小、📉 遺漏值、🔗 連號
- ⚡ AI 校準：依歷史資料計算每個號碼的權重
- 🎯 模擬選號：依權重抽號
- 匯出：簽注單（Excel）、分析報告（Excel）、🖨️ 列印簽注單
- 匯入的資料存在 IndexedDB，下次開啟自動還原

## 技術與依賴
- 單檔 HTML；SheetJS、JSZip（cdnjs）
- 目前沒有 `manifest.json` 與 `sw.js`，還不能安裝成 App

## 備註
- 彩券開獎是獨立隨機事件，歷史權重不會提高中獎機率，結果僅供娛樂。
- 相關：[lotto](https://github.com/kftseng2oo1/lotto)（台灣彩券分析系統，含威力彩）、[LT33](https://github.com/kftseng2oo1/LT33)（真隨機搖號機）
