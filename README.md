# gpt-from-scratch-pytorch
# Mini GPT from Scratch in PyTorch

A clean, educational implementation of a decoder-only Transformer (nano-GPT style) built from scratch using only PyTorch.

## Features
- Multi-head self-attention with causal masking
- Transformer blocks with pre-norm (LayerNorm)
- Residual connections
- Character-level tokenization
- Training + text generation

## Model Architecture
- Embedding size: 384
- Layers: 6
- Heads: 6
- ~10M parameters (or whatever yours is)

## Results
(Insert sample generated text here)

Training loss curve:  
![Loss Plot](assets/loss.png)

## How to Run

```bash
pip install -r requirements.txt
python train.py
python generate.py
