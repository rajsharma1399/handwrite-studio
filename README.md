# handwrite-studio
# ✍️ Handwrite Studio A4 Pro

A modern, client-side web application built with **Tailwind CSS** that converts any digital text, book excerpt, PDF, or Word document (`.docx`) into authentic, human-like handwritten notes formatted across precise **A4 pages**. 

Designed for students, educators, and creators who want clean, realistic, and printable handwritten notes without relying on a backend server.

---

## ✨ Key Features

* **📄 Real A4 Page-by-Page Pagination:** Automatically splits long books, PDFs, and notes into multiple realistic A4 sheets with page numbers and margins.
* **📂 Multi-Format File Support:** 
  * Upload and parse **PDF** books/documents (`pdf.js`)
  * Upload and extract text from **Word Documents (`.docx`)** (`mammoth.js`)
  * Upload plain text files (`.txt`)
  * Direct copy-paste and text editing
* **✍️ Real Handwriting Cloner:** Upload an image of your own handwriting sample (`.png` / `.jpg`) to map your personal handwriting style onto the generator.
* **🎨 Advanced Customization Options:**
  * **Handwriting Styles:** Choose between *Caveat*, *Kalam*, *Indie Flower*, *Patrick Hand*, and *Sacramento*.
  * **Pen Inks:** Royal Blue, Classic Black, Dark Red, Emerald Green, Purple, and Graphite Pencil.
  * **Paper Backgrounds:** Lined Notebook, Grid / Graph Paper, Legal Pad (Yellow), and Plain White A4.
* **🪄 Human Imperfection Engine:** Fine-tune line spacing, word spacing, and baseline jitter so characters look naturally organic rather than machine-generated.
* **💾 Multi-Format Exports:** 
  * Download all pages instantly as high-resolution PNG images.
  * Download as a structured, print-ready A4 PDF document.
  * Built-in direct print support.

---

## 🚀 Live Demo

You can view and use the live application hosted via GitHub Pages:  
👉 **[https://<your-github-username>.github.io/<repository-name>/](https://<your-github-username>.github.io/<repository-name>/)**

---

## 🛠️ Built With

* [Tailwind CSS](https://tailwindcss.com/) - Modern utility-first CSS framework for responsive UI styling.
* [PDF.js](https://mozilla.github.io/pdf.js/) - Client-side PDF text extraction library.
* [Mammoth.js](https://github.com/mwilliamson/mammoth.js) - `.docx` to raw text parser.
* [html2pdf.js](https://eKoopmans.github.io/html2pdf.js/) - Client-side canvas rendering and PDF/PNG export bundle.
* Google Fonts (`Caveat`, `Kalam`, `Indie Flower`, `Patrick Hand`, `Sacramento`).

---

## 📦 Quick Local Setup & GitHub Deployment

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/handwrite-studio.git](https://github.com/your-username/handwrite-studio.git)
   cd handwrite-studio
