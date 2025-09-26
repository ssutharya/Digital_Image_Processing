# Digital_Image_Processing

## Set 1
1. Write a program to do the following:

    a. Read an image  
    b. Get image info  
    c. Find compression ratio for the copied image  
    d. Display negative of an image  

2. Write a program for histogram plotting of an image

3. Write a program to perform histogram equalization

4. Write a program for performing local histogram equalization

5. Develop a program for the following image enhancement operations:

    a. Brightness enhancement  
    b. Contrast enhancement  
    c. Complement of an image  
    d. Bi-level or binary contrast enhancement  
    e. Brightness slicing  
    f. Low-pass filtering  
    g. High-pass filtering  

6. Develop programs for the following geometrical transformations on an image:

    a. Translation  
    b. Rotation  
    c. Scaling  
    d. Skewing  

## Set 2
1. Write a program to perform 4 arithmetic operations between 2 images.  

2. Take a noisy image. Write a program which reduces the noise by averaging the input image by 2, 8, 16, 32, 128. Compare all the resultant images and find which one is noise-free.  

3. Write a program which implements all the types of linear spatial filters using functions.  

4. Implement a program for image convolution and correlation using a rectangular convolution mask of any odd size. The mask should be input as an ASCII text file. Test your program using the following convolutional kernels:  

   a. 3×3 averaging  
   b. 7×7 averaging  
   c. 11×11 averaging  

5. Write a prgoram for implementing median filtering of an img. Add salt and pepper noise to it. Apply the median filter to the noisy img and compare the results.
   
6. Detect the edges in an ing using the following methods and compare the relative performance of these methods:
   
    a. sobel  
    b. prewitt  
    c. roberts  
    d. lapacian of a gaussian (LoG)   
    e. canny

7. Write a program for smoothening an rgb color img with a linear spatial filter.
   
8. Write a program for sharpening an rgb color img with the laplacian filter mask.

9. Take a sample image of size 256*256. Write a program for implementing DFT filtering  

    a. with padding  
    b. without padding  

   and compare the results.

10. Write a program to implement various low pass or smoothening frequency domain filters.

11. Write a program to implement various high pass or sharpening frequency domain filters.

12. Write a program to detect straight lines using horizontal, vertical, and diagonal filter masks.

## Set 3

1. Write a program which resotres a degraded image using direct inverse filtering.

2. Write a prgraom for implementing Wiener filtering for linear img restoration using  

    a. a constant ratio  
    b. auto correaltion function.

3. Write a program to convert an rgb color space to HSI. Display the hue img, saturation img, and the intensity img.

4. Write a program to histogram equalize the intensity component of a color img, and get a new HSI img. Conver the new HSI img to rgb.

5. Write a program to detect the line segements in a binary img using Hough transform.

6. Comsider an image composed of small, non overlapping blobs. Write a program to segment the blobs based on thresholding.
