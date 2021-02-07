# Lending Club Loan Default Detection
## 1 Database
LendingClub Issued Loans Data: https://www.kaggle.com/husainsb/lendingclub-issued-loans
## 2 Methodology
* Fully-connected Neural Network
* CNN\
\
Unsupervised Anomaly Detection
* Autoencoder
* Variational Autoencoder

Correctly identifying defaulters so that the lending club can decide whether a person is fit for sanctioning a loan or not in the future is important. I propose loan default detection methods with LendClub Issued Loans Data using supervised learning methods--**Fully-connected Neural Network** and **Convolutional Neural Network** to estimate the probability of the default, and **self-supervised learning** methods-- **autoencoder** and **variational autoencoder** based **anomaly detection**. In supervised learning, I solved the **data unbalanced problem** using undersampling and oversampling. In the anomaly detection modeling, I used the reconstruction error as an anomaly score for the autoencoder and variational autoencoder.

I used these principles to detect loan default. Experimental results show that undersampled Fully-connected NN, oversampled CNN and Autoencoder are good techniques to solve the problem. And overall, undersampled Fully-connected NN performs best.
## 3 Comments of Python Notebooks
The folder includes codes of the modeling process:\
**1.1 Data_processing_lc_loan.ipynb** is the codes of the training data lc_loan.csv processing. The details of processing methods are included in the comments.\
**1.2 Data _processing_lc_2016_2017.ipynb** is the codes of the test data lc_2016_2017.csv processing. The details of processing methods are included in the comments.\
**2 Fully-connected NN.ipynb** is the codes of the modeling process to estimate the probability of the loan default.\
**3 1D_CNN.ipynb** is the codes of the modeling process to estimate the probability of the loan default.\
**4 Autoencoder.ipynb** is the codes of the modeling process to do autoencoder/VAE based anomaly detection.


