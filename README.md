# 🎨 TP 04: Color Systems in Image Processing  BY Dr Guessoum

## 🎯 Objectives  
1. Understand different color spaces (RGB, HSV, Lab, Grayscale).  
2. Learn how to convert images between these color spaces.  
3. Observe how these conversions affect the perception of an image.  

## 📝 Steps  

### 🔹 1. Load the Image  
Start by loading an image (**`sweet-colorful-candies.jpg`**).  

---

### 🔹 2. RGB Color Space  
#### 📌 2.1 Display the Image in RGB  
- Visualize the image in the **Red-Green-Blue (RGB)** color space.  

#### 📌 2.2 Extract & Display RGB Channels  
- Extract the **R**, **G**, and **B** channels separately and display them.  

---

### 🔹 3. Convert to Other Color Spaces  
#### 📌 3.1 Convert to Grayscale, HSV, and Lab  
Use OpenCV conversion functions:  
```python
gray_image = cv2.cvtColor(image, cv2.COLOR_RGB2GRAY)  # Convert to Grayscale  
hsv_image = cv2.cvtColor(image, cv2.COLOR_RGB2HSV)    # Convert to HSV  
lab_image = cv2.cvtColor(image, cv2.COLOR_RGB2Lab)    # Convert to Lab  
