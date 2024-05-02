## 🛡️ Aegis: Intrusion Detection System (IDS) with Artificial Neural Networks

[![Python](https://img.shields.io/badge/Python-3.7%2B-brightgreen.svg)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.4.1-FF6F00.svg)](https://www.tensorflow.org/)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-0.24.1-F7931E.svg)](https://scikit-learn.org/)
[![Pandas](https://img.shields.io/badge/Pandas-1.2.4-150458.svg)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-1.20.2-013243.svg)](https://numpy.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.4.2-brightgreen.svg)](https://matplotlib.org/)
[![License](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1BbiyYLLjUKEKLozuRTu_ip6UzlWX9v-1?usp=sharing)

**Project Description**

Aegis is an Artificial Neural Network (ANN)-based Intrusion Detection System designed to safeguard networks by proactively identifying malicious activity and differentiating it from normal traffic. As a Free and Open Source Software (FOSS) project, Aegis embraces the principles of transparency, collaboration, and community-driven innovation.

**Key Features**

- **Enhanced Detection:** Employs a meticulously trained ANN model for superior detection accuracy of network attacks.
- **Data Preprocessing:** Thorough data cleaning and normalization to optimize model performance.
- **Dimensionality Reduction:** Leverages techniques like Principal Component Analysis (PCA) for efficient feature representation.
- **Customizable Architecture:** Flexible ANN architecture adaptable to diverse network environments.
- **Performance Visualization:** Provides graphical insights into model training and evaluation metrics.

**Architecture**

- **Data Input** (Raw network data)
- **Preprocessing**
 - Data cleaning & normalization
 - Feature encoding
- **Dimensionality Reduction** (Principal Component Analysis)
- **ANN Model**
 - Input Layer
 - Hidden Layers (Dense with ReLU activation)
 - Output Layer (Sigmoid activation for binary classification)
- **Detection Output** (Normal traffic vs. Attack)

**Getting Started**

1. **Prerequisites:**
  - Python 3.x
  - Libraries: pandas, numpy, matplotlib, scikit-learn, tensorflow

2. **Clone Repository:** `git clone https://github.com/thisisarnabdas/aegis.git`

3. **Run:** `python main.ipynb` 

4. **Run on Google Colab:** Click the "Open In Colab" badge above to run Aegis directly in your browser using Google Colab.

**Dataset**

- Utilize the KDD Cup 1999 dataset (or specify your source)

**Technologies**

- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow
- Keras
- Matplotlib

**Future Development**

- **Real-time Detection:** Explore streaming data integration.
- **Hyperparameter Tuning:** Automated hyperparameter optimization.
- **Ensemble Techniques:** Experiment with combining multiple models.

**Contributing**

We welcome contributions to improve and expand Aegis! Feel free to submit issues, feature requests, and pull requests. As a FOSS project, we believe in the power of collaboration and invite developers, researchers, and security enthusiasts to join our mission of building robust network defenses.

**Contact**

ARNAB DAS - arnab.das@g.bracu.ac.bd

AVIZIT SARKAR - avizit.sarkar@g.bracu.ac.bd

**✨ Embrace the Freedom of Open Source and Secure Your Digital Realm! ✨**
