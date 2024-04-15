# Lab Report: Exploring Deep Learning Architectures with PyTorch

## Objective
The primary objective of this lab is to gain familiarity with the PyTorch library and to build deep neural network architectures for Auto-encoders (AE), Variational Auto-encoders (VAE), and Generative Adversarial Networks (GANs). The lab aims to accomplish this by:

### Part 1: AE and VAE
1. Implementing an auto-encoder architecture and training it on the MNIST dataset.
2. Implementing a variational auto-encoder architecture and training it on the MNIST dataset.
3. Evaluating the two models by plotting relevant metrics such as loss and KL divergence.
4. Visualizing the latent space of the two models.

### Part 2: GANs
1. Defining the Generator, Discriminator, Loss Function, and setting up the training process using PyTorch.
2. Evaluating the GAN model by plotting loss and other relevant metrics for both the Generator and Discriminator.
3. Generating new data and comparing its quality to the original dataset.

## Implementation
### Part 1: AE and VAE
- **Auto-encoder Architecture**: Implemented a standard auto-encoder architecture with encoder and decoder components.
- **Variational Auto-encoder Architecture**: Developed a variational auto-encoder architecture, incorporating a reparameterization trick for the latent space.
- **Training**: Trained both models on the MNIST dataset, experimenting with different hyper-parameters to optimize performance.

### Part 2: GANs
- **GAN Architecture**: Defined the Generator and Discriminator networks for the GAN model.
- **Training Setup**: Configured the training process, including setting up data loaders, initializing optimizers, and enabling GPU training.
- **Evaluation**: Evaluated the GAN model by monitoring loss and other relevant metrics for both the Generator and Discriminator.
- **Data Generation**: Generated new data samples using the trained Generator and compared their quality with the original dataset.

## Conclusion
- **AE and VAE Evaluation**: Through plotting loss and KL divergence, it was observed that VAE tends to have a lower reconstruction error compared to AE, indicating its ability to better capture the underlying data distribution.
- **Latent Space Visualization**: Visualizing the latent space revealed that VAE produces a more structured and organized representation compared to AE.
- **GAN Performance**: The GAN model showed promising results in generating abstract art images, with loss metrics indicating convergence and quality comparable to the original dataset.
- **Learning Synthesis**: The lab provided valuable hands-on experience with PyTorch and deep learning architectures, emphasizing the differences between AE, VAE, and GANs, and their applications in image generation and representation learning.


