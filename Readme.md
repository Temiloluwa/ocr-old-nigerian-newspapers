# OCR on OLD Nigerian Newspapers

## Done Tasks

1. The `src/get_document_layout.py` uses Amazon Textextract to get the document layout and stores the information as json files.

2. The module `src/perform_ocr_aws_text_extract.py` performs ocr using AWS Textextract.
    - Stores OCR information at `ocr/aws_extract/december_1994`
    - Each Image's OCR information is captured in a folder named just like it.
    - The bounding boxes discovered when extracting the layout are cropped out of the image
    - Then OCR is performed on the cropped images

## To-Do Tasks

1. Implement a performant OCR function
    - Please modify `perform_ocr` function in module `src/aws-text-extract/exp_perform_ocr.ipynb` to improve the OCR performance. 
    It currently uses pytesseract which produces a low quality output