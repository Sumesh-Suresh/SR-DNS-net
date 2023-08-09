# SR-DNS-net
Auto-encoder for image super resolution 

Input images of low resolution of size is fed to the SR-DNS model. 
The SR-DNS model is a combination of U-net and inverse residual blocks of mobile net.
The model is trained on 900 pairs of low and high resolution image. 
PSNR and SSIM are the metrics used for the comparing the prediction and ground truth.
