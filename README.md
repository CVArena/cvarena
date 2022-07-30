# CVArena

##### CVArena is a Computer Vision Companion, which can do computer vision functions easily, which makes your code simpler and effective.

## CVArena 0.1

> **avgColor(img) :** 
  - This function helps to find average color of an Image
  - Arguments - (img : image in OpenCV format)

  ```python
  import cv2 # Importing cv2 is necessary
  from cvarena import Image # Importing Image from cvarena
  image = cv2.imread("Image.jpg") # Reading image and converting it to OpenCV format
  average_color = Image.avgColor(image) # Storing Average Color of a image in the variable average_color
  print(f"Average Color: {average_color}") # Printing the Average Color
  ```

> **RGBTOBGR(img) :**
  - This function converts RGB image to BGR
  - Arguments - (img : image in OpenCV format)

  ```python
  import cv2 # Importing cv2 is necessary
  from cvarena import Image # Importing Image from cvarena
  image = cv2.imread("Image.jpg") # Reading image and converting it to OpenCV format
  BGR_Image = Image.RGBTOBGR(image) # Storing BGR Image in the variable BGR_Image
  cv2.imshow("BGR Image", BGR_Image) # Displaying BGR Image
  ```
  
  
> **BGRTORGB(img) :**
  - This function converts BGR image to RGB
  - Arguments - (img : image in OpenCV format)

  ```python
  import cv2 # Importing cv2 is necessary
  from cvarena import Image # Importing Image from cvarena
  image = cv2.imread("Image.jpg") # Reading image and converting it to OpenCV format
  RGB_Image = Image.BGRTORGB(image) # Storing RGB Image in the variable RGB_Image
  cv2.imshow("RGB Image", RGB_Image) # Displaying RGB Image
  ```
  
> **RGBTOGRAY(img) :**
  - This function converts RGB image to GRAY
  - Arguments - (img : image in OpenCV format)

  ```python
  import cv2 # Importing cv2 is necessary
  from cvarena import Image # Importing Image from cvarena
  image = cv2.imread("Image.jpg") # Reading image and converting it to OpenCV format
  GRAY_Image = Image.RGBTOGRAY(image) # Storing GRAY Image in the variable BGR_Image
  cv2.imshow("GRAY Image", GRAY_Image) # Displaying BGR Image
  ```
