# 📱 YOLOv5 Smartphone Detection

A custom-trained **YOLOv5** model for automatic smartphone detection in images.  
The model was trained on a dedicated dataset to accurately locate and label smartphones in various real-world scenarios.

---

## 🚀 Features
- High-accuracy smartphone detection in static images.  
- Side-by-side comparison (before/after detection).  
- Outputs include annotated images **and** CSV files with bounding box coordinates & confidence scores.  
- Pretrained weights (`best.pt`) included — ready for use or further fine-tuning.  

---

## 📊 Results
- **Annotated Images**: Saved in the `outputs/` folder.  
- **CSV Files**: Contain detection results for deeper analysis.  
- **GIF Demo**: Example before vs after detection.

![Detection Example](outputs/phone_detection_comparison.gif)

---

## 🛠️ Usage
Run detection on your images using the trained weights:

```bash
python detect.py --weights best.pt --source data/test_images/
📂 Project Structure
yolov5_project/
│── best.pt              # Trained YOLOv5 weights
│── detect.py            # Detection script
│── data/                # Dataset (train/test images)
│── outputs/             # Detection results (images + CSV + GIFs)
│── README.md            # Project documentation


🔧 Requirements
Python >= 3.8

PyTorch >= 1.8

Install dependencies:
pip install -r requirements.txt


This project was developed as part of my learning journey in Computer Vision and Deep Learning.
By training YOLOv5 on a custom dataset, I focused on improving smartphone detection accuracy in real-world images.

⭐ If you find this project useful, feel free to star the repo!
هذا المشروع جزء من تعلمي العملي في مجال رؤية الحاسوب و التعلم العميق.
دربت نموذج YOLOv5 على بيانات مخصصة لاكتشاف الهواتف الذكية بدقة أكبر في الصور الواقعية.

