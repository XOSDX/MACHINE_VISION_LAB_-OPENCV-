                                                                      <img width="361" height="140" alt="image" src="https://github.com/user-attachments/assets/457c8551-5ed4-4185-b649-53182399e152" />

# Machine Vision Lab
This repository contains the implementation of various **Machine Vision Lab experiments** including image processing, filtering, segmentation, edge detection, and texture analysis using Python (OpenCV, NumPy, Matplotlib, and scikit-image).
---

## 📂 Lab Experiments

### **Lab 1: Basic Image Operations**
1. Read a black and white image and display:
   - Black and white pixels separately
   - Image in black and white channels
2. Read a color image and separate the **Red, Green, and Blue channels**
3. Convert an **RGB image to CMY (negative image)**
4. Convert an **RGB image to HSI and back to RGB**

---

### **Lab 2: Gray Level Transformations & Filtering**
1. **Image Negative** – Inverts intensity values of pixels  
2. **Gamma Correction** – Adjusts brightness of an image  
3. **Log Transformation** – Enhances dynamic range  
4. **Image Enhancement** – Low Pass & High Pass filtering using Gaussian filter  
5. **Noise Filtering** – Gaussian filter for denoising  

---

### **Lab 3: Histogram Equalization**
- Implement histogram generation, plotting, and equalization.
- Example with a sample numerical dataset and visualization of histograms and line graphs.

---

### **Lab 4: Spatial Filters**
1. **Median Filter** – Removes noise while preserving edges  
2. **Min Filter** – Reduces intensity by taking the minimum in a neighborhood  
3. **Max Filter** – Enhances bright regions by taking the maximum in a neighborhood  

---

### **Lab 5: Edge Detection**
- Implement edge detection using:
  - **Sobel Operator**
  - **Robert Operator**
  - **Prewitt Operator**

---

### **Lab 6: Image Segmentation**
1. **Thresholding (Binary Segmentation)**  
2. **Region Growing Algorithm**  

📌 Includes a Google Colab link for notebook execution.

---

### **Lab 7: Watershed Segmentation**
- Implements **watershed algorithm** for separating overlapping objects.

---

### **Lab 8: Texture Analysis using GLCM**
- Compute **Gray Level Co-occurrence Matrix (GLCM)**  
- Extract texture features:
  - Contrast
  - Dissimilarity
  - Homogeneity
  - Energy
  - Correlation
  - ASM (Angular Second Moment)  
- Display GLCM matrix and analyze results.

---

## 🛠️ Technologies Used
- Python
- OpenCV (`cv2`)
- NumPy
- Matplotlib
- scikit-image

---

## 🚀 How to Run
1. Clone the repository or download the code files.
2. Install dependencies:
   ```bash
   pip install opencv-python numpy matplotlib scikit-image
   ```
3. Run each experiment file:
   Just copy paste the code on your system either locally through VSCode or use Colab.
   or open the provided **Google Colab notebooks** for Labs 6–8.

---

## 📎 Google Colab Links
- [Lab 6 Notebook](https://colab.research.google.com/drive/1QThx-6z5lP0Ux9SDSUZPih0YkHE_zjPl?usp=sharing)  
- [Lab 7 & 8 Notebook](https://colab.research.google.com/drive/1KLBZ139Cd7m0XIt4JCfKxF__rQf9TCfj?usp=sharing)

---

## 👤 Author
**Name:** Om Subrato Dey  
---
