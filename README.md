# VAE

Variational Auto-Encoders (VAEs) is a generative model built on top of an auto-encoder. First, the encoder network encodes an input into a latent code (a compact Gaussian distribution), and finally the decoder decodes the latent code into the reconstructed input.

### Network architecture
[]!(images/VAE_architecture.png)
[]!(images/VAEnetwork.png)

### Loss Objective
[]!(images/LossObjective.png)

### Loss Plots
[]!(images/VAELOSS.png)

### Results
[]!(VAEResults.png)


#DCGAN
A generative adversarial network (GAN) is a generative model composed of two neural networks: a generator and a discriminator. These two networks are trained in an unsupervised way via a min-max Loss Objective. The generator creates ”realistic” synthetic images given random noise to fool the discriminator, while the discriminator evaluates the given image (real image or synthetic image) for authenticity.

### Network architecture
[]!(images/DCGAN.png)
[]!(images/NetworkDCGAN.png)

### Loss Objective
[]!(images/DCGANLOSS.png)

### Loss Plots
[]!(images/GANLoss.png)

### Results
[]!(GANResult.png)


# DCGAN
A generative adversarial network (GAN) is a generative model composed of two neural networks: a generator and a discriminator. These two networks are trained in an unsupervised way via a min-max Loss Objective. The generator creates ”realistic” synthetic images given random noise to fool the discriminator, while the discriminator evaluates the given image (real image or synthetic image) for authenticity.

### Network architecture
[]!(images/DCGAN.png)
[]!(images/NetworkDCGAN.png)

### Loss Objective
[]!(images/DCGANLOSS.png)

### Loss Plots
[]!(images/GANLoss.png)

### Results
[]!(GANResult.png)


# Cyclic GAN
Image-to-image translation problem describes translating an image from domain A to domain B. The main goal of CycleGAN is to solve the image-to-image translation problem without paired training images.

### Network architecture
[]!(images/CycleGAN.png)

### Loss Objective
[]!(images/cycleLoss.png)

### Loss Plots
[]!(images/CyclicGANLoss.png)

### Results
[]!(CyclicGANResults.png)


