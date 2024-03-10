This repository contains the code and datasets used for our research on anomaly detection in time series data. We have implemented and compared five different algorithms:

1. K-Nearest Neighbors (KNN)
2. Long Short-Term Memory Autoencoder (LSTM-AE)
3. Isolation Forest
4. Deep Ant
5. LoOp

We have evaluated the performance of these algorithms on both multivariate and univariate time series datasets.

## Datasets

### Multivariate Dataset (SWAT)

For the multivariate analysis, we used the SWAT dataset, which contains approximately 4.5 lakhs (450,000) records. This dataset is significant in size and complexity, making it suitable for testing the robustness of our anomaly detection algorithms in real-world scenarios.

### Univariate Dataset (Synthetic Data)

For the univariate analysis, we generated synthetic time series data using the GUENTAG algorithm. This allowed us to control the characteristics of the data, making it ideal for studying the behavior of our algorithms under controlled conditions. Users can customize the synthetic data by providing input parameters to the GUENTAG algorithm to generate specific types of time series data.


## Citation

If you find our work useful in your research, please consider citing our paper (if available) or this repository. You can find citation details in the respective research paper or in the repository's `CITATION.md` file.
