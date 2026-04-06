# 🐶 DogX CNN – Dog Breed Classification using ResNet152

## 📌 Project Overview  
DogX CNN is a deep learning-based image classification system that identifies dog breeds from images using a ResNet152 Convolutional Neural Network with transfer learning.  

The project focuses on fine-grained image classification, where subtle visual differences such as fur texture, ear shape, and patterns are important.  

Built using PyTorch, the model is trained on the Stanford Dogs Dataset and enhanced with data augmentation techniques to improve accuracy and generalization.

---

## 🎯 Objectives  
- Identify dog breeds from images  
- Use transfer learning (ResNet152) for high performance  
- Apply data augmentation to improve model robustness  
- Evaluate model performance using standard metrics  
- Build a scalable and deployable system  

---

## ⚙️ Tech Stack  

- **Programming Language:** Python  
- **Deep Learning:** PyTorch, TorchVision  
- **Data Handling:** NumPy, Pandas  
- **Visualization:** Matplotlib  
- **Deployment (Optional):** ONNX, TorchScript, Flask  
- **Environment:** Google Colab / Local GPU  

---

## 🧠 Model Architecture  

- Base Model: ResNet152 (Pre-trained on ImageNet)  
- Approach: Transfer Learning  
- Loss Function: Cross-Entropy Loss  
- Optimizer: Adam  
- Fine-tuning: Modified final layers for classification  

---

## 🔄 Workflow  

Dataset Collection (Stanford Dogs Dataset)
            ↓
Image Preprocessing
(Resizing, Cropping, Normalization, Augmentation)
            ↓
Model Setup (ResNet152 - Transfer Learning)
            ↓
Model Training (Loss Optimization)
            ↓
Validation & Hyperparameter Tuning
            ↓
Inference (Predict Dog Breed)


---

## 🖼️ Image Preprocessing Techniques  

- Image resizing and cropping  
- Normalization  
- Random flipping and rotation  
- Data augmentation for better generalization  

---

## 📊 Evaluation Metrics  

- Accuracy  
- Precision  
- Recall  
- F1 Score  
- Confusion Matrix  

---

## 🚀 Key Features  

- High accuracy using transfer learning  
- Handles fine-grained breed differences  
- Scalable to large datasets  
- Ready for deployment (ONNX / TorchScript)  
- Supports real-time inference  

---

## 🌍 Applications  

- Pet adoption platforms  
- Veterinary diagnostics  
- Mobile apps for breed recognition  
- Lost pet identification  
- Dog competitions and verification  

---

## 📦 Dataset  

- Stanford Dogs Dataset  
- Contains labeled images of multiple dog breeds  
- Used for training and validation  

---

## ▶️ How to Run  

1. Open the notebook in Google Colab  
2. Upload or mount the dataset  
3. Install dependencies:
   ```bash
   pip install torch torchvision numpy pandas matplotlib
4. Run all cells to train the model
5. Upload a dog image to predict the breed

   
---

## 📈 Scalability & Performance
- Supports large datasets (100+ breeds)
- Can be trained on free GPU platforms like Google Colab
- Deployable on mobile using ONNX / TorchScript
- Suitable for real-time applications

---
  🏫 Institution

SRM Institute of Science and Technology
Department of Computing Technologies

Course: Digital Image Processing (DIP) – Mini Project

---
📌 Conclusion

This project demonstrates the effectiveness of deep learning and transfer learning (ResNet152) for fine-grained image classification tasks like dog breed recognition.

The model achieves strong performance and can be extended for real-world applications in pet care, veterinary services, and mobile-based AI systems.


