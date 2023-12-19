# OCR on OLD Nigerian Newspapers

## Done Tasks

1. The `src/get_document_layout.py` uses Amazon Textextract to get the document layout and stores the information as json files.

2. The module `src/perform_ocr_aws_text_extract.py` performs ocr using AWS Textextract.
    - The file store the the OCR in a json file and crops of each crop as a jpeg file

## To-Do Tasks

1. Implement a performant OCR function
    - Please modify `perform_ocr` function in module `src/aws-text-extract/exp_perform_ocr.ipynb` to improve the OCR performance. 
    It currently uses pytesseract which produces a low quality output