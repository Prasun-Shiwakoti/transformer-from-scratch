# GPT from Scratch - Transformer Implementation

A complete implementation of a GPT-style transformer model built from the ground up using PyTorch. This project demonstrates the core concepts behind modern language models by progressively building from a simple bigram model to a full transformer architecture.

## What's Inside

- **Character-level tokenization** using Shakespeare's works as training data
- **Self-attention mechanism** with mathematical foundations
- **Multi-head attention** for parallel processing of different relationships
- **Positional embeddings** to give the model spatial awareness
- **Layer normalization and residual connections** for stable training
- **Complete transformer blocks** with feed-forward networks

## Key Learning Outcomes

- Understanding the mathematical intuition behind self-attention
- Implementing scaled dot-product attention from scratch
- Building multi-head attention mechanisms
- Creating positional encodings for sequence modeling
- Training a language model to generate coherent text

## Model Architecture

The final model includes:
- 6 transformer blocks
- 6 attention heads per block  
- 384-dimensional embeddings
- Context window of 256 characters
- ~5M parameters

## Results

The model progresses from generating random characters to producing Shakespeare-like text that maintains coherent structure and style. Training loss decreases from ~4.0 to ~1.5 over 5000 iterations.

## Acknowledgments

Built following Andrej Karpathy's excellent "Let's build GPT" tutorial, which provides deep insights into transformer architecture and implementation details.
