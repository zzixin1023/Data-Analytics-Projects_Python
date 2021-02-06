# Lending Club Loan Default Detection
* Fully-connected Neural Network
* CNN\
\
Unsupervised Anomaly Detection
* Autoencoder
* Variational Autoencoder

Correctly identifying defaulters so that the lending club can decide whether a person is fit for sanctioning a loan or not in the future is important. I propose loan default detection methods with LendClub Issued Loans Data using supervised learning methods--**Fully-connected Neural Network** and **Convolutional Neural Network** to estimate the probability of the default, and **self-supervised learning** methods-- **autoencoder** and **variational autoencoder** based **anomaly detection**. In supervised learning, I solved the **data unbalanced problem** using undersampling and oversampling. In the anomaly detection modeling, we used the reconstruction error as an anomaly score for the autoencoder and variational autoencoder.

I used these principles to detect loan default. Experimental results show that undersampled Fully-connected NN, oversampled CNN and Autoencoder are good techniques to solve the problem. And overall, undersampled Fully-connected NN performs best.

