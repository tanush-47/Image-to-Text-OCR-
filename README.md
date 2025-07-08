Image to Text OCR
This project is a simple Optical Character Recognition (OCR) tool built using Python. It extracts readable text from images using the pytesseract library and displays the output for further use or processing.

🔍 Features
Convert printed or handwritten text in images to digital text.

Supports various image formats (.jpg, .png, .jpeg, etc.).

Easy-to-use interface for uploading images.

Displays extracted text in a user-friendly format.

🛠️ Tech Stack
Python

OpenCV

pytesseract (Tesseract-OCR)

🚀 Installation
Clone the Repository

bash
Copy
Edit
git clone https://github.com/tanush-47/Image-to-Text-OCR-.git
cd Image-to-Text-OCR-
Install Required Libraries

bash
Copy
Edit
pip install -r requirements.txt
Install Tesseract-OCR Engine

Windows: Download and install from Tesseract OCR Windows Installer

Linux:

bash
Copy
Edit
sudo apt install tesseract-ocr
Configure Tesseract Path (if needed)

python
Copy
Edit
pytesseract.pytesseract.tesseract_cmd = r'C:\Program Files\Tesseract-OCR\tesseract.exe'  # For Windows
🖼️ How to Use
Run the script:

bash
Copy
Edit
python image_to_text.py
Upload an image file.

The script will process the image and print the extracted text.

📄 Example
Input Image:

Output Text:

vbnet
Copy
Edit
Welcome to OCR using Python!
📌 To-Do
Add GUI support (Tkinter/Streamlit).

Support multi-language OCR.

Text-to-speech conversion from OCR output.
