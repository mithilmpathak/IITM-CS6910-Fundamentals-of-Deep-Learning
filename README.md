# CS6910: Fundamentals of Deep Learning (IIT Madras)

This repository contains the coursework, code implementations, Jupyter Notebooks, output visualizations, and project reports for **CS6910: Fundamentals of Deep Learning**, taken at **IIT Madras** (M.Tech / Year 1 / Semester 2).

---

## 📌 Repository Structure

```
.
├── 1/                        # Assignment 1: Feedforward Neural Networks & Autoencoders
│   ├── ASSIGNMENT_1_TASK_1.ipynb
│   ├── ASSIGNMENT_1_TASK_2.ipynb
│   ├── ASSIGNMENT_1_TASK_3.ipynb
│   ├── CS6910_Assignment1_2026.pdf
│   ├── Team10_A1.pdf         # Final Report
│   └── outputs/              # Loss plots & classification results
├── 2/                        # Assignment 2: Convolutional Neural Networks & NLP Baselines
│   ├── Task_1.ipynb          # CNN Architecture Exploration
│   ├── Task_2.ipynb          # Fine-Tuning & Transfer Learning (VGG, GoogleNet)
│   ├── Task_3.ipynb          # POS Tagging
│   ├── Task_4.ipynb          # Sentiment Analysis
│   ├── OUTPUT_IMAGES/
│   ├── CS6910_Assignment2.pdf
│   └── Team10_A2.pdf         # Final Report
└── 3/                        # Assignment 3: Recurrent Networks & Sequence-to-Sequence Models
    ├── Assignment_3_Task_1_2.ipynb  # RNN / LSTM / GRU implementations
    ├── Assignment_3_Task_3.ipynb    # Sequence-to-Sequence Machine Translation
    ├── Assignment_3_Task_4.ipynb    # Attention Mechanisms
    ├── Assignment_3_Task_5.ipynb    # Image Captioning / Transformer architectures
    ├── Team10_A3.pdf         # Final Report
    └── CS6910_Assignment3_30th April 2026.pdf
```

---

## 📚 Overview of Assignments

### 🔹 Assignment 1: Feedforward Neural Networks & Optimization
- **Task 1 & 2**: Building custom Feedforward Neural Networks (FNN) from scratch, implementing forward/backward propagation, and experimenting with optimization algorithms (SGD, Momentum, Nesterov, RMSprop, Adam, Nadam).
- **Task 3**: Autoencoders, Deep Feature Extraction, and Pre-training vs. No Pre-training performance comparison.

### 🔹 Assignment 2: Convolutional Neural Networks & Sequence Modeling
- **Task 1 & 2 (Computer Vision)**: Design & training of custom CNN architectures, transfer learning, fine-tuning pretrained models (**VGGNet**, **GoogLeNet**), feature visualization, and error analysis.
- **Task 3 & 4 (NLP Baselines)**: Part-of-Speech (POS) Tagging and Sentiment Analysis tasks.

### 🔹 Assignment 3: Recurrent Architectures & Seq2Seq Models
- **Task 1 & 2**: Implementing Vanilla RNNs, LSTMs, and GRUs for sequence processing.
- **Task 3**: Sequence-to-Sequence (Seq2Seq) encoder-decoder model for Machine Translation (English to Hindi).
- **Task 4**: Attention Mechanism (Bahdanau / Luong attention) integration and attention map visualization.
- **Task 5**: Transformer models and Image Captioning architectures.

---

## 🛠️ Requirements & Setup

### Prerequisites
- Python 3.9+
- PyTorch / TensorFlow / Keras
- NumPy, Pandas, Matplotlib, Seaborn
- Jupyter Notebook / JupyterLab

### Installation
```bash
git clone https://github.com/mithilmpathak/IITM-CS6910-Fundamentals-of-Deep-Learning.git
cd IITM-CS6910-Fundamentals-of-Deep-Learning
```

> **Note on Datasets**: Large raw dataset directories (`DATASETS/`, GloVe embeddings, Flickr images, etc.) are excluded from this repository via `.gitignore` to maintain lightweight storage. Download instructions or preprocessing steps can be found within the respective notebook cells.

---

## 📜 Reports
Detailed experimental setups, hyperparameter sweeps, architecture diagrams, and analysis reports are available in the respective `Team10_Ax.pdf` files in each assignment directory.
