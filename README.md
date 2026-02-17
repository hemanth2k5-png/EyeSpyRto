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

