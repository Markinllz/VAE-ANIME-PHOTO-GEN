# VAE-ANIME-PHOTO-GEN

## Project Summary: Anime Face Generation with VAE

### Project Overview:
Building a **Variational Autoencoder (VAE)** to generate synthetic anime face images from scratch using deep learning.

### What We Used:

**Dataset:**
- AnimeFaceDataset with 63,565 images
- 64x64 pixel RGB anime character faces
- Custom PyTorch Dataset class for image loading

**Technology Stack:**
- **PyTorch** - Deep learning framework
- **Python** libraries: NumPy, Pandas, Matplotlib, OpenCV
- **Kaggle Notebook** environment
- **CUDA** for GPU acceleration

**Model Architecture:**
- **Variational Autoencoder (VAE)** - generative neural network
- **Encoder**: Convolutional layers to compress images into latent space
- **Decoder**: Transposed convolutions to reconstruct images
- **Latent dimension**: 64 (compressed representation)

**Key Components:**
- **Reparameterization trick** for gradient flow
- **KL divergence loss** for regularization
- **Reconstruction loss** (MSE/BCE) for image quality
- **β-VAE** approach with annealing

### Project Goal:
Create an AI model that can:
1. **Learn** the distribution of anime faces
2. **Generate** new, realistic anime characters
3. **Interpolate** between different character styles
4. **Encode** existing images into compact latent representations

### What We Achieved:
- Successfully trained VAE on 63K+ anime images
- Optimized model for stable training and good generation quality
- Created pipeline for both training and inference
- Built robust data loading and preprocessing system

**Result**: A working generative model capable of creating new anime face images by sampling from learned latent space.
