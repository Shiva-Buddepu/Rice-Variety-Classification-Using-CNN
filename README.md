# Rice Variety Classification Using CNN

This project focuses on classifying five different varieties of rice using **Convolutional Neural Networks (CNNs)**.  
The dataset contains labeled images of rice grains belonging to the following classes:

- **Karacadag**
- **Basmati**
- **Jasmine**
- **Arborio**
- **Ipsala**

The goal is to build an accurate deep learning model that can identify the rice variety from an image.

---

##  Dataset

- **Source:** Kaggle  
- **Classes:** 5 rice varieties  
- **Images:** Pre-labeled and divided by class  
- **Tasks Performed:**
  - Downloading and loading the dataset  
  - Inspecting dataset structure  
  - Counting and plotting images from each class  
  - Preprocessing images for CNN input  


---

##  Steps Performed in the Project

### 1️⃣ Importing the Required Libraries  
All standard libraries for image processing, visualization, and CNN modeling were imported.

### 2️⃣ Dataset Inspection  
- Displayed image samples  
- Checked dataset structure  
- Computed number of images per category  

### 3️⃣ Visualization  
Plotted a **class distribution graph** and sample images from each rice variety.

### 4️⃣ Image Preprocessing  
- Resizing images  
- Normalizing pixel values  
- One-hot encoding labels  
- Splitting dataset into **train**, **validation**, and **test sets**

### 5️⃣ Building the CNN Model  
- Used multiple convolution layers  
- MaxPooling layers  
- Dense and dropout layers  
- Softmax output for 5 classes

### 6️⃣ Model Training  
- Saved the **best model** using `ModelCheckpoint`  
- Used early stopping to prevent overfitting  
- Tracked accuracy and loss curves

### 7️⃣ Evaluation  
Generated:

- **Confusion Matrix**  
- **Classification Report**  
- **Accuracy & Loss Curves**  
- Final model accuracy on test data  

---

## Results

- Achieved high accuracy in identifying rice varieties  
- Best model saved automatically during training  
- Produced detailed classification metrics such as precision, recall, and F1-score
  
---
