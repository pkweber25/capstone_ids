# Adaptive Intrusion Detection via Hybrid Autoencoder–Random Forest

This project implements a hybrid intrusion detection system that combines a Random Forest (RF) classifier and an Autoencoder (AE) anomaly detector using the NSL-KDD dataset. It aims to improve detection accuracy and reduce false positives in a resource-efficient way suitable for free Google Colab compute.

- Cached preprocessing to speed up reruns
- RF baseline, AE anomaly detector, and hybrid RF+AE fusion
- PCA+AE and temporal aggregation extensions

## How to Run
1. Open the notebook in [Google Colab]
2. Set `DATA_DIR` and upload the NSL-KDD dataset (`KDDTrain+.csv`)
3. Run all cells top to bottom
