# 🚀 Fine-Tuning Large Language Models for Arabic NLP

> Graduation Project focused on adapting Large Language Models (LLMs) for Arabic Natural Language Processing using modern fine-tuning techniques like LoRA & QLoRA.

---

# 📌 Overview

This project explores the evolution of NLP architectures from:

- RNN
- LSTM
- GRU
- Transformers
- Large Language Models (LLMs)

The main goal is to improve Arabic NLP performance by fine-tuning instruction-based LLMs for tasks such as:

✅ Arabic Entity Extraction  
✅ Arabic → English Translation  
✅ Structured Output Generation  
✅ High-Speed Inference using vLLM

---

# 🎓 Graduation Project

## 👨‍💻 Author
**Omar Tamer Elazab Melegy**

## 👩‍🏫 Supervisor
**Dr. Doaa Abo Shady**

## 🏫 University
Tanta University — Faculty of Science — Computer Science Department

---

# 🧠 Project Objectives

- Build a complete Arabic NLP fine-tuning pipeline
- Fine-tune LLMs for Arabic tasks
- Apply LoRA & QLoRA techniques
- Improve Arabic understanding & translation
- Optimize inference speed using vLLM
- Create a scalable Arabic AI framework

---

# 🏗️ Architecture & Concepts

## 🔹 Sequential Models
- Vanilla RNN
- LSTM
- GRU
- Bidirectional Networks

## 🔹 Transformer Concepts
- Attention Mechanism
- Self-Attention
- Multi-Head Attention
- Positional Encoding
- Encoder–Decoder Architecture

## 🔹 Large Language Models
- Qwen2.5-1.5B-Instruct
- GPT-4o-mini
- LLaMA-Factory
- vLLM

---

# ⚙️ Technologies Used

| Category | Technologies |
|---|---|
| Programming | Python |
| Deep Learning | PyTorch |
| NLP | Transformers |
| Fine-Tuning | PEFT, LoRA, QLoRA |
| Frameworks | LLaMA-Factory |
| Inference | vLLM |
| Experiment Tracking | Weights & Biases |
| Data Processing | Pandas, NumPy |

---

# 📂 Project Structure

```bash
project/
│
├── dataset/                 # Arabic datasets
├── training/                # Fine-tuning scripts
├── evaluation/              # Evaluation metrics
├── inference/               # Inference pipeline
├── notebooks/               # Jupyter notebooks
├── models/                  # Saved adapters/models
├── app/                     # Deployment application
├── README.md
└── requirements.txt
```

---

# 🗂️ Dataset

The dataset contains:

- Arabic News Articles
- Entity Extraction Samples
- Arabic → English Translation Pairs
- Instruction-Response Data

## ✨ Dataset Features

- High-quality Arabic annotations
- Structured instruction format
- GPT-4o-mini knowledge distillation
- Multiple entity categories

---

# 🔥 Fine-Tuning Pipeline

## Base Model
```python
Qwen2.5-1.5B-Instruct
```

## Fine-Tuning Techniques
- Supervised Fine-Tuning (SFT)
- LoRA
- QLoRA

## Training Framework
```python
LLaMA-Factory
```

---

# 📊 Training Configuration

| Parameter | Value |
|---|---|
| Epochs | 3 |
| LoRA Rank | 64 |
| Quantization | 4-bit |
| Training Type | SFT |
| Framework | LLaMA-Factory |

---

# 🧪 Tasks Performed

## 1️⃣ Arabic Entity Extraction

Extracting:
- Person Names
- Organizations
- Locations
- Dates
- Events

---

## 2️⃣ Arabic → English Translation

Improving translation quality using fine-tuned LLMs.

---

# ⚡ Inference Optimization with vLLM

The project integrates **vLLM** to improve inference performance.

## 🚀 Improvements
- Faster token generation
- Lower latency
- Better GPU utilization
- Scalable deployment

---

# 📈 Results

✅ Better Arabic language understanding  
✅ Improved entity extraction accuracy  
✅ Higher translation quality  
✅ Faster inference speed  
✅ Efficient memory usage with QLoRA

---

# 🔄 Workflow

```text
Arabic Text
     ↓
Preprocessing
     ↓
Instruction Formatting
     ↓
Fine-Tuning (LoRA / QLoRA)
     ↓
Evaluation
     ↓
vLLM Deployment
     ↓
Optimized Inference
```

---

# 📚 Topics Covered

- RNN / LSTM / GRU
- Vanishing Gradients
- Attention Mechanism
- Transformers
- Encoder–Decoder Models
- Decoder-Only LLMs
- Fine-Tuning
- RLHF
- LoRA & QLoRA
- Arabic NLP Challenges

---

# 🛠️ Installation

## Clone Repository

```bash
git clone https://github.com/your-username/project-name.git
cd project-name
```

## Install Requirements

```bash
pip install -r requirements.txt
```

---

# ▶️ Run Training

```bash
python train.py
```

---

# ▶️ Run Inference

```bash
python inference.py
```

---

# 🌟 Future Work

- Retrieval-Augmented Generation (RAG)
- Arabic AI Assistant
- Multi-Lingual Fine-Tuning
- API Deployment
- Real-Time NLP Systems
- Larger Arabic Datasets

---

# 🤝 Acknowledgements

Special thanks to:

- Dr. Doaa Abo Shady
- Tanta University
- Hugging Face
- Open-source AI Community
- LLaMA-Factory Contributors

---

# 📬 Contact

## Omar Tamer Elazab Melegy

💼 AI & NLP Enthusiast  
📧 Add your email here  
🔗 Add your LinkedIn here  
💻 Add your GitHub here

---

# ⭐ Final Note

This project represents a complete practical pipeline for adapting Large Language Models to Arabic NLP tasks using modern fine-tuning strategies and efficient deployment techniques.
