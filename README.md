# 100DaysOfMLCode

This repository is a part of #100DaysofMLCode challenge. That means, I pledge to code machine learning for at least an hour everyday for the next 100 days, starting from June 20, 2018.

## Day 1-11: June 20-30, 2018

### What I did ?

Learned <b>Linear Algebra</b> from <b>Gilbert Strang</b>'s lectures.

## Day 12: July 1, 2018

### What I did ?

1. Resumed <b>Machine Learning</b> course by <b>Andrew Ng</b> on <b>Coursera</b>.
2. Had completed upto week 4 before.
3. Resumed from week 6.

## Day 13: July 2, 2018

### What I did ?

1. Since it was my birthday, I decided to apply the knowledge that I have gained so far before proceeding further with learning process.
2. Searched for projects and found <b>MNIST Model</b> was the best thing to train to get good hold of concepts as a beginner.

## Day 14: July 3, 2018

### What I did ?

1. Trained the <b>MNIST model</b> for <b>Digit Classification</b>.
2. By Using Tensorflow.
3. Created a neural network model with <b>2 hidden layers</b>, an input layer and an output layer.
4. Achieved accuracy near to about <b>97%</b> after using <b>'Sigmoid'</b> as an activation function.

## Day 15: July 4, 2018

### What I did ?

1. Trained the <b>MNIST model</b> for <b>Digit Classification</b> again but this time I used <b>Convolutional Neural Network</b> or CNN.
2. By Using <b>Tensorflow</b>.
3. Created a neural network model with <b>3 convolutional layers</b>, a <b>fully connected layer</b> and an output layer.
4. Achieved accuracy near to about <b>97.5%</b> after using <b>'Sigmoid'</b> as an activation function and <b>AdamOptimizer</b>.

## Day 16: July 5, 2018

### What I did ?

1. Trained the <b>MNIST model</b> for <b>Digit Classification</b> again using <b>Convolutional Neural Network</b> or CNN.
2. By Using <b>tflearn</b>.
3. Created a neural network model with <b>2 convolutional layers</b>, and <b>2 fully connected layers</b>.
4. Achieved accuracy near to about <b>97.5%</b> after using <b>'Relu'</b> and <b>'Softmax'</b> as activation functions and <b>AdamOptimizer</b>.

## Day 17: July 6, 2018

### What I did ?

1. Trained the <b>MNIST model</b> for <b>Digit Classification</b> again but this time I used <b>Recurrent Neural Network</b> or RNN.
2. By Using <b>Tensorflow</b>.
3. Created a <b>BasicLSTMCell</b>.
4. Achieved accuracy near to about <b>98.5%</b> after using <b>AdamOptimizer</b>.
5. Did not understand fully, will study further about RNN in future.

## Day 18: July 7, 2018

### What I did ?

1. Came to know about <b>Kaggle</b>.
2. Browsed through the website and found various competitions that were going on or were finished in the past.

## Day 19: July 8, 2018

### What I did ?

1. Picked the competition held in 2017 <b>Dogs vs Cats Redux</b> and decided to implement it using <b>CNN</b>.
2. By using <b>tflearn</b>
3. Created a neural network model with <b>6 convolutional layers</b> and <b>2 fully connected layers</b>.
4. Achieved accuracy near to about <b>82%</b> after using <b>'Relu'</b> and <b>'Softmax'</b> as activation functions and <b>AdamOptimizer</b>.
5. Plotted the images using <b>matplotlib</b> to see the results.

## Day 20: July 9, 2018

### What I did ?

1. Completing the previous project involving classification of cats and dogs, I got interested in <b>Image and Video Operations</b>.
2. So I started looking up as to what else can be done in this field.
3. So I found <b>OpenCV</b> played a major role here along with <b>Python Imaging Library</b> or PIL.
4. So started learning <b>OpenCV</b>.

## Day 21: July 10, 2018

### What I did ?

1. Learned to open or load images from local folders or access webcam using <b>imread</b> from <b>cv2</b> library.
2. Learned to display the images using <b>imshow()</b> from <b>cv2</b> library.
3. Learned to display images or plot them using <b>matplotlib</b> library.
4. Learned to draw on the images plotted with <b>matplotlib</b>.

## Day 22: July 11, 2018

### What I did ?

