# Digital-Image-Processing-A2
Question 1
  1.
    Write a function to separate teeth from the rest of the areas.
  2.
    For the above x-ray image, the very high intensity (brightest) shows there is an issue in the teeth. Write a code that separates this region within the teeth and show this affected      part in red color in the output image while the rest of the pixels will remain the same.
  3.
    Write a function that finds the percentage of the pixels that are affected in this image.

Question 2
  1.
    For the above human brain image, you need to apply intensity slicing to separate the bright part from the rest of the brain and the background. This step will result in a binary         image. Display the binary image and original image side by side along with the original image.
  2.
    For the output binary image obtained in a), count the number of white pixels in each row and store in a 1-D array. Plot the data in this array using any plot function.
  3.
    Similarly, do the same task as in b) for all columns in the output image. Count the number of pixels in each column and then plot it.

Question 3
    Apply different log transformations to enhance the above image. For each transformations show the output and also display the values of parameters in the title of the image.         
    Describe which log transformation and which parameters produced the best results.

Question 4
  1.
    Write a function without using any library to count each intensity value in the image. This will give you count of how many times a particular pixel is repeating (counting).     
    Finally, using any library plot these values.
  2.
    Use two custom Box-filters of these sizes: 7x7 and 3x3. Let original image be I, output of 7x7 filter be O7 and output O3. Find the final output as follows and display the resulting     image.
    Final_output = I – Absolute ( O7 - O3 )

Question 5
  You are given two images of a syrup. We can see that one syrup is completely filled while the other one is not properly filled. Write a function that takes an image as input and   
  prints the filled percentage of the bottle. If the filled percentage is less then threshold it should also display a message “Bottle is not properly filled”, otherwise, it will   
  display a message “Bottle is properly filled.”
