# Adverserial Training
We train a simple convolutional neural network on the MNIST dataset, then we perform adverserial training showcasing the trade-off between robustness and accuracy. Lastly, we compare FGSM, PGD and Trades. 

## Results

| Training Method | Clean Accuracy | PGD Accuracy | FGSM Accuracy | Robustness Gap |
|-----------------|----------------|--------------|---------------|----------------|
| **Standard** | **98.94%** | 85.75% | 6.11% | 13.19 |
| **FGSM** | 98.61% | 75.61% | **84.76%** | 23.00 |
| **PGD** | 98.54% | **95.96%** | 51.80% | 2.58 |
| **TRADES** | 98.24% | 96.09% | 68.72% | **2.15** |
