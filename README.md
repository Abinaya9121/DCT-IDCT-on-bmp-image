# DCT-IDCT-on-bmp-image
Compressing a bmp image using discrete cosine transform, coefficient quantization and performed inverse discrete cosine transformed and calculated the PSNR value of the 
# Steps<br>
<li>The bmp image was converted to yCbCr format and then the y was taken to perform compression
<li>The image was partitioned into uniform blocks of 8*8 matrices
<li>Each matrix was transformed using Discrete cosine transform
<li>Each DCT matrix was quantized using coefficient quantization
<li>Inverse DCT was applied on the quantized matrices to obtain the compressed image.
<li>Quantitative analysis of Image using PSNR(Peak Signal to Noise Ratio)
  
# Final Output<br>
![image](https://user-images.githubusercontent.com/64024900/144798567-4e6c4d15-4fbb-4a6d-9cf5-1cd91bfbe26d.png)

