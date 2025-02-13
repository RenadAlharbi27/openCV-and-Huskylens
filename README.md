## 🏆 Face & Color Detection using Huskylens & OpenCV  

### 📌 Overview  
This repository includes two AI-powered detection implementations:  

1. **Huskylens with Arduino** – Facial detection and identification using the Huskylens AI camera.  
2. **OpenCV with Python** – Color detection and classification in uploaded images.  

---

### 🚀 Project 1: Face Detection using Huskylens (Arduino)  

#### 📌 Requirements  
#### 🛠️ Hardware:  
- **Huskylens AI Camera**  
- **Arduino Uno** (or a compatible board)  
- Jumper wires (for I2C communication)  

#### 💾 Software:  
- **Arduino IDE**  
- **Huskylens Library** (install via Library Manager)  

#### 🔍 How Face Detection Works?  
1. The **Huskylens** AI camera detects a face and assigns it a unique **Face ID**.  
2. The **Face ID** is stored for future recognition.  
3. When the same face appears again, the stored ID is retrieved.  
4. You can link custom names to specific **Face IDs** for easier identification.  

#### 🖼️ Huskylens Output  
📷 The camera displays images with detected and processed faces.  

![image](https://github.com/user-attachments/assets/a559eac1-f654-4eb9-8aea-a4cbe6114c04)


---

### 🎯 Project 2: Color Detection using OpenCV (Python)  

#### 📌 Requirements  
#### 💻 Software:  
- **Python 3.x**  
- **OpenCV**  
- **NumPy**  
- **Google Colab** or **Jupyter Notebook** (for cloud-based execution)  

#### 🎨 How Color Detection Works?  
1. The image is loaded and converted to the **HSV color space**.  
2. Predefined color thresholds are used to identify primary colors such as **Red, Green, Blue, and Yellow**.  
3. The script highlights detected colors and labels them accordingly.  
4. The processed image is displayed with the detected color names.  

#### 🖼️ OpenCV Color Detection Output  
📷 The image is shown with identified colors labeled.  
![image](https://github.com/user-attachments/assets/94780258-7638-4cb0-b5b8-118742b733ed)

---

### 🛠️ Troubleshooting  

#### 🔹 Huskylens Issues  
- Ensure **Huskylens** is correctly connected and trained for facial detection.  
- Verify that Huskylens is set to **Face Recognition Mode**.  

#### 🔹 OpenCV Color Detection Issues  
- Ensure the input image is clear and well-lit.  
- Modify the **HSV color range** to enhance detection precision.
