# Medical Image Generation with GANs

Custom and pre-trained Generative Adversarial Networks (GANs) built to generate synthetic medical images such as X-rays, and deployed in a Streamlit app.

## Problem
Medical imaging data is scarce and protected by privacy rules. Realistic synthetic images can help with research, training and data augmentation without exposing real patient data.

## Process
1. **Data preparation:** loaded and normalised the medical images and built a data loader.
2. **Custom GAN:** designed a generator, which turns random noise into an image, and a discriminator, which judges real from fake.
3. **Adversarial training:** trained the two networks against each other, tracking generator and discriminator loss and saving sample images at checkpoints to watch quality improve.
4. **Pre-trained GAN:** compared the custom model with a pre-trained GAN to see the gain in image quality.
5. **Review:** inspected generated images visually against real examples.
6. **Deployment:** built a Streamlit app that generates new synthetic images on demand.

## Tools
Python · PyTorch · torchvision · NumPy · Matplotlib · Streamlit · Jupyter

## Skills shown
Generative models · GAN training · Synthetic data · App deployment with Streamlit

## Repository status
The project notebooks and scripts are being prepared for upload and will be added here shortly.

## Programme
Completed as part of the **WorldQuant University Applied AI Lab: Deep Learning for Computer Vision** (Jul 2025).

## Author
**Uchenna Francis Onyeka** · MSc FinTech with Business Analytics, University of Westminster
[LinkedIn](https://www.linkedin.com/in/uchenna-onyeka) · [GitHub](https://github.com/uchenna8243)
