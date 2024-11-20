A project that explores the application of the Bayer pattern and demosaicing in image processing. It includes sampling a colored image with the Bayer pattern to create a mosaic, reconstructing missing R, G, B values using demosaicing, and evaluating the quality of the reconstructed image using metrics such as MAE, MSE, and PSNR.

# Comments
What is intended to be done in this assignment is to sample the colored image taken from the R.C. Gonzalez Digital Image Processing book with the Bayer pattern and then apply the mosaic process to the pixels. After applying the Bayer pattern for the mosaic processes, the missing pixels were completed with demosaicing and a new image was obtained.

When we look at the difference between the demosaiced image and the original image here, a red-yellow dashed stripe is seen on the right edge of the completed image in the demosaicing process. This stripe represents the changes in the new image given to the demosaicing process. A blue-turquoise transformation is seen on the bottom edge of the image that underwent the demosaicing process. Here, the losses after applying the Bayer pattern are detected at the bottom and right edges of the image. When we look at the PSNR value, it is seen that it is above 30 db. The effect of a value above 30 db here is due to the change experienced at the bottom and right edges of the Bayer pattern.
There are also changes when the original image is converted to a mosaic image. Here, the green, red, blue pixels in the pixels resulting from the mosaicing process and the filtered colors and original image pixels are visible. However, as can be seen from the screenshot, green colors are dominant. The reason for the green color weight below is due to the pattern.

R	G	R
G	B	G
Bayer Pattern
