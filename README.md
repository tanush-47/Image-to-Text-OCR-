# 🖼️ Image to Text OCR

A simple Python project to extract text from images using Optical Character Recognition (OCR) with `pytesseract`.

## 📌 Features

- Extracts text from images (JPG, PNG, etc.)
- Uses Tesseract OCR via `pytesseract`
- Easy and minimal code

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/tanush-47/Image-to-Text-OCR-.git
cd Image-to-Text-OCR-
```

### 2. Install Requirements

```bash
pip install -r requirements.txt
```

### 3. Install Tesseract-OCR

- **Windows**: [Download Installer](https://github.com/tesseract-ocr/tesseract/wiki)
- **Linux**:
```bash
sudo apt install tesseract-ocr
```

Update the Tesseract path in your code (for Windows):

```python
pytesseract.pytesseract.tesseract_cmd = r'C:\Program Files\Tesseract-OCR\tesseract.exe'
```

## 🧪 Usage

Run the script:

```bash
python image_to_text.py
```

It will load the image and print the extracted text to the terminal.

## 📷 Example

**Input:** An image with printed or handwritten text  
**Output:** Extracted text in the terminal

## 📃 License

MIT License
