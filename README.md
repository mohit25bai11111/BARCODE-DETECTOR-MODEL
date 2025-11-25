

# 📄 Python Barcode & QR Code Generator

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)
![License](https://img.shields.io/badge/License-Open%20Source-orange.svg)

> A lightweight, offline, and programmable Command-Line Interface (CLI) tool capable of generating industry-standard barcodes and QR codes instantly.

---

## 📖 Overview

In the domains of inventory management, retail, and digital information sharing, the need to generate barcodes and QR codes is frequent. Most existing solutions are online web converters that are often riddled with ads, require an active internet connection, or pose privacy risks when handling sensitive data.

This project bridges that gap by providing a **robust, offline tool** that generates compliant barcodes quickly without external dependencies.

## ✨ Key Features

* **Versatility:** Support for multiple standard formats including:
    * **QR Codes** (2D)
    * **EAN-13** (Retail)
    * **UPC-A** (North American Retail)
    * **Code 128** (Logistics)
    * **Code 39** (Industrial/Military)
* **Smart Validation:** Automatically validates input data (e.g., ensuring EAN-13 has the correct number of digits) to prevent the generation of unusable codes.
* **Automated Management:** Automatically handles file naming (timestamps) and directory organization (`generated/` folder).
* **Integrated Viewer:** Includes a built-in image viewer (via OpenCV) to inspect output immediately after generation.

## 🛠️ Tech Stack & Methodology

The application is built using **Python 3.x** with a modular, Object-Oriented approach. The core logic is encapsulated in a `BarcodeQRGenerator` class.

**Key Libraries:**
* `qrcode`: For generating 2D Quick Response codes.
* `python-barcode`: For generating 1D linear barcodes.
* `opencv-python`: For rendering and displaying generated images.

## ⚙️ Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/yourusername/barcode-qr-generator.git](https://github.com/yourusername/barcode-qr-generator.git)
    cd barcode-qr-generator
    ```

2.  **Install dependencies:**
    ```bash
    pip install qrcode[pil] python-barcode opencv-python
    ```

## 🚀 Usage

1.  Run the main script:
    ```bash
    python main.py
    ```
    *(Note: Replace `main.py` with your actual script name if different)*

2.  Follow the interactive CLI prompts:
    1.  **Select Format:** Choose between QR, EAN-13, UPC-A, etc.
    2.  **Input Data:** Enter text, URLs, or product numbers.
    3.  **View/Save:** The tool automatically saves the PNG to the `generated/` folder and offers to display it.

## 🔮 Future Scope

While the current version is a fully functional CLI tool, the following features are planned for **v2.0**:
* [ ] **Batch Processing:** Support for generating 100+ codes at once from CSV files.
* [ ] **GUI:** Development of a Graphical User Interface for better accessibility.
* [ ] **Database Integration:** For tracking generated codes and history.



## 🔮 Future Scope

* **Real-World Deployment:** Implementing the model on edge devices like **Raspberry Pi** for real-time assembly line verification.
* **Mobile Integration:** Developing a mobile app to allow warehouse staff to verify stock quality using smartphone cameras.
* **Format Expansion:** Extending the dataset to support **QR Codes** and **Data Matrix** codes.

---

## ⚙️ Installation & Usage

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/yourusername/barcode-verification-dl.git](https://github.com/yourusername/barcode-verification-dl.git)
    ```

2.  **Install dependencies:**
    ```bash
    pip install tensorflow opencv-python matplotlib seaborn python-barcode scikit-learn
    ```

3.  **Run the Notebook/Script:**
    Open `Barcode_Verification_CNN.ipynb` in Jupyter or Google Colab to see the training process and results.

---

## 📄 License

This project is licensed under the MIT License.├── requirements.txt          # Dependencies
└── README.md

## 👨‍💻 Author

**MOHIT PILLAI** 
**ID:** 25BAI11111  
