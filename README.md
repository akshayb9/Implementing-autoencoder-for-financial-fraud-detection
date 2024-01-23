# Implementing-autoencoder-for-financial-fraud-detection

The objective of this project is to develop and utilize autoencoders for detecting anomalies in various business
datasets. Autoencoders, as self-supervised machine learning models, encode data in a lower-dimensional
space, creating a "signature" to identify anomalies. This project specifically addresses the challenge of
unbalanced data in business environments, where traditional classification and linear regression models often
fall short due to their inability to handle multicollinearity and non-linear relationships. The project will involve
constructing a bottleneck autoencoder for dimensionality reduction, aiming to provide a more nuanced and
accurate analysis than methods like principal component analysis.
Accurate anomaly detection can prevent financial fraud, enhance operational efficiency, and improve customer
experience. By optimizing autoencoder parameters, we aim to provide a scalable, efficient solution adaptable
to diverse business contexts, thus offering a substantial competitive edge and cost-saving potential.

The final product will be a set of bottleneck autoencoder models tailored to analyse four distinct datasets: a
synthetic dataset generated with Python, a Kaggle dataset of firms listed on the NYSE, two Kaggle datasets of credit
card fraud, and a dataset sourced independently by participants. These autoencoders will be capable of
handling the multicollinearity inherent in business data, such as that arising from double-entry accounting, and
will effectively distinguish features indicative of anomalies like fraud or financial failure.

Approaches Used:
1) Ensemble Approach- Autoencoder with SMOTE+ XGBoost (Threshold=0.02)
2) Isolation Random Forest
