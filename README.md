# 🧠 Neural Network and Fuzzy Logic Control (Programs)

This repository contains a **Jupyter Notebook** with Python implementations of the major topics from the **PE-EC702C: Neural Network and Fuzzy Logic Control** syllabus.  
It is designed as a **lab manual + learning guide** for students to bridge theory with practice using code, visualizations, and real-world examples.  

---

## 📂 Contents

### 1. Neural Networks and Pattern Association
- McCulloch–Pitts Neuron (Boolean functions)  
- Perceptron Model (AND/OR gates, linear separability)  
- Adaline & Madaline Networks  
- Hebbian Learning & Delta Rule  
- Associative Networks (Hetero-associative, Auto-associative, Iterative Auto-associative)  
- Bidirectional Associative Memory (BAM)  

### 2. Neural Networks Based on Competition
- Kohonen Self-Organizing Map (SOM)  
- Learning Vector Quantization (LVQ)  
- Counter-Propagation Network (CPN)  

### 3. Adaptive Resonance & Backpropagation
- Adaptive Resonance Theory (ART1, ART2)  
- Standard Backpropagation (Multi-layer Perceptron, XOR example)  
- Boltzmann Machine (energy-based learning)  

### 4. Fuzzy Logic
- Classical vs Fuzzy Sets (union, intersection, complement)  
- Membership Functions (triangular, trapezoidal, Gaussian)  
- Crisp vs Fuzzy Relations, λ-cuts  
- Fuzzification and Defuzzification (centroid, max-membership, weighted average)  

### 5. Applications
- Pattern Recognition  
- Image Compression (SOM-based color quantization)  
- Communication Systems (Neural Equalization demo)  
- Fuzzy Logic Controller (temperature → fan speed)  

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/Shinjan-saha/Neural-Network-Fuzzy-Logic-Control
   cd Neural-Network-Fuzzy-Logic-Control
   ```

2. Create a Python virtual environment (recommended):
   ```bash
   python -m venv .venv
   source .venv/bin/activate   # Linux/Mac
   .venv\Scripts\activate      # Windows
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
   Open `NN_Fuzzy_Control_Lab.ipynb` and run the cells.

---

## 📦 Requirements

- Python 3.8+  
- [NumPy](https://numpy.org/)  
- [Matplotlib](https://matplotlib.org/)  
- [Jupyter](https://jupyter.org/)  

(Install all with `pip install -r requirements.txt`)

---

## 🎯 Learning Outcomes
By working through this notebook, students will:
- Understand the fundamentals of **neural network architectures**.  
- Implement **learning rules** (Perceptron, Hebbian, Delta, Backpropagation).  
- Explore **competitive learning models** like SOM and LVQ.  
- Apply **fuzzy set theory and logic controllers**.  
- Gain insight into **applications** in pattern recognition, image compression, communication, and control systems.  

---

## 📖 License
This repository is open-sourced under the MIT License.  
