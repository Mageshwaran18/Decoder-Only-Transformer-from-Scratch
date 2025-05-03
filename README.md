# Decoder-Only Transformer from Scratch

This project implements a decoder-only Transformer architecture from scratch using PyTorch and PyTorch Lightning. The model is designed to take two input statements and generate a predicted output sequence, demonstrating the key mechanisms of Transformer-based language modeling such as self-attention, positional encoding, and autoregressive decoding.

## 📌 Features

- Built entirely using PyTorch and PyTorch Lightning for modular training
- Implements Transformer decoder blocks from the ground up
- Accepts two input statements and generates an output sequence by learning contextual relationships
- Designed for educational purposes to understand the internals of Transformers

## 🚀 How It Works

1. **Data Preparation**: Two text statements are tokenized and embedded
2. **Model Architecture**:
   - Positional Encoding
   - Multi-Head Self-Attention
   - Feed-Forward Networks
   - Layer Normalization and Residual Connections
3. **Training Loop**: Uses PyTorch Lightning for streamlined training
4. **Prediction**: The model generates an output sequence based on the two inputs

## 🧰 Requirements

- Python 3.8+
- PyTorch
- PyTorch Lightning

Install dependencies with:
```bash
pip install torch pytorch-lightning
```

## 📈 Training

The model is trained using synthetic examples with two input sequences. You can modify the notebook to use any dataset or input format.

## 🧪 Example Usage

```python
input_1 = "The cat sat on"
input_2 = "The dog barked at"
output = model.generate(input_1, input_2)
print(output)  # Predicted continuation
```

## 🧠 Learnings

This project helps understand:
- How decoder-only Transformers operate
- Building and training a Transformer manually using PyTorch
- The mechanics of attention and token prediction

## 📚 Reference

StatQuest with Josh Starmer [ https://www.youtube.com/watch?v=bQ5BoolX9Ag ]
