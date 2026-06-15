# ImageRedaction
This is a Streamlit-based web application that automatically redacts sensitive information (like faces, phone numbers, PAN card numbers, names, etc.) from uploaded images using OpenCV, Tesseract OCR, and Regex.

🚀 Features
✅ Automatic face detection and redaction using Haar Cascades
✅ OCR-based detection and redaction of:
Phone numbers (10 digits)
PAN card numbers
Dates in dd/mm/yyyy format
Full names (basic format)
Credit card numbers
Ages
Father's names
✅ Adjustable face redaction level via slider
✅ Preview of original and redacted image
✅ Downloadable redacted image
🧰 Tech Stack
Python
Streamlit – Web UI
OpenCV – Image processing & face detection
pytesseract – OCR (Optical Character Recognition)
Regex – Pattern matching for sensitive info
📂 Project Structure
