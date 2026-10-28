# Geometric Transformations Using OpenCV

---

## Aim

To write a Python program using OpenCV to perform various geometric transformations on an image.

The program performs the following operations:

- Image Translation  
- Image Scaling (Resizing)  
- Image Shearing  
- Image Reflection (Flipping)  
- Image Rotation  

---

##  Software Used

- Anaconda – Python 3.7  
- Jupyter Notebook / VS Code  
- OpenCV (`cv2`)  
- NumPy  
- Matplotlib  

---

##  Algorithm

### Step 1:
Import the required libraries: OpenCV, NumPy, and Matplotlib.

### Step 2:
Read the input image in color mode.

### Step 3: Image Translation
- Create a translation matrix to shift the image  
- Move the image 50 pixels to the right and 80 pixels down  
- Apply transformation using `cv2.warpAffine()`  
- Display original and translated images  

### Step 4: Image Scaling
- Resize the image to 0.5× (downscale)  
- Resize the image to 2× (upscale)  
- Use `cv2.resize()`  
- Display original, downscaled, and upscaled images  

### Step 5: Image Shearing
- Create transformation matrices for:
  - Horizontal shearing  
  - Vertical shearing  
- Apply transformations using `cv2.warpAffine()`  
- Display original and sheared images  

### Step 6: Image Reflection
- Perform flipping using `cv2.flip()`:
  - Horizontal reflection  
  - Vertical reflection  
  - Both axes  
- Display all reflected images  

### Step 7: Image Rotation
- Create rotation matrices for:
  - 45° rotation  
  - 90° rotation  
- Use `cv2.getRotationMatrix2D()` and `cv2.warpAffine()`  
- Display original and rotated images  

---

##  Program

### Developed By:
**Name:** INFANT VIJAY A

### Register No: 212225240052

---

##  Output
<img width="1266" height="373" alt="Screenshot 2026-10-28 182614" src="https://github.com/user-attachments/assets/e82b881d-89b8-448d-8bf6-a1c0dff374a8" />

<img width="1208" height="366" alt="Screenshot 2026-10-28 182638" src="https://github.com/user-attachments/assets/cac7c71e-7b84-4feb-9bfa-b0e8cc581715" />

<img width="1241" height="387" alt="Screenshot 2026-10-28 182859" src="https://github.com/user-attachments/assets/2b9f2ea0-c586-4962-958b-fd75d0eefacc" />

<img width="1225" height="372" alt="Screenshot 2026-10-28 182920" src="https://github.com/user-attachments/assets/4742bf7f-d56a-4228-889a-c7b3a026f58f" />

<img width="1231" height="363" alt="Screenshot 2026-10-28 182931" src="https://github.com/user-attachments/assets/cec9d17b-a28e-484a-90d0-5c929a32691e" />

<img width="1252" height="372" alt="Screenshot 2026-10-28 182940" src="https://github.com/user-attachments/assets/fdb7d3a6-d472-460c-9d3b-ec5004c19ad9" />

### Image Translation
- Original image is displayed  
- Translated image (shifted right and down) is displayed  

### Image Scaling
- Original image is displayed  
- Downscaled image (0.5×) is displayed  
- Upscaled image (2×) is displayed  

### Image Shearing
- Original image is displayed  
- Horizontally sheared image is displayed  
- Vertically sheared image is displayed  

### Image Reflection
- Original image is displayed  
- Horizontally flipped image is displayed  
- Vertically flipped image is displayed  
- Both-axis flipped image is displayed  

### Image Rotation
- Original image is displayed  
- 45° rotated image is displayed  
- 90° rotated image is displayed  

---

##  Result

Thus, various geometric transformations such as translation, scaling, shearing, reflection, and rotation are successfully performed using OpenCV. These transformations demonstrate how images can be spatially manipulated for different computer vision applications.
