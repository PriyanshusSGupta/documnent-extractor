# AI-Powered Logistics Document Extractor

## Project Overview

This project is a Python-based system designed to automatically extract key information from unstructured documents. It leverages the Donut transformer model from Hugging Face to perform Optical Character Recognition (OCR) and information extraction in a single step, converting messy, image-based documents into structured JSON data.

This project was built to target key requirements for understanding tasks done by AI Engineer, focusing on document understanding and handling real-world, messy data.

## Key Features

*   **Input:** Processes image-based documents (PNG, JPG).
*   **Core Technology:** Utilizes the `naver-clova-ix/donut-base-finetuned-cord-v2` model.
*   **Output:** Generates structured JSON data containing the extracted fields.
*   **Adaptability:** Uses prompt engineering to guide the model for different document layouts.

## How to Run the Code

1.  Clone the repository.
2.  Install dependencies: `pip install transformers torch pillow "sentencepiece<0.2.0>"`
3.  Place your document image in the root folder.
4.  Run the script: `python extractor_v3.py`

**This is still under progress so don't try to rely completely on this program**