1. Learned to open or load videos from local folders or access webcam using <b>VideoCapture()</b> from <b>cv2</b> library.
2. Learned to read the frames using <b>read()</b> function.
3. Learned to convert color of frames or images using <b>cvtColor()</b> from <b>cv2</b> library.
4. Learned about the codecs and formats associated with them to save the videos read from webcam or local folder using <b>VideoWriter</b> from <b>cv2</b> library.

## Day 23: July 12, 2018

### What I did ?

1. Learned to draw shapes on a loaded image using following functions of <b>cv2</b> library :-
   i)   line()
   ii)  rectangle()
   iii) circle()
   iv)  polylines()
2. Learned to write text on loaded image using <b>putText()</b> of <b>cv2</b> library.

## Day 24: July 13, 2018

### What I did ?

1. Learned to <b>manipulate pixels</b> of a loaded image.
2. Pixels are just <b>coordinates</b> in a image containing a list of three values <b>[Blue, Green, Red]</b>.
3. cv2 loads images in <b>BGR mode</b> so to convert to original color we have to apply <b>cvtColor(image, cv2.COLOR_BGR2RGB)</b>.
4. We can change color of a pixel by altering <b>BGR value</b> at that pixel.
5. We can <b>select</b> a part of picture and <b>copy</b> it over another part of the same picture.

## Day 25: July 14, 2018

### What I did ?

1. Learned <b>masking</b> in OpenCV.
2. Used the following functions :-
   i)   <b>threshold()</b>   --> selects the parts of image between two threshold values.
   ii)  <b>bitwise_not()</b> --> inverts the mask.
   iii) <b>bitwise_and()</b> --> overlaps the mask with background.
   iv)  <b>add()</b>         --> adds two images.
3. Learned different thresholding functions :-
   i)   <b>threshold()</b>         --> normal threshold function.
   ii)  <b>adaptiveThreshold()</b> --> gaussian threshold function.
   iii) <b>threshold()</b>         --> otsu threshold function (did not understand much about it though).
   
## Day 26: July 15, 2018

### What I did ?

1. Learned <b>color filtering</b> in OpenCV.
2. Basically color filtering creates a <b>mask</b> between <b>two ranges of color values</b>.
3. First converted the color of image to <b>hsv</b> using <b>cv2.COLOR_BGR2HSV</b> then overlapped it with frames with <b>bitwise_and()</b> to just show that mask and black background.
4. There was some <b>noise</b> in the background as well as on the mask though.
5. Converted to hsv because <b>color filtering</b> works on <b>brightness</b> or <b>lightness</b> rather than the color values.

## Day 27: July 16, 2018

### What I did ?

1. Learned <b>blurring</b> and <b>smoothing</b> in OpenCV.
2. Basically blurring and smoothing remove the <b>noise</b> as much as possible from the image.
3. For smoothing :-
   i)   A kernel is made which is simply an <b>array of ones</b> of some size e.g. 15x15.
   ii)  Keep the kernel above a pixel and take an <b>average</b> of all 225 (15x15) pixels below it and replace central pixel with this average.
   iii) Repeat for all pixels.
   iv)  Function used --> <b>cv2.filter2D()</b>.
4. For blurring, following functions can be used :-
   i)  <b>cv2.GaussianBlur()</b>
   ii) <b>cv2.medianBlur()</b>
   
## Day 28: July 17, 2018

### What I did ?

1. Learned to apply <b>gradients</b> and implement <b>edge detection</b>.
2. For gradient, following functions can be used :-
   i)  <b>cv2.Laplacian()</b> --> applies laplacian blur.
   ii) <b>cv2.Sobel(frame, datatype, x, y, ksize)</b> --> applies horizontal or vertical gradient if (x=1 and y=0) or (x=0 and y=1).
3. For edge detection, function that can be used --> <b>cv2.Canny()</b> --> converts the image into network of edges.

## Day 29: July 16, 2018

### What I did ?

1. Learned <b>template matching</b> in OpenCV.
2. Function used --> <b>cv2.matchTemplate()</b>
3. Learned <b>corner detection</b> in OpenCV.
4. Function used --> <b>cv2.goodFeaturesToTrack()</b> --> detects corners in an image.
5. Corner detection works best when image is <b>grayscaled</b>.

## Day 30: July 17, 2018

### What I did ?

1. Learned <b>screen recording</b> in OpenCV.
2. Function used --> <b>ImageGrab.grab()</b> function of <b>PIL</b> library
