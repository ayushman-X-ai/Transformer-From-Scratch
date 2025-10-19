# 🧠 Transformer From Scratch (PyTorch)

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python)
![PyTorch](https://img.shields.io/badge/PyTorch-2.0+-EE4C2C?logo=pytorch)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Contributions](https://img.shields.io/badge/Contributions-Welcome-brightgreen)

A complete **Transformer architecture built from scratch** using **PyTorch**, inspired by the paper  
📜 [*Attention Is All You Need* (Vaswani et al., 2017)](https://arxiv.org/abs/1706.03762).

This project demonstrates a full, modular implementation of a Transformer — including **embeddings**, **positional encodings**, **multi-head attention**, **encoder-decoder stacks**, and **attention visualization** — entirely coded by hand.  

---

## 🚀 Features

✅ Implemented **from scratch** using pure PyTorch  
✅ Includes **Encoder** and **Decoder** architecture  
✅ Supports **multi-head self-attention**  
✅ Visualizes **attention maps** for interpretability  
✅ Modular, well-documented code structure  
✅ Fully customizable for any NLP or sequence modeling task  

---

## 🏗️ Architecture Overview

The Transformer model follows the original *Attention Is All You Need* structure:

Input → Embedding → Positional Encoding →
[Encoder Blocks × N] → [Decoder Blocks × N] → Linear → Output

### Components Implemented
- **Input Embedding**
- **Positional Encoding**
- **Layer Normalization**
- **Feed Forward Networks**
- **Multi-Head Attention**
- **Residual Connections**
- **Encoder & Decoder Modules**
- **Attention Visualization**

---

## 📂 Project Structure

pytorch-transformer/
│
├── transformer/
│ ├── embeddings.py
│ ├── positional_encoding.py
│ ├── attention.py
│ ├── encoder.py
│ ├── decoder.py
│ ├── transformer.py
│ └── utils.py
│
├── train.py
├── evaluate.py
├── visualize_attention.py
├── requirements.txt
└── README.md
