<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>FLOTEX Project - README</title>
  <style>
    body {
      font-family: 'Segoe UI', Arial, sans-serif;
      max-width: 900px;
      margin: 40px auto;
      padding: 0 20px;
      line-height: 1.6;
      color: #333;
    }
    h1, h2, h3 {
      color: #003366;
    }
    h1 {
      font-size: 2em;
    }
    h2 {
      margin-top: 40px;
      border-bottom: 2px solid #ccc;
      padding-bottom: 5px;
    }
    code {
      background-color: #f4f4f4;
      padding: 2px 5px;
      border-radius: 4px;
    }
    pre {
      background: #f4f4f4;
      padding: 10px;
      border-radius: 6px;
      overflow-x: auto;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 15px;
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
    .qr {
      margin: 30px 0;
    }
    img {
      border: 1px solid #ccc;
      border-radius: 6px;
    }
    .author {
      font-weight: bold;
      font-size: 1.1em;
    }
    .folder-tree {
      font-family: monospace;
      background: #f9f9f9;
      padding: 10px;
      border-left: 4px solid #003366;
      border-radius: 6px;
      white-space: pre;
    }
  </style>
</head>
<body>

  <h1>🌊 FLOTEX: Floating Waste Detection & Recognition System using AI</h1>

  <p class="author">
    Author: Stuti Chaurasia<br/>
    Institution: Banasthali Vidyapith<br/>
    Session: 2024–25<br/>
    Supervisor: Dr. Neelam Sharma<br/>
    Email: <a href="mailto:neelamsharma@banasthali.in">neelamsharma@banasthali.in</a>
  </p>

  <h2>🧠 Abstract</h2>
  <p>
    <strong>FLOTEX</strong> is an AI-powered real-time system that detects and classifies floating waste in India’s rivers. Built using modern computer vision models like YOLOv8 and DETR, the project can identify biodegradable and non-biodegradable materials to assist with smart, sustainable waste cleanup through unmanned surface vehicles (USVs).
  </p>

  <h2>📌 Motivation</h2>
  <p>
    India contributes nearly <strong>11% of global plastic river waste</strong>. This results in massive environmental and public health issues, including over <strong>1.44 lakh deaths annually</strong> due to water pollution. FLOTEX is built to provide an intelligent, affordable, and scalable solution for this critical problem.
  </p>

  <h2>💻 Tech Stack</h2>
  <ul>
    <li><strong>Computer Vision:</strong> YOLOv8, DETR (Roboflow)</li>
    <li><strong>Frameworks:</strong> PyTorch, OpenCV</li>
    <li><strong>Dataset:</strong> Over 13,600 real-world floating waste images</li>
    <li><strong>Deployment:</strong> Flask App + Colab + Roboflow</li>
    <li><strong>Tools:</strong> LabelImg, Roboflow, COCO format, GitHub</li>
  </ul>

  <h2>📁 Project Structure</h2>
  <div class="folder-tree">
FLOTEX/  
├── notebooks/         # Training & testing notebooks  
├── src/               # Model, preprocessing, and utility scripts  
├── dataset/           # Images and annotations  
├── weights/           # YOLOv8 and DETR trained weights  
├── static/            # Visualizations, sample output  
├── app/               # Flask web app for demo  
├── qr_code.png        # QR code for web/demo  
└── README.md          # Project documentation
  </div>

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
    <li><strong>Clone the Repository:</strong>
      <pre><code>git clone https://github.com/yourusername/flotex-ai.git</code></pre>
    </li>
    <li><strong>Install Dependencies:</strong>
      <pre><code>pip install -r requirements.txt</code></pre>
    </li>
    <li><strong>Run Inference:</strong>
      <pre><code>python detect.py --weights weights/yolov8.pt --source test_images/</code></pre>
    </li>
    <li><strong>Launch Web App:</strong>
      <pre><code>python app/app.py</code></pre>
    </li>
  </ol>

  <h2>📲 Scan for Live Demo / Docs</h2>
  <div class="qr">
    <img src="qr_code.png" alt="QR Code to Web App or Docs" width="200"/>
  </div>

  <h2>🔮 Future Scope</h2>
  <ul>
    <li>Deploy on USVs for real-time floating waste tracking</li>
    <li>Integrate with Namami Gange & Smart River Missions</li>
    <li>Automated waste collection & categorization</li>
    <li>Edge inference using Raspberry Pi or Jetson Nano</li>
  </ul>

  <h2>📘 Research Paper</h2>
  <p>
    <strong>Title:</strong> FLOTEX: Floating Waste Detection and Recognition for Sustainable Waterway Management<br/>
    <strong>Publication:</strong> [To be updated]
  </p>

  <h2>🤝 Acknowledgement</h2>
  <p>
    Gratitude to <strong>Dr. Neelam Sharma</strong> and the Department of Computer Science, Banasthali Vidyapith for their constant support and encouragement. Special thanks to peers and mentors who contributed insights and feedback.
  </p>

  <h2>📜 License</h2>
  <p>
    This project is licensed under the <strong>MIT License</strong>. See the LICENSE file for details.
  </p>

</body>
</html>
