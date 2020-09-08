# Audio Genre Classification

Three different versions are presented, one on each branch of the project. Each one contain three different notebooks, along with some python algorithm for data analysis:

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

Four different models are proposed for this classification task:

- K-Nearest Neighbors.
- Decision Tree.
- Random Forests.
- Logistic Regression.

However, a fifth model related to Neural Networks is on development.

To compare the result across multiple models, we have an additional fifth model, related to Deep Learning and Neural Networks (on development). Thus, the classic Machine Learning approach of extracting features and then using a classifier is compared to a performance of a Convolutional Neural Network.

# Results

The main results for the different architectures is exposed. The best score for the test set is shown:

| Model  | Accuracy | Version |
| ------------- | ------------- | |
| K-Nearest Neighbors  | 0.64  | v1.2 |
| Decision Tree  | 0.49 | v1.2 |
| Random Forests | 0.61 | v1.1 |
| Logistic Regression | 0.54 | v1.1|

In relation to the Deep Learning approach, the results are shown for the different models tested:

| Model  | Accuracy | Version |
| ------------- | ------------- | |
| CNN2D  | -- | v1.2 |
|   |   | |
