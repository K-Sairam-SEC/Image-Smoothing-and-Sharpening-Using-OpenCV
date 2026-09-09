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

<img width="725" height="358" alt="image" src="https://github.com/user-attachments/assets/6803e104-c370-4f1f-8369-ff448553e658" />

<img width="558" height="266" alt="image" src="https://github.com/user-attachments/assets/86acff4a-1a13-4ec1-b4fe-dcb917c06de6" />

<img width="528" height="263" alt="image" src="https://github.com/user-attachments/assets/8b7394b5-34a9-407a-add8-d33de7cc32fe" />

<img width="745" height="353" alt="image" src="https://github.com/user-attachments/assets/0aa87d35-a85e-4cb2-86aa-e1aaf7633d0a" />

<img width="559" height="263" alt="image" src="https://github.com/user-attachments/assets/aaf1faaa-2119-4041-aad7-bb166f135910" />

<img width="576" height="253" alt="image" src="https://github.com/user-attachments/assets/5d59e6b9-ac21-4ff5-8420-983d59d60884" />


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
