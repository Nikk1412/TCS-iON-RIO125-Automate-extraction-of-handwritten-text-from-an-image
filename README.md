# TCS iON RIO125 – Automate Extraction of Handwritten Text from an Image

## 📌 Project Overview
This project is developed as part of **TCS iON RIO125** and focuses on **automating the extraction of handwritten text from images** using **Optical Character Recognition (OCR)** techniques. The primary goal is to convert handwritten text into machine-readable format, making it easier to process and analyze for various applications such as **document digitization, form processing, and data extraction**.

The system leverages **Tesseract OCR** combined with **image preprocessing techniques** to improve recognition accuracy.

---

## 🚀 Features
✅ **Handwritten Text Recognition** – Extracts handwritten text from images  
✅ **OCR Integration** – Uses **Tesseract OCR** for text recognition  
✅ **Image Preprocessing** – Improves recognition accuracy using OpenCV  
✅ **Multi-Language Support** – Can recognize different handwriting styles  
✅ **Structured Output** – Saves extracted text in a user-friendly format  
✅ **User Interface** – Web-based UI using **Streamlit** for easy access  

---

## 🛠️ Tech Stack
- **Programming Language:** Python  
- **Libraries & Tools:**  
  - [OpenCV](https://opencv.org/) – Image processing  
  - [Tesseract OCR](https://github.com/tesseract-ocr/tesseract) – Optical Character Recognition  
  - [NumPy](https://numpy.org/) – Mathematical operations  
  - [PIL (Pillow)](https://pillow.readthedocs.io/en/stable/) – Image handling  
  - [Streamlit](https://streamlit.io/) – Web-based UI  

---

## 📂 Project Structure
```
📦 Automate-identification-and-recognition-of-handwritten-text-from-image
┣ 📂 App/ # Application files
┣ 📂 HTR_Models/ # Handwritten Text Recognition models
┣ 📂 HTR_Using_CRNN/ # CRNN implementation files
┣ 📂 Images/ # Input images for processing
┣ 📂 TestImages/ # Test images for evaluation
┣ 📜 HTR_USING_CRNN.ipynb # Jupyter notebook with CRNN implementation
┣ 📜 Project Report.pdf # Documentation of the project
┣ 📜 TCS_iON_RIO125_-_Automate_extraction.ipynb # Main implementation notebook
┣ 📜 README.md # Project documentation
```

---

## 🔧 Installation & Setup

### 🔹 Prerequisites
Ensure you have **Python 3.8+** installed on your system.

### 🔹 Step 1: Clone the Repository
```bash
git clone https://github.com/Nikk1412/TCS-iON-RIO125-Automate-extraction-of-handwritten-text-from-an-image.git
cd tcs-ion-handwritten-text-extraction
```

### 🔹 Step 2: Install Dependencies
Run the following command to install the required libraries:

```bash
pip install -r requirements.txt
```

### 🔹 Step 3: Install Tesseract OCR
Windows: Download and install Tesseract OCR from [here](https://github.com/UB-Mannheim/tesseract/wiki).

Linux: Install using:

```bash
sudo apt install tesseract-ocr
```

### 🔹 Step 4: Run the Application
Command-line Mode (Basic OCR Extraction)

```bash
python main.py
```

Web Interface (Streamlit App)

```bash
streamlit run app.py
```

Open the browser and access http://localhost:8501/ to use the web app.

---

## 📸 Usage
1. Upload an image containing handwritten text.
2. The system processes the image using OpenCV for better recognition.
3. Tesseract OCR extracts the text from the preprocessed image.
4. The extracted text is displayed on-screen and saved for later use.

---

## 🔍 Applications
🔹 **Digitization of handwritten documents** – Convert physical notes into digital text.  
🔹 **Automated Form Processing** – Extract data from scanned forms.  
🔹 **Educational Tools** – Help students and researchers analyze handwritten content.  

---

## 📈 Future Enhancements
🔸 **Deep Learning-based OCR** – Improve accuracy using CNN-based models.  
🔸 **Real-time Handwriting Recognition** – Implement handwriting-to-text conversion in real-time.  
🔸 **Support for Multiple Languages** – Enhance OCR to support handwritten regional languages.  
🔸 **Mobile App Integration** – Extend functionality to Android/iOS using Flutter or React Native.  

---

## 💡 Contributing
Contributions are welcome! Follow these steps:

1. Fork the repository
2. Create a new feature branch: `git checkout -b feature-name`
3. Commit your changes: `git commit -m "Add new feature"`
4. Push to the branch: `git push origin feature-name`
5. Create a Pull Request

---

## 📄 License
This project is licensed under the MIT License – feel free to use, modify, and distribute.

---

## 🙌 Acknowledgements
Special thanks to TCS iON for providing this opportunity to work on industry-relevant projects.
