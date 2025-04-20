Implementation of different generative network architectures like autoencoders, GANs etc.

## AutoEncoders

### `random_face_generator.ipynb`
- **Purpose**: Implements a Variational Autoencoder (VAE) to generate random face images. It includes training, evaluation, and a Gradio interface for generating faces interactively.
- **Tech Stack**: PyTorch, PyTorch Lightning, Gradio, Matplotlib, and PIL.

### `simple_autoencoder_cnn.ipynb`
- **Purpose**: Demonstrates a convolutional autoencoder for image reconstruction. It includes data preprocessing, model training, and visualization of reconstructed images.
- **Tech Stack**: PyTorch, PyTorch Lightning, WandB, Matplotlib, and PIL.

### `simple_autoencoder.ipynb`
- **Purpose**: Implements both a simple linear autoencoder and a Variational Autoencoder (VAE) for image reconstruction and generation. It includes training and evaluation steps.
- **Tech Stack**: PyTorch, PyTorch Lightning, WandB, Matplotlib, and PIL.

## GANs

### `vanilla_gan.ipynb`
- **Purpose**: Implements a Vanilla GAN to generate MNIST digit images. It includes training of the generator and discriminator, along with visualization of generated images.
- **Tech Stack**: PyTorch, PyTorch Lightning, WandB, Matplotlib, and torchvision.
