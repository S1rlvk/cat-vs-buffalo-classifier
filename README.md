# cat-vs-buffalo-classifier
PyTorch CNN that distinguishes cats from buffaloes.


# Cat vs Buffalo Image Classifier 🐱 🦬

A simple convolutional neural network (PyTorch) that tells whether an input
image is a cat or a buffalo.

| Metric | Value |
| ------ | ----- |
| Train images | 8 (4 per class) |
| Val accuracy | 100 % (tiny set) |

## Quick Start (Colab)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](link-to-your-colab)

1. `pip install torch torchvision`
2. Run `cat_vs_buffalo.ipynb`
3. Upload any image – see probabilities.

## Model


Trained for 20 epochs with `CrossEntropyLoss` and Adam (`lr=1e-3`).


 – [@s1rlvk](https://github.com/S1rlvk)
