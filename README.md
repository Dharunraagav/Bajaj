# Lab Test OCR Extraction API

This project provides an API that extracts lab test results from medical report images using OCR (Optical Character Recognition). It uses Tesseract OCR through `pytesseract`, along with FastAPI to expose the service via a RESTful endpoint.

## Features

- Upload a PNG or JPEG image of a medical report.
- Automatically extracts:
  - Test Name
  - Test Value
  - Unit (e.g., mg/L)
  - Reference Range (if available)
- Returns the extracted data as JSON.

## Technologies Used

- Python 3.8+
- FastAPI
- pytesseract (Tesseract OCR)
- Pillow (for image processing)
- Regex (for data extraction)
- Uvicorn (ASGI server)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/lab-test-ocr-api.git
   cd lab-test-ocr-api
