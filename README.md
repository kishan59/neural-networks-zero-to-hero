# Neural Networks: Zero to Hero

This repository contains my code implementations, notes, and projects from Andrej Karpathy's [Neural Networks: Zero to Hero](https://karpathy.ai/zero-to-hero.html) series. The course builds deep learning models from the ground up, starting from basic backpropagation math all the way to a modern GPT architecture.

## Repository Structure

* **01-micrograd:** An autograd engine and neural network built from scratch.
* **02-makemore:** Character-level language models (Bigram, MLP, CNN, WaveNet).
* **03-nanogpt:** A Transformer-based Generative Pretrained Transformer built from scratch.
* **04-tokenizer:** A custom implementation of the Byte Pair Encoding (BPE) algorithm.

## Getting Started & Missing Files

To keep this repository clean and lightweight, large machine learning datasets and trained model weights (`.pt` files) are excluded via `.gitignore`. 

**To run this code locally:**
1. Clone this repository: `git clone https://github.com/kishan59/neural-networks-zero-to-hero.git`
2. Open the respective `.ipynb` notebook in VS Code or Jupyter.
3. **Fetching Datasets:** The code cells at the top of the `makemore` and `nanoGPT` notebooks contain Python scripts (using `requests` or `wget`) to automatically download the necessary training data (such as `names.txt` and the Tiny Shakespeare dataset). Simply run the notebook cells in order, and the data will be pulled into your local directory automatically.