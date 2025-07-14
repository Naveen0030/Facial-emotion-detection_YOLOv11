# Facial Emotion Detection using YOLOv11n 😄😠😢

A lightweight and real-time **Facial Emotion Detection** system built using the **YOLOv11n** model. Trained on a dataset of **1227 facial images**, this model can accurately classify seven human emotions from facial expressions—perfect for edge or mobile deployment.

---

## 🧠 Emotion Classes

This model detects and classifies the following emotions:

- 😠 Angry  
- 🤢 Disgust  
- 😨 Fear  
- 😀 Happy  
- 😐 Neutral  
- 😢 Sad  
- 😲 Surprise  

---

## 📊 Model Performance

Trained on **1227 images** and evaluated on **862 annotated instances**. Here are the detection metrics:

| Class     | Precision | Recall | mAP@0.5 | mAP@0.5:0.95 |
|-----------|-----------|--------|--------|-------------|
| Angry     | 0.617     | 0.693  | 0.650  | 0.497       |
| Disgust   | 0.788     | 0.944  | 0.957  | 0.939       |
| Fear      | 0.625     | 0.691  | 0.715  | 0.551       |
| Happy     | 0.717     | 0.839  | 0.852  | 0.637       |
| Neutral   | 0.576     | 0.715  | 0.631  | 0.475       |
| Sad       | 0.512     | 0.688  | 0.626  | 0.502       |
| Surprise  | 0.934     | 0.888  | 0.963  | 0.956       |
| **Overall** | **0.681** | **0.780** | **0.771** | **0.651** |

---

## ⚙️ Model Details

- **Model**: YOLOv11n (fused)
- **Layers**: 238
- **Parameters**: 2.58M
- **GFLOPs**: 6.3
- **Speed per image**:
  - Preprocess: 0.2ms  
  - Inference: 1.6ms  
  - Postprocess: 5.8ms  

> ✅ The best trained weights are saved as `best.pt` and can be used directly for **real-time emotion detection**.
