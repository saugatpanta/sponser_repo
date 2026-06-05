<p align="center">
  <img src="https://img.shields.io/badge/Apex-Pitch%20%26%20Pop-7B1C1C?style=for-the-badge&labelColor=1a0808" />
  <img src="https://img.shields.io/badge/A4-PDF%20Export-333?style=for-the-badge" />
  <img src="https://img.shields.io/badge/300%20DPI-Print%20Ready-0d1e0d?style=for-the-badge" />
</p>

<h1 align="center">⚜ Apex Sponsorship Agreement Builder</h1>

<p align="center">
  <strong>A sleek, browser-based tool to generate professional sponsorship agreements for Apex Pitch & Pop 2026.</strong><br>
  No server needed. No dependencies to install. Just open and build.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML-single%20file-e34c26?style=flat-square&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/Export-PDF%20%7C%20PNG-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Storage-LocalStorage-orange?style=flat-square" />
</p>

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 📄 **Live A4 Preview** | WYSIWYG dual-page document with real-time editing |
| 🎨 **Theme Customization** | 7 accent colors, adjustable watermark, custom logos |
| 💰 **Tier Templates** | Pre-built content for Platinum, Gold, Silver, Bronze, Stall packages & more |
| ⬇️ **High-Quality Export** | PDF & PNG at 2480×3508 px (A4 @ 300 DPI) |
| 💾 **Auto-Save** | Every keystroke saved to localStorage with version history |
| ✏️ **Inline Editing** | Click any text to edit directly on the document |
| 📋 **Section Manager** | Reorder, add, or delete sections from the sidebar |
| 🔴 **Bullet Manager** | Hover-to-delete, right-click menu, or backspace removal |
| 🖼 **Logo Uploads** | Club logo, event logo, college logo — all customizable |
| 📦 **JSON Backup** | Export/import full document state as JSON |

---

## 🚀 Getting Started

```bash
# Just open the file in any modern browser
open sponser.html
```

That's it. No build step, no `npm install`, no server.

---

## 📖 Usage

1. **Open** `sponser.html` in your browser
2. **Fill in** sponsor details in the sidebar (Info tab)
3. **Select a tier** — content auto-populates based on the package
4. **Edit inline** — click any text on the document to modify
5. **Upload logos** — Design tab → drag or click to upload
6. **Export** — Switch to Export tab → Download PDF or PNG

---

## 🏗 Architecture

```
sponser.html          ← Single-file application (HTML + CSS + JS)
├── Sidebar Panel     ← Info, Content, Design, Export tabs
├── Page 1 (A4)       ← Agreement intro, obligations, IP clause
├── Page 2 (A4)       ← General conditions, signature block
└── Local Storage     ← Auto-persisted document state
```

**Libraries used (CDN):**
- [html2canvas](https://html2canvas.hertzen.com/) — DOM-to-canvas rendering
- [jsPDF](https://github.com/parallax/jsPDF) — PDF generation

---

## 🎯 Sponsorship Tiers

| Tier | Amount (NPR) |
|------|-------------|
| Platinum | 3,50,000 |
| Gold | 3,00,000 |
| Silver | 2,50,000 |
| Bronze | 2,00,000 |
| In-Kind | 50,000+ |
| Stall (per day) | 15,000 |
| Stall (full event) | 45,000 |

---

## 🖥 Browser Support

| Chrome | Firefox | Safari | Edge |
|--------|---------|--------|------|
| ✅ | ✅ | ✅ | ✅ |

---

## 📝 License

Built for **Apex Media and Marketing Club** — Apex College, Mid-Baneshwor, Kathmandu.

---

<p align="center">
  <sub>Made with ❤️ for Apex Pitch & Pop 2026</sub>
</p>
