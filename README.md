

# 🧠 YOLOv8-Gradio-Detector

A simple, interactive object detection application using the YOLOv8 model powered by [Ultralytics](https://github.com/ultralytics/ultralytics), with support for both Google Colab execution and a local Gradio web interface.

This project enables users to:
- Upload any image (.jpg, .png) and detect objects in real-time.
- Visualize the results with bounding boxes and confidence scores.
- Launch a clean Gradio UI for fast testing and demonstrations.

---

## 🔧 Features

✅ YOLOv8 inference (custom or pre-trained `.pt` models)  
✅ Clean Gradio interface for real-time detection  
✅ Google Colab compatibility for online testing  
✅ Automatic visualization and result saving  

---

## 🚀 Getting Started

### 1. Clone the Repository

git clone https://github.com/your-username/YOLOv8-Gradio-Detector.git
cd YOLOv8-Gradio-Detector
2. Install Required Packages

pip install -r requirements.txt
Or install manually:


pip install ultralytics opencv-python gradio ipywidgets nest_asyncio
3. Place Your YOLOv8 Model
Save your trained model file (e.g., best.pt) in the root directory.
Update the path in app.py or detect_image.ipynb if needed.

### 🖼️ Usage Options
Option A: Google Colab (No installation required)
Open the detect_image.ipynb notebook in Google Colab

Upload your YOLOv8 model and image

Run all cells and see detection results instantly

### 👉 Perfect for quick testing or demos!

Option B: Run Locally with Gradio UI

python app.py
This will launch a local Gradio interface in your browser:

Upload an image

Click "Detect"

See annotated detection results

Optionally exit with "Exit" button

### 📁 File Structure

YOLOv8-Gradio-Detector/
├── app.py                # Gradio-based app
├── detect_image.ipynb    # Google Colab detection script
├── requirements.txt      # Required packages
└── README.md             # This file
### 🧪 Example Output
Input Image	Detected Output

(Replace above with real samples in the docs/ folder if available.)

### 📄 License
This project is licensed under the MIT License.
You are free to use, modify, and distribute this project for research or commercial purposes.

#### 🤝 Contributing
Pull requests and feature suggestions are welcome!
If you find a bug or have a feature request, open an issue.

### ✨ Acknowledgments
Ultralytics YOLOv8

Gradio

Google Colab

### 🔗 Connect
Made with ❤️ by Muhammad Abdullah]
For questions or collaborations, contact: [abdullah21533@gmail.com]
