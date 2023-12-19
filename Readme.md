# OCR on OLD Nigerian Newspapers

## Done Tasks

1. The `src/get_document_layout.py` uses Amazon Textextract to get the document layout and stores the information as json files.

## To-Do Tasks

1. Implement a performant OCR function
    - Please modify `perform_ocr` function in module `src/aws-text-extract/exp_perform_ocr.ipynb` to improve the OCR performance. 
    It currently uses pytesseract which produces a low quality output