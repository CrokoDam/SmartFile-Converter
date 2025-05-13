# SmartFile Converter

SmartFile Converter is a powerful and polished Python CLI tool for converting files between formats like PDF, DOCX, TXT, Markdown, and Images. It supports batch processing, basic formatting preservation, and metadata extraction.

## 🚀 Features
- ✅ Convert between:
  - Word (.docx) ↔ PDF *(partial support)*
  - PDF ↔ Text (.txt)
  - Word ↔ Markdown (.md)
  - Image (.png, .jpg) ↔ PDF
- ✅ Batch conversion support
- ✅ Basic formatting preserved
- ✅ Metadata extraction (author, creation date)
- ✅ Intuitive CLI using `typer`
- ✅ Logging of all operations

## 📦 Installation
```bash
git clone [https://github.com/CrokoDam/smartfile-converter.git](https://github.com/CrokoDam/SmartFile-Converter)
cd smartfile-converter
pip install -r requirements.txt

Convert running the below (Make sure the files you want to conver are in the same folder as converter.py)

# Convert PDF to DOCX
python converter.py --input input.pdf --to docx

# Convert DOCX to Markdown
python converter.py --input file.docx --to md

# Convert multiple images to PDF
python converter.py --input img1.jpg img2.png --to pdf

# Extract metadata from PDF
python converter.py --input file.pdf --metadata
