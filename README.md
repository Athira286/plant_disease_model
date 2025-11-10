# 🌿 Plant Disease Detection using YOLOv8n

This project implements a **YOLOv8n (You Only Look Once)** object detection model to **detect plant diseases from leaf images**.  
The model identifies diseased regions directly within the image, providing bounding boxes and confidence scores.

---

## 🚀 Project Overview
- Built using the **Ultralytics YOLOv8n** model architecture.  
- Trained on a **custom plant leaf dataset** to detect multiple types of plant diseases.  
- Conducted training in **Google Colab** for a total of **140 epochs**  
  (100 base training + 40 fine-tuning with `pretrained=True`).  
- Achieved practical detection performance with room for further optimization.

---

## 📈 Model Performance

| Metric | Value |
|--------|--------|
| **Precision (B)** | 0.48028 |
| **Recall (B)** | 0.38176 |

> These metrics correspond to bounding-box detection performance.  
> The model effectively learns to localize disease regions but will benefit from additional data augmentation, tuning, and post-processing improvements.

---

## 📂 Files Included
| File | Description |
|------|--------------|
| `APP.ipynb` | Final training notebook (40 epochs with pretrained weights) |
| `best (1).pt` | Trained YOLOv8n weights |
| `results.zip` | Includes training curves (Precision, Recall, F1), confusion matrices, and batch visualizations |

---

## ⚙️ Tech Stack
- **Python**
- **Ultralytics YOLOv8**
- **PyTorch**
- **Google Colab**
- **NumPy**
- **Matplotlib**

---

## 📊 Sample Results
The `results.zip` archive contains:
- Training and validation curves  
- F1, Precision, Recall graphs  
- Confusion matrices (normalized and standard)  
- Detection visualizations showing bounding boxes and predicted disease labels  

---

## 🧠 Next Steps
- Integrate **Grad-CAM / Explainable AI (XAI)** for visual interpretability.  
- Develop a **frontend interface** for real-time detection.  
- Deploy the system using a **Flask or Streamlit web app**.  

---

## 🤝 Author
**Athira Anish**  
B.Tech CSE | SRM Ramapuram  
Focused on Deep Learning, Computer Vision, and Explainable AI.

---

⭐ *If you like this project, consider giving it a star on GitHub!*
