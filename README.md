## Aim:
To write a Python program to detect the lines using Hough Transform.

## Software Required:
Anaconda - Python 3.7

## Algorithm:
### Step1:

Import all the necessary modules for the program.
### Step2:

Load a image using imread() from cv2 module.
### Step3:

Convert the image to grayscale.
### Step4:

Using Canny operator from cv2,detect the edges of the image.
### Step5:

Using the HoughLinesP(),detect line co-ordinates for every points in the images.Using For loop,draw the lines on the found co-ordinates.Display the image.
## Output

### Input image and grayscale image
<img width="236" height="409" alt="image" src="https://github.com/user-attachments/assets/9aa7abc9-af4e-4a8b-974a-7c2f61ccd690" />

### Canny Edge detector output
<img width="236" height="409" alt="image" src="https://github.com/user-attachments/assets/5f85529e-6857-499c-90b2-3c0966c4ee4b" />



### Display the result of Hough transform
<img width="240" height="409" alt="image" src="https://github.com/user-attachments/assets/c96df4bd-08e7-48a2-a687-f26104d7f058" />

