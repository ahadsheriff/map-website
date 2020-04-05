<!-- omit in toc -->
# Map Website

- [Requirements](#requirements)
- [Setup](#setup)
  - [Windows](#windows)
  - [Linux](#linux)
- [Running the Script](#running-the-script)

## Requirements

- **Dependencies** (included in requirements.txt - see below)
  - bs4
  - requests
  - lxml
  
- **Python Versions Tested**
  - 3.8.2

## Setup

### Windows

```cmd
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
```

### Linux

```cmd
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## Running the Script

```cmd
python map_website.py -d https://webscrapethissite.org -o test.txt
```