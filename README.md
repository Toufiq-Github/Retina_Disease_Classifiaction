# Retina_Disease_Classifiaction
# Retinal Disease Detection using a Hybrid Deep Learning Model with Explainable AI (XAI)

## 🧠 Overview
This project presents a **hybrid deep learning framework** designed for the accurate classification of retinal diseases, including:
- Diabetic Retinopathy (DR)
- Age-related Macular Degeneration (AMD)
- Glaucoma

The model leverages **ensemble CNN architectures** (VGG16, ResNet50, and MobileNetV2) and integrates **Explainable AI (XAI)** techniques such as **Grad-CAM** and **LIME** to improve both performance and interpretability. The system aims to assist ophthalmologists with more reliable and transparent diagnostic support.

---

## 📁 Dataset
- **Source**: [Kaggle Fundus Images Dataset](https://www.kaggle.com/)
- **Size**: 1,113 labeled retinal fundus images
- **Categories**: Multiple retinal conditions
- **Format**: `.jpeg` images with associated class labels

---

## 🚀 Features
- Hybrid CNN architecture combining multiple pre-trained models
- Explainable AI using Grad-CAM and LIME
- Improved classification accuracy over standalone models
- Clinically meaningful visualizations for decision support
- Evaluation using Accuracy, Precision, Recall, F1-score, and AUC

---

## 🛠️ Tech Stack
- **Language**: Python
- **Deep Learning**: TensorFlow / Keras
- **Model Architectures**: VGG16, ResNet50, MobileNetV2
- **Explainability**: Grad-CAM, LIME
- **Visualization**: Matplotlib, OpenCV

---

## 📊 Evaluation Metrics

| Model         | Accuracy | Precision | Recall | F1-score |
|---------------|----------|-----------|--------|----------|
| VGG16         | 88.74%   | 0.89      | 0.89   | 0.89     |
| ResNet50      | 87.30%   | 0.88      | 0.87   | 0.87     |
| **Hybrid Model** | **91.35%** | **0.92**  | **0.91** | **0.91** |

---

## 📌 Key Highlights
- 📈 **High Accuracy**: Outperformed individual CNN models.
- 🧠 **Better Interpretability**: Visual focus on medically significant regions (macula, blood vessels, lesions).
- ⚙️ **Scalable**: Framework can be expanded for more diseases and integrated into mobile/clinical tools.
- 🔍 **Trustworthy AI**: Enhanced transparency using XAI techniques.

---

## 📷 Sample Visualization

<p align="center">
  <img src="images/gradcam_sample.jpeg" alt="Grad-CAM output" width="400"/>
</p>

> *Grad-CAM highlighting disease-specific retinal regions*

---

## 🔮 Future Work
- ✅ Use larger and more diverse datasets
- ✅ Extend model to cover other retinal diseases (e.g., hypertensive retinopathy)
- ✅ Apply advanced XAI tools like SHAP or Integrated Gradients
- ✅ Optimize for real-time use in clinical/mobile settings

---

## 📄 References
1. Gulshan et al., JAMA, 2016  
2. Ting et al., JAMA, 2017  
3. Selvaraju et al., Grad-CAM, ICCV 2017  
4. Chollet, Xception, CVPR 2017  
5. Tschandl et al., Nat Med, 2020  
6. Zhang et al., MIUA 2019

---

## 💡 Contribution
This project was developed as part of a research initiative to enhance AI-assisted healthcare diagnostics, particularly in ophthalmology. Contributions and suggestions are welcome!

---

## 📬 Contact
For questions or collaboration:  
**Shafaeat Hasan Touiq**  
✉️ safaeathasantoufiq@gmail.com 
📍 Department of Computer Science, East West University

---

## ⭐ License
This project is open-source under the **MIT License**.
