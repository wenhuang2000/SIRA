# SIRA: Secret Image Revealing Attack
The code &amp; training strategies for the paper **Generalizability Vulnerability in the Deep Image Hiding Framework**.


# Training Settings of VQEN：

## Loss Function

secret 1
- revealing loss 2.0
- low-frequency wavelet loss 1.0
- perceptual loss 0.01

secret 2
- revealing loss 4.0
- low-frequency wavelet loss 2.0
- perceptual loss 0.02

## optimizer
- AdamW
- learning rate: $2 \times 10^{-5}$
- epochs 50,000
- learning rate scaled by 0.9 every 3,500 epochs.

# Code
The source code will be released after the paper acceptance.
