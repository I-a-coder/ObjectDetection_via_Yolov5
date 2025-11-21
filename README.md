# White Blood Cell (WBC) Detection using YOLOv5

An object detection project focused on identifying and localizing **14 different classes of White Blood Cells (WBCs)** using the **YOLOv5s** model architecture.

---

## Project Overview

This repository contains:

- Custom YOLOv5 configuration  
- Dataset YAML file  
- Training scripts  
- Sample result images  
- Trained model weights (external link)

The purpose of this project is to accurately **classify and detect WBC types** in microscopic blood smear images.

### Model Details

| Component | Value |
|----------|--------|
| **Framework** | PyTorch (Ultralytics YOLOv5) |
| **Model Used** | `yolov5s.yaml` |
| **Input Size** | 640 × 640 |
| **Training Run** | `wbc_detection_run_3` |
| **Number of Classes** | 14 |

---

## Dataset

The dataset consists of **14 WBC classes**, defined in the included `WBC_v1.yaml` file.

### Class Names (14 classes)

1. None  
2. Myeloblast  
3. Lymphoblast  
4. Neutrophil  
5. Atypical lymphocyte  
6. Promonocyte  
7. Monoblast  
8. Lymphocyte  
9. Myelocyte  
10. Abnormal promyelocyte  
11. Monocyte  
12. Metamyelocyte  
13. Eosinophil  
14. Basophil  

---

## Dataset Download
Dataset link :   https://drive.google.com/drive/folders/1gdP_zikQ8Bo52-nQXBky6LdVCqJmzErN?usp=drive_link
---

