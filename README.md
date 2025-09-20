# ppt2pdf

**ppt2pdf** is a sleek, easy-to-use command-line tool for macOS that converts PowerPoint presentations (`.ppt` and `.pptx`) to PDF.

---

## 🌟 Features

- Convert a **single PowerPoint file** to PDF.
- Convert **all **``** and **``** files** in a folder.
- Keeps the **original filename** for the PDF.

---

## 🛠 Requirements

- macOS
- Python 3
- Microsoft PowerPoint installed

---

## ⚡ Installation

1. **Clone the repository:**

```bash
git clone https://github.com/HaoweiLi97/ppt2pdf.git
cd ppt2pdf
```

2. **Make the script executable:**

```bash
chmod +x ppt2pdf
```

3. **Move it to your PATH** to run it anywhere:

```bash
sudo mv ppt2pdf /usr/local/bin/
```

---

## 🚀 Usage

### Convert a single PowerPoint file:

```bash
ppt2pdf /path/to/file/my_presentation.pptx
```

### Convert all PowerPoint files in a folder:

```bash
ppt2pdf /path/to/folder
```

### Convert files in the current folder:

```bash
ppt2pdf
```

---

## 📂 Example

```bash
ppt2pdf ~/Desktop/presentations
```

This will convert all `.ppt` and `.pptx` files in `~/Desktop/presentations` to PDFs in the same folder.

---

## 💡 Notes

- Existing PDF files with the same name will be **overwritten**.
- The script relies on **Microsoft PowerPoint**. Make sure it is installed and licensed.
- No extra Python packages required; uses macOS’s built-in `osascript` for AppleScript execution.

---

## 📝 License

MIT License – feel free to use, modify, and share.

