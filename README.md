# 🛠️ PDF and Passion: Terminal-Themed LaTeX Resume

[![Compiler](https://img.shields.io/badge/Compiler-pdfLaTeX-green.svg)](https://www.latex-project.org/)
[![Vibe](https://img.shields.io/badge/Theme-Cybersecurity%20%2F%20VSCode-blueviolet.svg)]()
[![User](https://img.shields.io/badge/Developer-Neo--woupier-orange.svg)](https://github.com/Neo-woupier)

Welcome to my personal resume repository. This isn't just a standard, boring CV. This project is a **typeset-from-scratch \LaTeX\ document** meticulously crafted to look like a live CLI/Terminal environment, complete with simulated multi-page frame animations.

---

## 🚀 Features

* **Manual Flipbook Animation:** The first 3 pages simulate a Windows CMD terminal rendering a `/info` command frame-by-frame when scrolling down.
* **Developer Dashboard Theme:** The main profile page mimics a dark-mode IDE/VS Code interface containing structured student data.
* **System Overrides (The Passion Log):** A custom Linux-inspired boot-up kernel log (`dmesg`) screen that outputs my raw, unfiltered philosophy on life and discipline.
* **Dynamic QR Code Generation:** Embedded compiler-level QR code linking directly back to my GitHub portfolio.

---

## 📂 Repository Structure

```
PDF-and-Passion/
├── Main.tex       # Core LaTeX Source Code (The Engine)
├── README.md      # Project documentation (You are here)
├── Me.jpg         # Profile picture asset
├── Idol.jpg       # Mentor/Inspiration image asset
└── behind.png     # Behind-the-scenes pipeline screenshot
```


🛠️ System Requirements & Dependencies
To locally compile or fork this project, your TeX distribution needs to support the following packages:

xcolor - For terminal ANSI/Hex code color mapping (CMD_Black, VSCodeBG).

graphicx - For processing and rendering geographic image bounds.

hyperref - For compiling stable active anchor links inside the PDF.

qrcode - For generating low-error vector QR codes on the fly.

Recommended Compiler: pdfLaTeX (TeX Live 2020+, MiKTeX, or Overleaf).

💻 How to Compile
1. Clone this repository into your local workspace or upload assets directly to Overleaf:

```
git clone [https://github.com/Neo-woupier/PDF-and-Passion.git](https://github.com/Neo-woupier/PDF-and-Passion.git)
```

2. Ensure Me.jpg and Idol.jpg are present in the same root folder as Main.tex.

3. t your internal compilation engine to pdfLaTeX.

3. Hit Compile/Recompile. The machine will output a multi-page interactive PDF document.

🧠 The "Passion" Logic (Behind the Logs)
Inside the kernel log terminal page, you will find this core statement overridden into the system:

"Just a kid trying to level up in life. When your background, family, and financial constraints leave absolutely no room for surrender... Even if you don't have a specific 'passion', the sheer refusal to give up BECOMES the passion itself."

Developed with 💻, ☕, and pure discipline by NruNew (Neo-woupier).