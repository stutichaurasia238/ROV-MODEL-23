<h1>🌊 FLOTEX: Floating Waste Detection & Recognition System using AI</h1>

**Author:** Stuti Chaurasia  
**Institution:** Banasthali Vidyapith  
**Session:** 2024–25  
**Supervisor:** Dr. Neelam Sharma  
**Email:** [neelamsharma@banasthali.in](mailto:neelamsharma@banasthali.in)

---

## 🧠 Abstract

**FLOTEX** is an AI-powered real-time system that detects and classifies floating waste in India’s rivers. Built using modern computer vision models like YOLOv8 and DETR, the project can identify biodegradable and non-biodegradable materials to assist with smart, sustainable waste cleanup through unmanned surface vehicles (USVs).

## 📌 Motivation

India contributes nearly **11% of global plastic river waste**. This results in massive environmental and public health issues, including over **1.44 lakh deaths annually** due to water pollution. FLOTEX is built to provide an intelligent, affordable, and scalable solution for this critical problem.

## 💻 Tech Stack

- **Computer Vision:** YOLOv8, DETR (Roboflow)  
- **Frameworks:** PyTorch, OpenCV  
- **Dataset:** Over 13,600 real-world floating waste images  
- **Deployment:** Flask App + Colab + Roboflow  
- **Tools:** LabelImg, Roboflow, COCO format, GitHub

## 📁 Project Structure

FLOTEX/
├── notebooks/ # Training & testing notebooks
├── src/ # Model, preprocessing, and utility scripts
├── dataset/ # Images and annotations
├── weights/ # YOLOv8 and DETR trained weights
├── static/ # Visualizations, sample output
├── app/ # Flask web app for demo
├── qr_code.png # QR code for web/demo
└── README.md # Project documentation


## 🧪 Model Performance

| Model    | mAP@0.5 | Precision | Recall |
|----------|---------|-----------|--------|
| YOLOv8   | 86.4%   | 88.9%     | 83.2%  |
| RF-DETR  | 84.7%   | 85.3%     | 81.6%  |

## 🚀 How to Run

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/flotex-ai.git
2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
3. **Run Inference:**
   ```bash
   python detect.py --weights weights/yolov8.pt --source test_images/
4. **Launch Web App:**
   ```bash
python app/app.py

📲 Scan for Live Demo / Docs
Use the QR code below to access the live deployment or detailed documentation:

<img src="qr_code.png" alt="QR Code" width="200">
🔮 Future Scope
Deploy on USVs for real-time floating waste tracking

Integrate with Namami Gange & Smart River Missions

Automated waste collection & categorization

Edge inference using Raspberry Pi or Jetson Nano

---

✅ **Now you can directly copy and paste** this into your `README.md` file and it will render perfectly on GitHub or any Markdown viewer.

Do you want me to generate a live preview file for this or help you link the Colab + QR demo as well?

