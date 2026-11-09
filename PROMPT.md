# 乙七｜漫畫博物館 — Vibe Coding Prompt 說明

## 專題目標
將大二乙七「漫畫博物館」影展專題整理成繁體中文展示網站，主軸為「文化保存即永續」。

## 使用的指令與設計需求
請根據成果冊文字與五張原始照片建立完整靜態網站。以米白、墨黑、深橄欖色與暖色照片呈現文化保存的氣氛。包含首頁、專題介紹、廣告企劃、影像紀錄四個獨立 HTML 分頁。提供主要導覽列與內頁側邊欄；使用 CSS Grid、RWD、獨立 css 資料夾與 images 圖片資料夾。加入各頁 title、description、Open Graph、語言標記、圖片替代文字與語意化 HTML。照片可點擊放大，支援鍵盤關閉。僅使用提供資料，不虛構影片網址、獎項或團隊職務。

## 內容依據
使用者提供之乙七成果冊截圖、五張專題照片與 Canva 設計連結。

## 檔案架構
- index.html：首頁
- project.html：專題介紹與團隊
- concept.html：廣告概念與故事
- gallery.html：影像紀錄與 Canva 連結
- css/style.css：獨立樣式與 RWD
- images/：五張專題照片
- gallery.js：圖片放大功能

## 部署
將本資料夾內容放到 InfinityFree 的 htdocs 首頁目錄；GitHub 上傳相同內容並連接 Vercel，選擇 Other 靜態網站、無建置指令。繳交 GitHub 的本 Markdown 檔網址、InfinityFree 首頁網址及 Vercel 部署網址。

## 製作與檢查
以 AI 輔助生成 HTML/CSS/JavaScript，依提供資料整理敘事。檢查內部連結、圖片路徑、分頁及響應式配置。
