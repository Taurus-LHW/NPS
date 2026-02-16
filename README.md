Markdown
# NotebookLM PPTX Studio 📝➡️📊

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Made with Gemini](https://img.shields.io/badge/AI-Gemini_Pro-orange)](https://deepmind.google/technologies/gemini/)


**NotebookLM PPTX Studio** 是一款基於 Web 的 AI 簡報重製工具。它能將筆記、講義或舊投影片的圖片（或 PDF），透過 **Google Gemini Vision AI** 進行語義分析與版面重組，最終轉換為**真正可編輯**的 PowerPoint (.pptx) 檔案。

🔗 **[點此線上直接使用(Demo)](https://taurus-lhw.github.io/NPS/)** 
![Screenshot 2026-02-17 030505](https://github.com/user-attachments/assets/7bb2fd8a-96c7-40d3-b2ce-f44cc235f25f)
![Screenshot 2026-02-17 030400](https://github.com/user-attachments/assets/11891af9-8bf2-4393-959d-4577a4715ac6)


## ✨ 主要功能 (Features)
* **🧠 AI 智慧分析：** 使用 Gemini 3 / 2.5 Pro 模型，精準辨識標題、內文、列表與圖片區塊，而非單純的文字辨識。
* **🔒 雙模式支援：**
    * **雲端 AI 模式：** 極高精準度，具備邏輯重組能力 (需自備 Gemini API Key)。
    * **離線模式：** 內建 Tesseract.js，在無網路或無 Key 狀態下也能進行基礎 OCR。
* **🎨 視覺化編輯器：** 提供所見即所得 (WYSIWYG) 的介面，可手動微調遮罩範圍、文字內容與排版。
* **📥 一鍵匯出 PPTX：** 自動生成投影片母片，保持版面整潔，不再是「一張大圖貼在 PPT 上」。
* **🛠️ 隱私優先：** 純前端架構 (Single Page Application)，您的 API Key 僅儲存於本地瀏覽器 (LocalStorage)，不會上傳至任何第三方伺服器。

## 🚀 快速開始 (Quick Start)

### 方法一：直接使用 (推薦)
前往 [GitHub Pages NPS 頁面](https://taurus-lhw.github.io/NPS/)，填入你的 Google Gemini API Key 即可開始使用。

### 方法二：本地執行
如果你想在本地端運行或修改程式碼：下載此專案：
```bash git
clone https://taurus-lhw.github.io/NPS/
```

直接用瀏覽器開啟 index.html。
注意：由於瀏覽器安全性限制 (CORS)，建議使用 VS Code 的 "Live Server" 套件開啟，以獲得最佳體驗。

## 🔑 關於 API Key
本專案需要 Google Gemini API Key 才能發揮 100% 效能，推薦使用Gemini 3.0 flash。


👉 [點此免費獲取 Gemini API Key](https://aistudio.google.com/app/apikey)


本工具也支援 Tesseract 離線模式，但準確度與排版效果會低於 AI 模式。

## 🛠️ 技術棧 (Tech Stack)
Frontend: HTML5, Tailwind CSS (via CDN)

AI/OCR: Google Gemini API, Tesseract.js, OpenCV.js

Export: PptxGenJS

PDF Handling: PDF.js

## 🤝 貢獻 (Contributing) ##
歡迎提交 Issue 回報 Bug，或發送 Pull Request 來改進功能！
如果你覺得這個專案對你有幫助，請別忘了給我一顆星星 ⭐！

## ☕ 支持開發者 (Support Me)
維護開源專案需要熱情與咖啡因的轉換。如果你喜歡這個工具，歡迎請我喝杯咖啡，這將支持我繼續開發更多好用的功能！
[buymeacoffee.com/taurus.lhw](https://buymeacoffee.com/taurus.lhw)

<a href="https://buymeacoffee.com/taurus.lhw" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>
<img width="100" height="100" alt="bmc_qr"  src="https://github.com/user-attachments/assets/412b391c-4066-4bfd-b1d0-f25b68719c74" />


## 📜 授權 (License)
本專案採用 GNU Affero General Public License v3.0 (AGPLv3) 授權。

這意味著：

您可以自由下載、修改和使用本程式碼。

如果您修改了本程式碼並透過網路提供服務（例如架設網站給他人使用），您必須公開您的完整原始碼。

您的修改版本必須維持相同的 AGPL v3 授權。

<p align="center">Made with ❤️ by L.HW</p>
