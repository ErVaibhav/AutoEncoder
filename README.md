
# AutoEncoder Project

This repository contains two Keras-based autoencoder implementations:

- **Basic_AE_Keras**: A simple autoencoder for tabular data.
- **FashionMnist_Clustering**: An autoencoder for clustering and visualizing the Fashion MNIST dataset.

## Project Structure

```
Basic_AE_Keras
FashionMnist_Clustering
LICENSE
README.md
```

## Requirements

- Python 3.x
- Keras
- TensorFlow
- scikit-learn
- pandas
- numpy
- matplotlib
- scipy

Install dependencies with:

```sh
pip install keras tensorflow scikit-learn pandas numpy matplotlib scipy
```

## Usage

### 1. Basic Autoencoder for Tabular Data

- Expects a tab-separated CSV file named `your_data.csv` in the project directory.
- Adjust `input_neuron` and `encoding_dim` as needed for your data.

Run:

```sh
python Basic_AE_Keras
```

This will:
- Train an autoencoder on your data.
- Output encoded and decoded representations for the test set.

### 2. Fashion MNIST Clustering Autoencoder

- Downloads and uses the Fashion MNIST dataset automatically.

Run:

```sh
python FashionMnist_Clustering
```

This will:
- Train an autoencoder with a 2D latent space.
- Save cluster visualizations before and after training as PNG files.
- Save the trained autoencoder model as `AE.h5`.

## Outputs

- `AE.h5`: Trained autoencoder model (Fashion MNIST).
- `UNTRAINED_CLUSTER.png`: Latent space visualization before training.
- `TRAINED_CLUSTER_epoch_1.png`: Latent space visualization after training.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## Author

Copyright (c) 2020 ErVaibhav
