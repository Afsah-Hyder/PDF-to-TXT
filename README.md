# PDF-to-TXT
OCR
https://www.geeksforgeeks.org/python-reading-contents-of-pdf-using-ocr-optical-character-recognition/

py -m pip install PIL was failing with error:
ERROR: Could not find a version that satisfies the requirement PIL (from versions: none)
ERROR: No matching distribution found for PIL

solution to use pillow instead
py -m pip install Pillow
from PIL import Image
https://stackoverflow.com/questions/32772596/pip-install-pil-fails

py -m pip install pytesseract
py -m pip install pdf2image
py -m pip install tesseract-ocr

We may need to do some additional downloading and setup...
Windows needs a PyTesseract Download
https://github.com/UB-Mannheim/tesseract/wiki/Downloading-Tesseract-OCR-Engine

C:\Program Files\Tesseract-OCR

Downloaded poppler from path https://github.com/oschwartz10612/poppler-windows/releases/tag/v23.07.0-0
