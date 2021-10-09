# Convolutional autoencoder using Siamese Neural Networks for noise removal

1) Get MNIST dataset and split it in train / test

2) Create a simple convolutive autoencoder (CAE), and also a CNN (create the model from scratch, don’t use an already made model)

3) Train both models

4) Build a pipeline using the CAE, where you pick the intermediate embedding and add noise to it before reconstructing the input. Create a function for this, taking an image (or a batch of images) and a noise parameter and returning the reconstructed image.

5) For each image, test 10 perturbations using the previous pipeline (use about 10 % noise). Then show images that were having the highest variation (you must find a consistent way to estimate this variation).
