# Automatic Number Plate Recognition (APNR)

<p align="center">
  <img src="https://github.com/APNR-C242-AP01/.github/blob/main/img/188851772.png" alt="APNR Logo" />
</p>

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Team Members](#team-members)
- [Contributing](#contributing)

## Introduction

The **Automatic Number Plate Recognition (APNR)** system is an advanced solution for intelligent vehicle license plate detection and recognition. By leveraging cutting-edge technologies like **YOLO** and **PaddleOCR**, our project offers a robust, scalable approach to automatic license plate identification.

## Features

- Accurate Detection: Data analysis with high accuracy levels thanks to the latest AI technology.
- Easy Upload: Supports various photo and video formats for your flexibility.
- Free Daily Limit: Access up to 10 uploads per day for free.
- Data Security: You can manage your data securely and comfortably. to various image resolutions and environments

## Requirements

- **Language**: Python 3.8+
- **Object Detection**: YOLO v11n
- **OCR Engine**: PaddleOCR
- **Additional Libraries**: 
  - OpenCV
  - PyTorch
  - NumPy

## Prerequisites

Ensure you have the following installed:
- Python 3.8 or higher
- pip package manager
- Git

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/APNR-C242-AP01/cloud-computing.git
cd cloud-computing
```

### 2. Create Virtual Environment (Recommended)
```bash
python -m venv apnr_env
source apnr_env/bin/activate  # On Windows, use `apnr_env\Scripts\activate`
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
cd src/app/python
pip install -r requirements.txt
```

## Usage

### Detection Module
```bash
cd src/app/python
python app.py
```

### Web Interface
```bash
npm run dev
```

### Cloud Storage CORS Configuration
```bash
gsutil cors set cors-config.json gs://<your-bucket-name>
```

## Team Members

### Cloud Computing Track
- **Eric Vincent Kho** (C239B4KY1270)
- **Hanif Al Falih** (C002B4KY1705)

### Machine Learning Track
- **Muhammad Syafiq Ibrahim** (M312B4KY3095)
- **Alvin Giovanni** (M002B4KY0429)
- **Sofia Maulida** (M279B4KY4190)
- **Anjas Rani** (M144B4KY0567)

## Contributing

We welcome contributions! Here's how you can help:

1. Fork the repository
2. Create a feature branch
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes
   ```bash
   git commit -m 'Add some amazing feature'
   ```
4. Push to the branch
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a Pull Request

## Acknowledgments

- [YOLO](https://github.com/ultralytics/) for state-of-the-art object detection
- [PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR) for powerful text recognition
- [SORT](https://github.com/abewley/sort) for multi-object tracking and data association
- Bangkit Program for continuous support and guidance


<!-- ## 📄 License

*Licensing details to be added*

--- -->

**Developed with ❤️ by the APNR Project Team**
