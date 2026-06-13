# Object Detection in Images and Videos using YOLOv5

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/0x41hd/Object_Detection_YOLOv5/blob/main/object_detection_yolov5.ipynb)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This project demonstrates real-time object detection on both static images and video streams using the official **YOLOv5 (Medium architecture - `yolov5m.pt`)** framework by Ultralytics.

## 🌟 Key Highlights
* **Google Drive Syncing:** Automatically mounts Google Drive to leverage custom stored data assets (`Street.jpg` and `Times.mp4`).
* **Threshold Adjustment Exploration:** Compares baseline execution against a high-confidence filtering threshold (`--conf-thres 0.7`) to optimize object classification.
* **Multi-Media Processing:** Seamless execution over both dense urban photography and sequential frame-by-frame video datasets.

## 🚀 Getting Started

### Installation
Clone this framework repository alongside the official YOLOv5 sub-module:

```bash
# Clone the repository
git clone [https://github.com/0x41hd/Object_Detection_YOLOv5.git](https://github.com/0x41hd/Object_Detection_YOLOv5.git)
cd Object_Detection_YOLOv5

# Clone official YOLOv5 architecture
git clone [https://github.com/ultralytics/yolov5.git](https://github.com/ultralytics/yolov5.git)
cd yolov5
pip install -r requirements.txt
