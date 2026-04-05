
# Transfer Learning for Image Classification using MobileNetV2

## Description
This project implements **Transfer Learning** using a pre-trained MobileNetV2 model for image classification.  
The model is fine-tuned by freezing initial layers and training custom top layers.  
Additionally, a CNN model is implemented on the MNIST dataset for performance evaluation and comparison.

---

##  Dataset
- Dataset: MNIST  
- Training Samples: 60,000  
- Testing Samples: 10,000  
- Image Size: 28×28 (grayscale)  
- Classes: 10 (digits 0–9)

---

##  Model Implementation

### 🔹 Pre-trained Model
- Model: MobileNetV2 (pre-trained on ImageNet)  
- Top layers removed (`include_top=False`)  
- Custom Dense layers added  

### 🔹 Transfer Learning
- Initial layers frozen  
- Top layers fine-tuned  

### 🔹 CNN Model
- Custom CNN implemented for MNIST classification  
- Used for evaluation and comparison  

---

## Results

| Metric | Value |
|--------|------|
| Accuracy | 98.99% |
| Precision | 98.99% |
| Recall | 98.98% |
| F1 Score | 98.98% |

---

## 📈 Visualizations
- Accuracy vs Epoch graph  
- Loss vs Epoch graph  
- Confusion Matrix  
- Feature Map Visualization  

---

##  Comparison with Research Paper

Compared with LeNet-5:
- Achieved similar performance (~99% accuracy)  
- Minor variations due to architecture differences  

---

##  Possible Improvements
- Increase number of epochs  
- Add Dropout & Batch Normalization  
- Use deeper architectures (ResNet, VGG)  
- Apply data augmentation  

---

## How to Run

### 1️⃣ Install Dependencies
```bash
pip install tensorflow numpy matplotlib seaborn scikit-learn

##  Author
Soha Sayyed
