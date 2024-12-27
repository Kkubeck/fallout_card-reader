# fallout_card-reader
Fallout Board Game Card Reader (Unofficial)

## Disclaimer
This project is a fan-created tool intended for personal use with the Fallout board game, created by Bethesda Softworks and Fantasy Flight Games. It is not affiliated with, endorsed by, or sponsored by these companies. No copyrighted materials from the Fallout board game are included in this repository, aside from sample images for demonstration purposes under fair use.

## Drive
```
fallout_card-reader/
├── .gitignore
├── README.md
├── LICENSE
├── fallout_card-reader.py
├── images
│   ├── IMG_2386.jpg
│   ├── IMG_2387.jpg
│   ├── 2024-12-27 09-36.pdf

## Main Program Workflow

1. Capture card image.
2. Preprocess image for OCR.
3. Extract text using OCR.
4. Detect the language of the extracted text.
5. Translate text to English if necessary.
6. Convert text to speech.