  Implementation of a Variational Autoencoder (VAE) utilizing TensorFlow and Keras. Two Datasets were used in training, one contain images from 120 different breeds of dogs, and the other contain images from 10 different subjects varying the lighting, facial expressions, and facial details. Olivetti faces were used to better visualize the capabilities of decoder output into generating random samples of data since that in the experiments in the dog breed dataset, it doesn't become clear due to high variability in subject position and space in the images.

Datasets utilized: 

1. Dog breed dataset: https://www.kaggle.com/c/dog-breed-identification/
2. Olivetti Faces: https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_olivetti_faces.html
