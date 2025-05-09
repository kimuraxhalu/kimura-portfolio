# GitHub Pages部署步驟指南

以下是如何快速將你的作品集網站部署到GitHub Pages的詳細步驟，讓你能立即上線並用於求職展示。

## 1. 建立本地專案資料夾

將提供的檔案放入一個名為`kimura-portfolio`的專案資料夾:

kimura-portfolio/ │ ├── index.html ├── css/ │ └── styles.css ├── js/ │ └── main.js ├── README.md └── .gitignore

## 2. 初始化Git倉庫

在專案資料夾中打開終端機並執行:

```bash
# 初始化git倉庫
git init

# 添加所有檔案
git add .

# 進行第一次提交
git commit -m "Initial portfolio website"


3. 在GitHub上創建新倉庫
	1	登入你的GitHub帳戶
	2	點擊右上角的"+"按鈕，然後選擇"New repository"
	3	輸入倉庫名稱: kimura-portfolio (或自訂名稱)
	4	保持公開選項
	5	不要勾選"Initialize this repository with a README"
	6	點擊"Create repository"
4. 連接並推送到GitHub
在終端機中執行:
# 添加遠端倉庫
git remote add origin https://github.com/你的用戶名/kimura-portfolio.git

# 推送到GitHub
git branch -M main
git push -u origin main

5. 啟用GitHub Pages
	1	在GitHub上打開你的新倉庫
	2	點擊"Settings"標籤
	3	在左側導航欄中點擊"Pages"
	4	在"Source"部分，選擇"main"分支
	5	點擊"Save"按鈕
	6	等待幾分鐘，你會看到一個綠色的通知，顯示你的網站已發布，並提供連結

6. 訪問網站
GitHub Pages通常會為你的網站提供如下格式的URL:

https://你的用戶名.github.io/kimura-portfolio/
7. 更新網站內容
如需更新網站內容:
	1	在本地編輯檔案
	2	使用git提交更改:

bash
git add .
git commit -m "更新說明"
git push origin main
GitHub Pages會自動更新你的網站，通常在幾分鐘內完成。
使用Cursor AI快速部署
如果你有Cursor AI編輯器，可以簡化這個過程:
	1	在Cursor AI中打開專案資料夾
	2	按下 Cmd+K (Mac) 或 Ctrl+K (Windows)
	3	輸入: "幫我初始化Git倉庫並部署這個網站到GitHub Pages"
	4	根據Cursor AI提供的指示操作
求職準備提示
	1	確保在GitHub個人資料中添加這個專案的連結
	2	在履歷和求職申請中使用這個作品集網站的URL
	3	考慮購買自訂域名以獲得更專業的形象
現在你的作品集網站已經準備好用來求職了！祝你面試順利！



