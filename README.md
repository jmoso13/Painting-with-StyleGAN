# Painting_with_StyleGAN
<p align="left">
    <a href="https://colab.research.google.com/github/jmoso13/Painting-with-StyleGAN/blob/main/Painting_with_StyleGAN.ipynb"><img alt="Colab" src="https://colab.research.google.com/assets/colab-badge.svg"></a>  
</p>

# Painting with StyleGAN 🎨
### Hello 👋 welcome to the painting with stylegan notebook. This notebook is intended to
  1. Help explore stylegan's latent space using variational autoencoders as a sort of filter and,
  2. Produce animations interpolating through stylegan's latent space using VAE "palettes" as a way to more graphically interface with the complicated space

The code provided will train a VAE to represent portions of SG's 512-D latent space in 2-D. This representation will be plotted on a regular x/y axis for you to explore, and provides the optional injection of 'color' to your palette to explore less likely sections of the space. Once happy with a palette, get to painting! Draw a line through the space to interp from one image to another, draw a curve to pass through a third section, or draw a circle to create an interp that starts in one location and circles away and around back to the beginning to create loops. Hope you have fun painting!

Tutorial Video: https://youtu.be/pkYHMPoZrkg
