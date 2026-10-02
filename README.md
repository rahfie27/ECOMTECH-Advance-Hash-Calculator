<img src="https://www.upload.ee/image/19807845/SCREENSHOT.png" border="0" alt="SCREENSHOT.png" />

# Advance Hash Calculator

A desktop hash calculation and verification utility built with Python and PyQt5.

## Features
- Calculate and verify file hashes
- Multiple hashing algorithms
- Desktop GUI interface
- Theme and language support
- Windows icon included

## Requirements
- Python 3.10+
- PyQt5

## Installation

```bash
git clone https://github.com/yourname/Advance-Hash-Calculator.git
cd Advance-Hash-Calculator
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
```

## Run

```bash
python src/Hash_Check.py
```

## Build Windows EXE

```bash
pip install pyinstaller
pyinstaller --onefile --windowed --icon app.ico src/Hash_Check.py
```
