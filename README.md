
# LSTM & RNN Comparison Notebook

This repository contains a Jupyter Notebook that demonstrates the implementation and comparison of Recurrent Neural Networks (RNN) and Long Short-Term Memory (LSTM) networks using PyTorch. These models are applied to time-series sequence prediction tasks.

## 📘 Notebook: `LSTM&RNN.ipynb`

### ✅ Features

- **Introduction to RNN and LSTM architectures**
- **PyTorch implementations** of both RNN and LSTM models
- **Synthetic data generation** for sequence modeling
- **Training loops and loss monitoring**
- **Model comparison based on performance and behavior**
- **Visualization of predictions** to highlight differences between RNN and LSTM

### 🧠 Models

1. **RNN (Recurrent Neural Network)**  
   - Captures sequential dependencies
   - Suitable for short-term patterns

2. **LSTM (Long Short-Term Memory)**  
   - Designed to retain long-term dependencies
   - Mitigates the vanishing gradient problem

### 📊 Output

- Visualization of model predictions vs actual sequences
- Loss curves for training performance
- Commentary on effectiveness and limitations of each model

### 🛠️ Requirements

Make sure you have the following libraries installed:

```bash
pip install numpy matplotlib torch
```

### ▶️ Run the Notebook

You can run the notebook using:

```bash
jupyter notebook LSTM&RNN.ipynb
```

Or open it in platforms like **Google Colab** or **JupyterLab**.

---

## 📂 File Structure

```
├── LSTM&RNN.ipynb     # Main notebook comparing RNN and LSTM
├── README.md          # Project description and instructions
```

---

## 📌 Notes

- The notebook is designed as a learning tool for understanding how RNN and LSTM behave in sequence modeling tasks.
- The models use synthetic sine wave sequences as input data to highlight pattern prediction capability.

---

## 📬 Contact

For any suggestions or feedback, feel free to open an issue or contact the repository maintainer.
