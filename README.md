# Image-Acquisition-from-Web-Cameraa
## Aim
 
Aim:
 
To write a python program using OpenCV to capture the image from the web camera and do the following image manipulations.
i) Write the frame as JPG 
ii) Display the video 
iii) Display the video by resizing the window
iv) Rotate and display the video

## Software Used
Anaconda - Python 3.7
## Algorithm
### Step 1:
<br>

### Step 2:
<br>

### Step 3:
<br>

### Step 4:
<br>

### Step 5:
<br>

## Program:
``` Python
### Developed By:praveens 
### Register No:212222240077

## i) Write the frame as JPG file
import cv2
video = cv2.VideoCapture(0)
while(True):
    t,frame = video.read()
    cv2.imwrite("212222240077_praveens.jpg",frame)
    result=False
    if cv2.waitKey(1) == ord('b'):
        break
video.release()
cv2.destroyAllWindows()



## ii) Display the video




## iii) Display the video by resizing the window





## iv) Rotate and display the video









```
## Output

### i) Write the frame as JPG image
</br>
</br>


### ii) Display the video
</br>
</br>


### iii) Display the video by resizing the window
</br>
</br>



### iv) Rotate and display the video
</br>
</br>





## Result:
Thus the image is accessed from webcamera and displayed using openCV.
