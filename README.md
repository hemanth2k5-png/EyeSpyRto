# EyeSpyRTO 🚗👁️  
### AI-Based Automatic Number Plate Recognition & Vehicle Compliance Monitoring System

---

## 📌 Introduction

EyeSpyRTO is an Artificial Intelligence-driven Automatic Number Plate Recognition (ANPR) system designed to automate vehicle identification and document compliance verification. The project leverages state-of-the-art computer vision and deep learning technologies to detect Indian vehicle number plates from video streams, extract alphanumeric text using Optical Character Recognition (OCR), and validate legal vehicle documents through a backend database.

Traditional traffic monitoring mechanisms heavily depend on manual inspection by authorities, which introduces delays, inaccuracies, and operational inefficiencies. EyeSpyRTO aims to bridge this gap by providing a scalable, AI-powered framework that reduces human dependency while improving accuracy and automation.

This project was developed as part of an academic Capstone Project with a focus on real-world applicability, modular design, and extensibility for future smart-city integrations.

---

## 🎯 Problem Statement

Vehicle document verification and traffic compliance monitoring remain largely manual processes in many regions. Traffic officers visually inspect number plates and manually check document validity, leading to:

• Increased verification time  
• Human errors and inconsistencies  
• Difficulty handling high traffic density  
• Limited automation for CCTV footage analysis  
• Inefficient tracking and logging of violations  

Existing commercial ANPR systems are often expensive, proprietary, or poorly optimized for Indian number plate variations. Furthermore, most systems focus only on plate detection and recognition without extending into document validation or enforcement logic.

EyeSpyRTO addresses these challenges by implementing a cost-effective, AI-based solution specifically tailored for Indian vehicle plate formats and traffic conditions.

---

## 💡 Proposed Solution

EyeSpyRTO introduces a unified pipeline combining deep learning-based detection, OCR, backend processing, and reporting. The system performs:

1. Automatic detection of number plates from video frames using YOLOv8  
2. OCR-based text extraction using EasyOCR  
3. Text normalization and stabilization  
4. Validation against a structured vehicle document database  
5. CSV-based reporting of detected plates  
6. Modular backend integration via FastAPI  

The architecture is designed to be extensible, enabling future additions such as helmet detection, rule violation classification, cloud deployment, and real-time surveillance.

---

## 🧠 System Architecture


---

## ⚙️ Technology Stack

### **Programming Language**
• Python – Chosen for its rich AI/ML ecosystem and rapid prototyping capability

### **Object Detection**
• YOLOv8 (Ultralytics) – Selected for its superior performance, lightweight design, and real-time inference speed

### **OCR Engine**
• EasyOCR – Preferred over traditional OCR engines due to better robustness against noise, blur, and variable fonts

### **Backend Framework**
• FastAPI – Provides high-performance API handling, asynchronous support, and scalable backend structure

### **User Interface**
• Streamlit – Enables rapid UI development for AI applications with minimal overhead

### **Computer Vision**
• OpenCV – Used for frame extraction, preprocessing, cropping, and visualization

### **Data Processing**
• Pandas, NumPy – Used for CSV generation and structured data handling

### **Database**
• MySQL / MongoDB – Used for storing vehicle metadata and document validity records

### **Development Environment**
• Google Colab / Local Machine – Used for model training and testing

---

## ✨ Key Features

✔ AI-based number plate detection optimized for Indian vehicles  
✔ OCR extraction with stabilization and normalization  
✔ Frame-wise video processing with configurable FPS  
✔ CSV generation containing detected number plates  
✔ FastAPI backend integration for scalable processing  
✔ Streamlit UI for easy file upload and interaction  
✔ Modular pipeline for future enhancements  
✔ Lightweight and research-friendly architecture  

---

## 📂 Input & Output

### **Input Supported**
• MP4 video files  
• Image files (JPG / PNG)  
• Webcam feed (optional extension)

### **Output Generated**
• Annotated frames/videos  
• CSV reports containing:

| Frame Number | Detected Plate Text | Confidence (Optional) |
|--------------|----------------------|------------------------|

---

## 📊 Performance Highlights

The system was evaluated on multiple test videos with variations in lighting, motion blur, angles, and plate formats.

Observed performance metrics:

• Detection Accuracy: ~92–95% (under clear visibility)  
• OCR Accuracy: ~85–90% (depending on frame quality)  
• Significant speed improvement with GPU acceleration  

Performance may vary depending on hardware, video resolution, and environmental conditions.

---

## 🚀 Future Enhancements

EyeSpyRTO is designed with scalability and extensibility in mind. Planned improvements include:

• Helmet and safety violation detection  
• Multi-class traffic violation recognition  
• Real-time CCTV stream processing  
• Cloud-based deployment (AWS / GCP / Azure)  
• Integration with official RTO databases/APIs  
• Automated fine generation system  
• SMS/email notification module  
• Agentic AI-based decision engine  

---

## 📎 Project Evidence & Artifacts

Due to academic constraints, large project artifacts such as trained models, videos, outputs, and screenshots are stored externally.

👉 **Google Drive Repository:**  
_Add your Drive link here_

---

## 📜 Limitations

• OCR accuracy decreases under severe motion blur  
• Performance depends on video quality and resolution  
• Prototype does not access real government databases  
• Fine simulation is conceptual for academic purposes  

---

## 📜 Disclaimer

This project is developed strictly for academic, research, and demonstration purposes. It does not generate official fines nor interact with government systems.

---

## 👤 Author

**Hemanth Sai**  
Capstone Project – Computer Science & Engineering  
AI / Machine Learning / Computer Vision Enthusiast  

---

⭐ If you find this project interesting, consider starring the repository!
