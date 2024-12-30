# fallout_card-reader
Fallout Board Game Card Reader (Unofficial)

## Disclaimer
This project is a fan-created tool intended for personal use with the Fallout board game, created by Bethesda Softworks and Fantasy Flight Games. It is not affiliated with, endorsed by, or sponsored by these companies. No copyrighted materials from the Fallout board game are included in this repository, aside from sample images for demonstration purposes under fair use.

## Project map
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

```
## Main Program Workflow
1. Capture card image.
2. Preprocess image for OCR.
3. Extract text using OCR.
4. Detect the language of the extracted text.
5. Translate text to English if necessary.
6. Convert text to speech.

### Decisions
1. Keep it pythonic
2. Since final product will be deployed to Jetson Nano use cloud-based solution when possible
3. Test device switching in openCV with USB. Set camera_index = 1 for connected usb device
4. Concentrate on capturing clear images rather than preprocessing before OCR
5. Switched camera type from webcam to document cam
