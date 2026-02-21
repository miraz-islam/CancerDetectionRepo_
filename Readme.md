<h1 align="center">🧠 Brain Tumor Detection using CNN</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.9-blue.svg">
  <img src="https://img.shields.io/badge/TensorFlow-2.x-orange.svg">
  <img src="https://img.shields.io/badge/Keras-DeepLearning-red.svg">
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen.svg">
</p>

<p align="center">
Deep Learning based Brain Tumor Detection system using MRI images and Convolutional Neural Networks (CNN).
</p>

---

<h2>📌 Overview</h2>

<p>
This project uses a Convolutional Neural Network (CNN) to classify brain MRI images and detect whether a tumor is present or not.
It is designed as a medical image classification system using deep learning.
</p>

---

<h2>🧠 Model Features</h2>

<ul>
  <li>✔ CNN based deep learning architecture</li>
  <li>✔ MRI image classification</li>
  <li>✔ Binary classification (Tumor / No Tumor)</li>
  <li>✔ Image preprocessing and normalization</li>
  <li>✔ Custom image prediction support</li>
</ul>

---

<h2>🏗 Model Architecture</h2>

<pre>
Input Layer (224x224x3)
↓
Conv2D (ReLU)
↓
Conv2D (ReLU)
↓
MaxPooling
↓
Conv2D (ReLU)
↓
Flatten
↓
Dense Layer
↓
Output Layer (Sigmoid)
</pre>

---

<h2>📂 Project Structure</h2>

<pre>
CancerDetection/
│
├── cancerdetection.ipynb
├── README.md
├── dataset/
│   ├── yes/
│   └── no/
│
└── model/
</pre>

---

<h2>🗂 Dataset</h2>

<ul>
  <li><b>yes/</b> → Tumor MRI images</li>
  <li><b>no/</b> → Normal MRI images</li>
</ul>

<p>
All images are resized to <b>224 × 224</b>
</p>

---

<h2>⚙️ Technologies Used</h2>

<ul>
  <li>Python</li>
  <li>TensorFlow</li>
  <li>Keras</li>
  <li>NumPy</li>
  <li>Matplotlib</li>
  <li>Jupyter Notebook</li>
</ul>

---

<h2>🚀 Installation</h2>

<pre>
git clone https://github.com/your-username/CancerDetection.git

cd CancerDetection

pip install tensorflow numpy matplotlib
</pre>

---

<h2>▶️ Usage</h2>

<pre>
jupyter notebook
</pre>

<p>Run:</p>

<pre>
cancerdetection.ipynb
</pre>

---

<h2>📊 Output</h2>

<ul>
  <li>0 → No Tumor</li>
  <li>1 → Tumor Detected</li>
</ul>

---

<h2>📈 Future Improvements</h2>

<ul>
  <li>Add Web App (Streamlit / Flask)</li>
  <li>Improve accuracy with larger dataset</li>
  <li>Add Grad-CAM visualization</li>
  <li>Deploy to cloud</li>
</ul>

---

<h2>👨‍💻 Author</h2>

<p>
<b>Nahidul Islam Miraz</b><br>
Machine Learning Enthusiast<br>
</p>

<p align="center">
⭐ Star this repo if you found it useful!
</p>

---