## Dependencies
- tesseract
- pytesseract
- opencv-python

## Installation procedure 
First of all install Tesseract from [here](https://github.com/UB-Mannheim/tesseract/wiki)

### Defining paths to tesseract.exe
Download and install tesseract and place the path of the installed tessaract .exe file in environment variables of the system.

If you don't want to add the path to environment variable then simply give the path of the .exe file in main.py. By default path would be  `C:\Program Files\Tesseract-OCR\tesseract.exe`


### Installing Libraries

```
pip install opencv-python
pip install pytesseract
pip install tesseract
```

## Code running
After installing the dependencies place your pictures in pictures folder and simply run 

```
python main.py
```