**EE6222 Machine Vision**
*Quiz1 25Fall*
***
1. An object x may come from A with probability 0.6 or from B with probability 0.4. C contains 5% objects from A and 8% objects from B. Given an object from C, you need to predict whether it comes from A or B. What is the minimum probability of the wrong prediction?  

***
2. A filter of frequency response $H(u, v) = \delta(u, v)$ is applied to an image. What is the gray value of the center pixel in the output image?   
<table border="1" style="width: 405px; height: 115px; margin: 0 auto; border-collapse: collapse; text-align: center; vertical-align: middle;">
  <tr>
    <td style="width: 135px;">1</td>
    <td style="width: 135px;">2</td>
    <td style="width: 135px;">3</td>
  </tr>
  <tr>
    <td>2</td>
    <td>3</td>
    <td>1</td>
  </tr>
  <tr>
    <td>7</td>
    <td>8</td>
    <td>9</td>
  </tr>
</table>

***
3. Given an image
<table border="1" style="width: 405px; height: 115px; margin: 0 auto; border-collapse: collapse; text-align: center; vertical-align: middle;">
<tr>
    <td style="width: 135px;">1</td><td style="width: 135px;">2</td><td style="width: 135px;">3</td>
  </tr>
  <tr>
    <td>4</td><td>5</td><td>6</td>
  </tr>
  <tr>
    <td>7</td><td>8</td><td>9</td>
  </tr>
</table>
and a filter mask
<table border="1" style="width: 405px; height: 115px; margin: 0 auto; border-collapse: collapse; text-align: center; vertical-align: middle;">
<tr>
    <td style="width: 135px;">0</td><td style="width: 135px;">1</td><td style="width: 135px;">0</td>
  </tr>
  <tr>
    <td>1</td><td>-4</td><td>1</td>
  </tr>
  <tr>
    <td>0</td><td>1</td><td>0</td>
  </tr>
</table>
What is the gray value of the center pixel in the output image.

***
4. A median filter of size 3 is applied to an 1-D image of 11 pixels 0, 0, 10, 80, 10, -90, 10, 70, 10, 0, 0. Give the output image of the center 9 pixels in the format of, for example: 3, 5, 2, 4, 6, 8, 1, 9, 5. 
***
5. A mean filter of size 3 is applied to an 1-D image of 11 pixels 0, 0, 10, 80, 10, -90, 10, 70, 10, 0, 0. Give the output image of the center 9 pixels in the format of, for example: 3, 5, 2, 4, 6, 8, 1, 9, 5, round the answer to integers.
***
6. To enhance an image with over-exposure, which point processing method shoud be used?  
**a.** Power transform with the power factor smaller than 1. 
**b.** Logarithm transform.  
**c.** Piecewise linear transform.  
**d.** Power transform with the power factor larger than 1. 
***
7. Class A has training samples 0, 1, 6, 9 and class B has training samples -3, -4, -4, -5. Give a test sample -1, the classification results of minimum Euclidian distance classifier, first nearest neighbour classifier and minimum Mahalanobis distance classifier are respectively:
**a.** B,A,A
**b.** A,B,A
**c.** B,A,B
**d.** A,B,B
***
8. An image is given by
<table border="1" style="width: 405px; height: 115px; margin: 0 auto; border-collapse: collapse; text-align: center; vertical-align: middle;">
<tr>
    <td style="width: 135px;">1</td><td style="width: 135px;">0.5</td><td style="width: 135px;">0.2</td>
  </tr>
  <tr>
    <td>0.5</td><td>0.1</td><td>0.5</td>
  </tr>
  <tr>
    <td>0.7</td><td>0.2</td><td>1</td>
  </tr>
</table>
What is the gray value that has the maximum histogram value?

***
9. Historgram equalization is applied to image 
<table border="1" style="width: 300px; height: 80px; margin: 0 auto; border-collapse: collapse; text-align: center; vertical-align: middle;">
  <tr>
    <td style="width: 150px;">1</td><td style="width: 150px;">2</td>
  </tr>
  <tr>
    <td>4</td><td>5</td>

  </tr>
</table>
Without normalization, what is the equalized gray value of the pixel at the left upper corner?

***
10. Given the data set with -3, -1, 1, 1, 3, 3. Use a rectangular with width 4 to estimate the probability distribution. Please give the PDF at x=0.

