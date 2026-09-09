# Image Smoothing and Sharpening Using OpenCV

## Aim

To write a Python program using OpenCV to apply different smoothing filters (Averaging, Weighted Averaging, Gaussian, Median) and sharpening filters (Laplacian Kernel and Laplacian Operator) for image enhancement, and display each result separately along with the original image for comparison.

---

## The program performs the following operations:

- Read and display an input image  
- Apply Averaging filter  
- Apply Weighted Averaging filter  
- Apply Gaussian filter  
- Apply Median filter  
- Apply Laplacian sharpening using kernel  
- Apply Laplacian operator  
- Display all outputs for comparison  

---

##  Software Used

- Anaconda – Python 3.7  
- Jupyter Notebook / VS Code  
- OpenCV (cv2)  
- NumPy  
- Matplotlib  

---

##  Algorithm

### Step 1:
Import the required libraries: OpenCV, NumPy, and Matplotlib.

### Step 2:
Read the input image (e.g., `image.jpg`).

### Step 3:
Convert the image from BGR to RGB format for display.

### Step 4:
Apply Averaging Filter using `cv2.blur()`.

### Step 5:
Apply Weighted Averaging Filter using a custom kernel with `cv2.filter2D()`.

### Step 6:
Apply Gaussian Filter using `cv2.GaussianBlur()`.

### Step 7:
Apply Median Filter using `cv2.medianBlur()`.

### Step 8:
Apply Laplacian Sharpening using Kernel with `cv2.filter2D()`.

### Step 9:
Convert image to grayscale and apply Laplacian Operator using `cv2.Laplacian()`.

### Step 10:
Display all filtered images using a grid layout for comparison.

---

##  Developed By

- **Name:** Sairam K 
- **Register No:**  212225240132

---

##  Output

<img width="516" height="249" alt="image" src="https://github.com/user-attachments/assets/ceb3ee91-d9fa-4453-9eb5-8c9240b5da55" />
<img width="717" height="334" alt="image" src="https://github.com/user-attachments/assets/ad0d7c07-8dda-4592-9daa-f45a0efa4738" />
<img width="516" height="249" alt="image" src="https://github.com/user-attachments/assets/cc00f536-0a8c-4ace-9a74-0810a54b7b8e" />
<img width="533" height="249" alt="image" src="https://github.com/user-attachments/assets/8c1d1a55-0553-44e6-855f-f5086c4c54e6" />
<img width="717" height="334" alt="image" src="https://github.com/user-attachments/assets/81434cf8-a682-4262-ae66-f7af7226f818" />

<img width="516" height="249" alt="image" src="https://github.com/user-attachments/assets/a03416b3-0337-405b-8f2a-6b6126bf7916" />

### Smoothing Filters

- Averaging filter produces blurred image  
- Weighted averaging provides smoother result with less distortion  
- Gaussian filter preserves edges better while reducing noise  
- Median filter removes salt-and-pepper noise effectively  

###  Sharpening Filters

- Laplacian kernel enhances edges and fine details  
- Laplacian operator detects edges clearly in grayscale  

---

##  Result

Thus, smoothing filters and sharpening filters are successfully implemented using OpenCV.

The smoothing filters reduce noise and improve image quality, while sharpening filters enhance edges and details for better feature extraction.
