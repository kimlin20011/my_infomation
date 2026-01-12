# 個人簡歷網站部署指南 / Resume Website Deployment Guide

## 📋 概述 / Overview

這是一個包含英文、中文、日文三種語言的個人簡歷網站，可以輕鬆部署到 GitHub Pages。

This is a trilingual (English, Chinese, Japanese) resume website that can be easily deployed to GitHub Pages.

## 🚀 部署到 GitHub Pages / Deploy to GitHub Pages

### 步驟 1: 創建 GitHub Repository

1. 登入 GitHub
2. 創建新的 repository，命名為 `resume` 或 `[your-username].github.io`
3. 設置為 Public repository

### 步驟 2: 上傳文件

```bash
# 初始化 Git repository
git init

# 添加遠程 repository
git remote add origin https://github.com/[your-username]/[repository-name].git

# 添加 index.html
git add index.html

# 提交
git commit -m "Add trilingual resume website"

# 推送到 GitHub
git push -u origin main
```

### 步驟 3: 啟用 GitHub Pages

1. 進入 repository 的 Settings
2. 點擊左側的 "Pages"
3. 在 "Source" 下拉選單中選擇 "main" branch
4. 點擊 "Save"
5. 等待幾分鐘，您的網站將會在 `https://[your-username].github.io/[repository-name]/` 上線

## 🎨 功能特點 / Features

- ✅ **三語言支援**: 英文、繁體中文、日文可以輕鬆切換
- ✅ **響應式設計**: 在桌面、平板、手機上都能完美顯示
- ✅ **列印友好**: 支援直接列印或匯出 PDF
- ✅ **現代化設計**: 漂亮的漸層配色和流暢的動畫效果
- ✅ **零依賴**: 純 HTML/CSS/JavaScript，不需要任何外部框架

## 🛠️ 自定義 / Customization

### 修改內容

直接編輯 `index.html` 文件：

- **個人資訊**: 修改 header 部分
- **工作經歷**: 修改各語言版本的 experience-item
- **學歷**: 修改 education-item
- **技能**: 修改 skills-grid

### 修改配色

在 CSS 的 `:root` 部分修改顏色變數：

```css
:root {
    --primary-color: #2c5aa0;    /* 主要顏色 */
    --secondary-color: #3d7cc9;   /* 次要顏色 */
    --accent-color: #5a9fd4;      /* 強調顏色 */
}
```

## 📱 使用方式 / Usage

### 切換語言

點擊頂部的語言標籤：
- 🇺🇸 English
- 🇹🇼 中文
- 🇯🇵 日本語

### 列印或匯出 PDF

1. 點擊右下角的 "🖨️ Print / PDF" 按鈕
2. 在列印對話框中選擇 "另存為 PDF"
3. 保存檔案

## 🌐 自訂域名 (選用) / Custom Domain (Optional)

如果您有自己的域名：

1. 在 repository 根目錄創建 `CNAME` 文件
2. 在文件中輸入您的域名，例如：`resume.yourdomain.com`
3. 在您的域名服務商設置 DNS 指向 GitHub Pages

## 📧 聯絡資訊 / Contact

如有任何問題，請通過以下方式聯繫：
- Email: kimlin20011@gmail.com
- Location: Tokyo, Japan

## 📄 授權 / License

此模板可以自由使用和修改。

This template is free to use and modify.

---

**最後更新 / Last Updated**: 2026年1月

