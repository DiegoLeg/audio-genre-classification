# Audio Genre Classification

Three different notebooks are presented:

1. Exploratory Data Analysis: related to an extensive analysis on the GTZAN dataset (http://marsyas.info/downloads/datasets.html). A first hearing of different audio samples of the database is performed.
    - Number of channels.
    - Sampling frequency.
    - Bit Depth.

2. Preprocessing: As the audio parameters are uniform, there is no need to perform resampling. Feature extraction is performed:

  - MFCC (Mel Frequency Cepstral Coefficients).
  - Spectral Centroid.
  - Zero Crossing Rate.

Also, the dataset is divided into train and test datasets, using 20% for testing.

3. Model Training and Evaluation:

Three different models are proposed for this classification task:

- K-Nearest Neighbors.
- Random Forest.
- Convolutional Neural Netwtork.
