<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>FLOTEX Project - README</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      margin: 20px;
      max-width: 900px;
    }
    h1, h2, h3 {
      color: #003366;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 10px;
    }
    th, td {
      border: 1px solid #aaa;
      padding: 8px;
      text-align: center;
    }
    th {
      background-color: #003366;
      color: white;
    }
    code {
      background-color: #f4f4f4;
      padding: 2px 5px;
      border-radius: 4px;
    }
    .qr {
      max-width: 200px;
      margin: 20px 0;
    }
  </style>
</head>
<body>

<h1>🌊 FLOTEX: Floating Waste Detection & Recognition System using AI</h1>

<p><strong>Author:</strong> Stuti Chaurasia<br>
<strong>Institution:</strong> Banasthali Vidyapith<br>
<strong>Session:</strong> 2024–25<br>
<strong>Supervisor:</strong> Dr. Neelam Sharma<br>
<strong>Email:</strong> <a href="mailto:neelamsharma@banasthali.in">neelamsharma@banasthali.in</a></p>

<hr>

<h2>🧠 Abstract</h2>
<p><strong>FLOTEX</strong> is an AI-powered real-time system that detects and classifies floating waste in India’s rivers. Built using modern computer vision models like YOLOv8 and DETR, the project can identify biodegradable and non-biodegradable materials to assist with smart, sustainable waste cleanup through unmanned surface vehicles (USVs).</p>

<h2>📌 Motivation</h2>
<p>India contributes nearly <strong>11% of global plastic river waste</strong>. This results in massive environmental and public health issues, including over <strong>1.44 lakh deaths annually</strong> due to water pollution. FLOTEX is built to provide an intelligent, affordable, and scalable solution for this critical problem.</p>

<h2>💻 Tech Stack</h2>
<ul>
  <li><strong>Computer Vision:</strong> YOLOv8, DETR (Roboflow)</li>
  <li><strong>Frameworks:</strong> PyTorch, OpenCV</li>
  <li><strong>Dataset:</strong> Over 13,600 real-world floating waste images</li>
  <li><strong>Deployment:</strong> Flask App + Colab + Roboflow</li>
  <li><strong>Tools:</strong> LabelImg, Roboflow, COCO format, GitHub</li>
</ul>

<h2>📁 Project Structure</h2>
<pre>
FLOTEX/
├── notebooks/           # Training & testing notebooks
├── src/                 # Model, preprocessing, and utility scripts
├── dataset/             # Images and annotations
├── weights/             # YOLOv8 and DETR trained weights
├── static/              # Visualizations, sample output
├── app/                 # Flask web app for demo
├── qr_code.png          # QR code for web/demo
└── README.html          # This documentation
</pre>

<h2>🧪 Model Performance</h2>
<table>
  <tr>
    <th>Model</th>
    <th>mAP@0.5</th>
    <th>Precision</th>
    <th>Recall</th>
  </tr>
  <tr>
    <td>YOLOv8</td>
    <td>86.4%</td>
    <td>88.9%</td>
    <td>83.2%</td>
  </tr>
  <tr>
    <td>RF-DETR</td>
    <td>84.7%</td>
    <td>85.3%</td>
    <td>81.6%</td>
  </tr>
</table>

<h2>🚀 How to Run</h2>
<ol>
  <li><strong>Clone the Repository:</strong><br>
    <code>git clone https://github.com/yourusername/flotex-ai.git</code>
  </li>
  <li><strong>Install Dependencies:</strong><br>
    <code>pip install -r requirements.txt</code>
  </li>
  <li><strong>Run Inference:</strong><br>
    <code>python detect.py --weights weights/yolov8.pt --source test_images/</code>
  </li>
  <li><strong>Launch Web App:</strong><br>
    <code>python app/app.py</code>
  </li>
</ol>

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
