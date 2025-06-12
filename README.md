# Edit-file-word-using-variables
📝 A simple Python desktop tool to upload Word .docx templates and replace placeholders like {{name}} with dynamic values. Built with Python, Tkinter, and python-docx.
# 📝 Word Template Editor (JS Version)

A web-based application that allows users to upload `.docx` templates and fill in dynamic variables (placeholders) like `{{name}}`, `{{date}}`, etc. It's built using **JavaScript** and libraries like `docx-templater` and `PizZip`.

---

## ⚙️ Features

- Upload `.docx` Word template files
- Detect and replace variables like `{{name}}`, `{{email}}`, `{{date}}`, etc.
- Export the filled `.docx` file for download
- Simple and responsive frontend interface
- Works in modern browsers (Chrome, Firefox, Edge)
- Supports Arabic and English content

---

## 🛠️ Tech Stack

- Vanilla JavaScript / or Vue/React (if applicable)
- [`docxtemplater`](https://docxtemplater.com/)
- `pizzip` for `.docx` file handling
- HTML5 + Tailwind CSS (optional for UI)

---

## 🚀 How to Use

1. Upload your `.docx` template that contains placeholders like `{{name}}`
2. Fill the values in the input form
3. Click “Generate Document”
4. Download the filled file instantly

---

## 📸 Screenshot

![screenshot](./screenshot.png)

---

## 🌐 Live Demo

> Coming soon…  
> Or host locally using a simple HTTP server:

```bash
npx serve .
# or
python3 -m http.server 8080
