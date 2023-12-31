# Generative Adversarial Network
## Description
The Jupyter Notebook in this repository(`GAN_Tutorial.ipynb`) provides a step-by-step guide on how to build, train and evaluate a GAN using Tensorflow. The notebook covers the following:
- Data Preprocessing: How to load in, normalize, and batch your data for training
- Model architecture: How to create the generator and discriminator networks
- Training loop: How to train the models on a batch of data, and how to implement a training loop
- Evaluation: How to generate new images using our trained GAN
- Saving model for later use


The requirements needed for this project are listed in the `requirements.txt` file.

## Getting Started

To get started clone the repository:
`git clone https://github.com/shreyvish5678/Generative_Adversarial_Network.git`

Then install the requirements:
`pip install -r requirements.txt`

After that, install Jupyter Notebook:
`pip install notebook`

Then, you can open up the notebook with:
`jupyter notebook GAN_Tutorial.ipynb`

The pre-trained models are also in the repository included as `generator.h5` and `discriminator.h5`

There is also more information included on GANs in `GANS.pdf`

You can test the gan in `test_gan.ipynb`
