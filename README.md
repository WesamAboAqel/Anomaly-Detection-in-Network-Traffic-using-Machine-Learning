This project aims to detect cyber threats by finding anomalious activities within network traffic.
For this purpose we used CIC-IDS-2017 dataset.
we used three alogorithms: incremental PCA, Knn and random forest.
Since security is a critical task, we decided our metric will be precision, since any false accept can cause catastrophic results, while in false reject the user can simply try again.
Between the three algorithms we used random forest yeilded the best results with precision=0.9967412586650543, followed by Knn with score of and finally IPCA 0.8844473617641094.

