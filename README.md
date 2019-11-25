# MNSIT-Digit-Recognition-TF2
A CNN network trained on 40k examples, giving an accuracy of 98.6% on 28k test set without data augmentation.

CNN architecture : 784 - [32C3-32C3-32C5S2] - [64C3-64C3-64C5S2] - 128 - 10 ; dropout=20%.

Raw implementation on TF2.0 (no APIs used).

![](CNN%20arch..png)
