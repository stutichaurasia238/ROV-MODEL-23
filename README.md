<h1>🌊 FLOTEX: Floating Waste Detection & Recognition System using AI</h1>

**Author:** Stuti Chaurasia  
**Institution:** Banasthali Vidyapith  
**Session:** 2024–25  
**Supervisor:** Dr. Neelam Sharma  


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

<pre>
FLOTEX/
├── <strong>notebooks/</strong>       # Training & testing notebooks
├── <strong>src/</strong>             # Model, preprocessing, and utility scripts
├── <strong>dataset/</strong>         # Images and annotations
├── <strong>weights/</strong>         # YOLOv8 and DETR trained weights
├── <strong>static/</strong>          # Visualizations, sample output
├── <strong>app/</strong>             # Flask web app for demo
├── <strong>qr_code.png</strong>      # QR code for web/demo
└── <strong>README.md</strong>        # Project documentation
</pre>


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

<h2>📲 Scan for Live Demo / Docs</h2>
<p>Use the QR code below to access the project demo or full deployment guide:</p>
<img src="qr_code.png" alt="QR Code" class="qr">

<h2>🔮 Future Scope</h2>
<ul>
  <li>Deploy on USVs for real-time floating waste tracking</li>
  <li>Integrate with Namami Gange & Smart River Missions</li>
  <li>Automated waste collection & categorization</li>
  <li>Edge inference using Raspberry Pi or Jetson Nano</li>
</ul>

<h2>📘 Research Paper</h2>
<p><strong>Title:</strong> <em>FLOTEX: Floating Waste Detection and Recognition for Sustainable Waterway Management</em><br>
<strong>Publication:</strong> [To be updated]</p>

<h2>🤝 Acknowledgement</h2>
<p>Gratitude to <strong>Dr. Neelam Sharma</strong> and the Department of Computer Science, Banasthali Vidyapith for their constant support and encouragement. Special thanks to peers and mentors who contributed insights and feedback.</p>

<h2>📜 License</h2>
<p>This project is licensed under the <strong>MIT License</strong>. See the LICENSE file for details.</p>

</body>
</html>
