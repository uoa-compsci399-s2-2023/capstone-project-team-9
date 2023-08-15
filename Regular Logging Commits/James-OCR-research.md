Researched alternatives to tesseract.

Looked further into [PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR/blob/release/2.7/README_en.md), based on various youtube demos it does a decent job for handwriting detection and recognition. The accuracy can vary although clear handwriting is crucial
- A lot of documentation is provided by PaddleOCR
- They provide a [tutorial](https://github.com/PaddlePaddle/PaddleOCR/blob/release/2.7/deploy/lite/readme.md) on mobile deployment


PaddleOCR can also be used as a service with FastAPI provided by [Sparrow](https://github.com/katanaml/sparrow), although this might only be specific to documents

Concerns for garbled OCR data could be solved by using ChatGPT to decipher text. 
- Although the example from youtube used text extracted from a document and used ChatGPT4
-- The output data was in arrays
