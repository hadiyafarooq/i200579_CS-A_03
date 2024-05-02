# i200579_CS-A_03
STEPS FOLLOWED FOR THE ASSIGNMENT:
1. Loading Data
2. Preprocessing using Z-score normalization
3. Binary Noise Mask Matrix was calculated.
4. The DataLoader created after preprocessing was masked.
5. The transformer-based autoencoder was trained using the Binary Noise Mask Matrix and training data. The Generator precisely reconstructs the time series data by learning the underlying distribution of normal patterns. By differentiating between actual and reconstructed time series data, the Discriminator places limitations on the reconstructions produced by the Generator.
6. In order to promote significant and discernible latent representations, contrastive constraints were applied to time series data representations.
7. Deviations from the acquired normal patterns are used to identify anomalies.
