# OPENING--AND-CLOSING
## Aim
To implement Opening and Closing using Python and OpenCV.

## Software Required
1. Anaconda - Python 3.7
2. OpenCV
## Algorithm:
### Step1:
Import the necessary packages


### Step2:
Create the Text using cv2.putText

### Step3:
Create the structuring element

### Step4:
Use Opening operation

### Step5:
Use Closing Operation
 
## Program:
### Dinesh Karthik R
### 212224230068
``` Python
# Import the necessary packages
import cv2
import numpy as np
import matplotlib.pyplot as plt

# Create a blank image

# Create the Text using cv2.putText



# Create the structuring element

# Add text on the image using cv2.putText
font = cv2.FONT_HERSHEY_SIMPLEX
cv2.putText(image, 'Open and Close', (100, 250), font, 1, (255, 255, 255), 2, cv2.LINE_AA)

# Use Opening operation


# Create a simple square kernel (3x3)
kernel = np.ones((3, 3), np.uint8)
# Display the input image
plt.imshow(cv2.cvtColor(image, cv2.COLOR_BGR2RGB))  # Convert BGR to RGB for displaying
plt.title("Input Image with Text")
plt.axis('off')

# Use Closing Operation

# Display the result of Opening
plt.imshow(cv2.cvtColor(opened_image, cv2.COLOR_BGR2RGB))  # Convert BGR to RGB
plt.title("Opening Operation")
plt.axis('off')







```
## Output:

### Display the input Image
<img width="1647" height="975" alt="image" src="https://github.com/user-attachments/assets/4aff04e9-0c3e-4430-8329-7ab9c3df971a" />


### Display the result of Opening
<img width="1172" height="516" alt="image" src="https://github.com/user-attachments/assets/a7e1a073-2ea6-4c36-9dd2-7c22ea14912c" />


### Display the result of Closing
<img width="1275" height="508" alt="image" src="https://github.com/user-attachments/assets/8e306bfe-9a16-4019-b440-80142015abb2" />


## Result
Thus the Opening and Closing operation is used in the image using python and OpenCV.
