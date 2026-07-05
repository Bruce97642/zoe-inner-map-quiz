# zoe-inner-map-quiz 專案指示

本專案受使用者(王少宇)的「模型交接鐵律」約束,完整版見
`C:\Users\User\.claude\projects\C--Users-User\memory\future-model-ironlaw.md`。
重點:過程可見、異動要記錄在 `異動紀錄.md`、對外動作(推上 GitHub / 部署 / 發文)先確認、修改前先問「我修還是你修」。

## 專案是什麼
「ZOE 內在阻礙地圖測驗」— 純前端單頁測驗網站,給 ZOE 療癒與內在轉化研究院(心靈 Love Beauty 香氣感官所)的客人做自我覺察測驗,結果頁導流到官方 Line 與 Google 預約表單。

- 內容來源:使用者的兩份 Google 表單
  1. 情緒芳療支持系統預約表(已發布)— 情緒/觸發/影響/決心等題目
  2. 內在阻礙地圖評估表(草稿)— 「文字敘述 + 0–10 評分」五向度架構(原表只完成「行為」,其餘四向度為依同模式延伸)
- 計分:情緒負載指數 / 五向度覺察力(雷達圖) / 行動準備度 → 四種類型
- 無後端:客人「複製結果」貼到 Line 給 ZOE,資料不上傳

## 技術
- 單一 `index.html`(vanilla HTML/CSS/JS,Noto Sans/Serif TC),無建置流程
- 部署:GitHub Pages(repo: Bruce97642/zoe-inner-map-quiz, branch main)
- 要改連結:`index.html` 內 `CONFIG` 區塊(LINE_URL / BOOKING_URL)

## 慣例
- 一律繁體中文
- 改版後更新 `異動紀錄.md` 再 commit
