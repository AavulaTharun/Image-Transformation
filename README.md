# Image-Transformation
## Aim
To perform image transformation such as Translation, Scaling, Shearing, Reflection, Rotation and Cropping using OpenCV and Python.

## Software Required:
Anaconda - Python 3.7

## Algorithm:
### Step1:
<br>

### Step2:
<br>

### Step3:
<br>

### Step4:
<br>

### Step5:
<br>

## Program:
```python
Developed By:Aavula Tharun
Register Number:212221240003

import numpy as np
import cv2
import matplotlib.pyplot as plt
input_image = cv2.imread("bird.jpg")
input_image = cv2.cvtColor(input_image,cv2.COLOR_BGR2RGB)
plt.axis('off')
plt.imshow(input_image)
plt.show()
rows,cols,dim = input_image.shape
i)Image Translation


ii) Image Scaling



iii)Image shearing



iv)Image Reflection




v)Image Rotation




vi)Image Cropping





```
## Output:
### original image:
![original](https://user-images.githubusercontent.com/93427201/166110969-f6f92431-eaf0-4dc0-b3a6-2e1753d9843f.png)

### i)Image Translation
<br>
<br>
<br>
<br>

### ii) Image Scaling
<br>
<br>
<br>
<br>


### iii)Image shearing
<br>
<br>
<br>
<br>


### iv)Image Reflection
<br>
<br>
<br>
<br>



### v)Image Rotation
<br>
<br>
<br>
<br>



### vi)Image Cropping
<br>
<br>
<br>
<br>



## Result: 

Thus the different image transformations such as Translation, Scaling, Shearing, Reflection, Rotation and Cropping are done using OpenCV and python programming.
