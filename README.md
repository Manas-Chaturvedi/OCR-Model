# OCR-Model
This repository contains implementation of Optical Character Recognition (OCR) . It demonstrates how to preprocess images and extract text using the Tesseract OCR engine.
Features:
Image preprocessing steps include:
Grayscale conversion
Thresholding
Noise removal
Text extraction using pytesseract
Modular design for easy customization
Requirements:
Python 3.x
OpenCV (cv2)
Tesseract OCR (pytesseract)
PIL (Pillow)
Setup:
Install the required Python packages:
Bash

pip install opencv-python pytesseract Pillow
Install Tesseract OCR and configure the tesseract_cmd path in the script.
Usage:
Place the image file in the same directory as the script.
Run the script:
Bash

python ocr_script.py path\_to\_your\_image.png
Code Highlights:
The core OCR functionality is implemented in the process_and_ocr function.
Preprocessing functions such as grayscale, thresholding, and remove_noise enhance OCR accuracy.
