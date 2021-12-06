# DCT-IDCT-on-bmp-image
Compressing a bmp image using discrete cosine transform, coefficient quantization and performed inverse discrete cosine transformed and calculated the PSNR value of the **Steps**<br><br>
<li>The bmp image was converted to ycbcr format and then the y was taken to perform compression
<li>The image was partitioned into uniform blocks of 8*8 matrices
<li>Each matrix was transformed using Discrete cosine transform
<li>Each DCT matrix was quantised using coefficient quantisation
<li>Inverse DCT was applied on the quantised matrices to obtain the compressed image<br><br>
**Final Output**<br><br>
![image](https://user-images.githubusercontent.com/64024900/144798567-4e6c4d15-4fbb-4a6d-9cf5-1cd91bfbe26d.png)

