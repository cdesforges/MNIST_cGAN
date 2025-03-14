# Conditional Generative Adversarial Network

This is my implementation of a cGAN trained on MNIST, and is my first generative model. The discriminator's architecture is a CNN.

<img width="531" alt="Screenshot 2025-03-13 at 5 33 28 PM" src="https://github.com/user-attachments/assets/ed739fc0-c687-4b4d-a000-666ec7d8673c" />

Training converges fairly quickly, and the digits start to look solid after around 5 epochs. At epoch 25, the model has fully converged to a state where the loss has been fully minimized.

<img width="531" alt="Screenshot 2025-03-13 at 5 36 11 PM" src="https://github.com/user-attachments/assets/a9fadafc-5184-4514-bbcc-70bcfd858b11" />

There are still a few tehcniques I've yet to implement, like LR scheduling and checkpoint saving.

After the sucess of fine tuning and tinkering with this model architexture, I wanted to try a DDPM to learn a more modern technique. See my MNIST_Diffusion repository for the results.
