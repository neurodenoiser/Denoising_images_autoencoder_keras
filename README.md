# Denoising_images_autoencoder_keras

This project aims at removing different kinds of noise, such as Gaussian. Speckle, Salt and Pepper in images of CIFAR10 dataset using autoencoder.
 
## Getting_started

The project contains training and testing files for CIFAR10 dataset and diiferent measures of comparing the results of the images. 

### Downloading the already trained model

The already trained weights are in the file denoise_autoencoder.h5. Download this file to use testing data.

### Training and Testing

The train file divides adds different noises to CIFAR10 dataset. The model is defined in the file and then the images are trained. The test file is used to train the saved model and test the images generating denoised images and giving results in the form of SSIM, PSNR and RMSE values.

