# 🛠️ PDF Utility Tool – All-in-One PDF AND other file formats Processor

This is a powerful and modular **Python-based PDF Utility Tool** that enables you to handle nearly every aspect of PDF and other file formats manipulation. It combines various libraries to offer a unified command-line interface for organizing, editing, optimizing, converting, and securing PDF files.

---

## 🚀 Features

### 📁 Organize PDFs

* **Merge PDFs**: Combine multiple PDF files into one.
* **Split PDFs**: Break a PDF into individual pages.
* **Remove Pages**: Delete specific pages from a PDF.
* **Extract Pages**: Create a new PDF with selected pages from another.
* **Scan to PDF**: Convert image files into a scanned PDF.

### 🧹 Optimize PDFs

* **Compress PDF**: Reduce file size without major quality loss.
* **Repair PDF**: Rebuild potentially corrupt or unreadable PDFs.
* **OCR PDF**: Extract text from scanned PDFs using Optical Character Recognition (OCR).

### 🔁 Convert To PDF

* **Images to PDF**: Convert JPG images into PDF format.
* **Word to PDF** *(Placeholder)*: Add Word-to-PDF functionality using `python-docx` and `reportlab`.
* **PowerPoint to PDF** *(Placeholder)*: Planned integration using `python-pptx`.
* **Excel to PDF** *(Placeholder)*: Excel to PDF via `pandas` and `reportlab`.
* **HTML to PDF** *(Placeholder)*: Use `pdfkit` or `weasyprint` to convert web content into PDFs.

### 🔄 Convert From PDF

* **PDF to JPG**: Turn each page of a PDF into high-quality images.
* **PDF to Word**: Extract readable text and export as a `.docx` file.
* **PDF to PowerPoint** *(Placeholder)*: Future support planned.
* **PDF to Excel**: Extract tabular data using `tabula` and save as `.xlsx`.
* **PDF to PDF/A**: Convert regular PDFs to the archival-friendly PDF/A format.

### ✏️ Edit PDFs

* **Rotate Pages**: Rotate all pages by 90°, 180°, or 270°.
* **Add Page Numbers**: Stamp page numbers onto every page.
* **Add Watermarks**: Overlay text watermarks to existing pages.
* **Basic Edit**: Copy contents to a new PDF for minor adjustments.

### 🔐 PDF Security

* **Unlock PDF**: Decrypt password-protected PDFs.
* **Protect PDF** *(Coming soon)*: Add password protection to PDF files.

---

## 🧰 Dependencies

* `PyPDF2`
* `pdf2image`
* `reportlab`
* `pdfplumber`
* `tabula-py`
* `pdfminer.six`
* `pytesseract`
* `Pillow (PIL)`

> 📌 Make sure to install system-level dependencies for tools like Tesseract OCR and Java (for `tabula`).

```bash
pip install PyPDF2 pdf2image reportlab pdfplumber tabula-py pdfminer.six pytesseract Pillow
```

---

## 📂 Output

All generated files (merged, edited, converted, etc.) are stored in an `output_files` directory, which is automatically created if it doesn’t exist.

---

## ✅ Usage

Run the script and follow the on-screen prompts to perform your desired operation. Each function is modular and works independently.

---

## 📌 Note

Some functionalities are placeholders and need third-party libraries like `python-docx`, `python-pptx`, or `pdfkit` to be fully implemented. These are already stubbed in the code for future expansion.

---

## 👨‍💻 Author

This utility was developed as part of a full-featured PDF and other file formats processing suite intended to streamline document handling workflows using Python.
