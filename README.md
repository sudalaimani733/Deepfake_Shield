# Deepfake Shield – AI-Powered Fake Image Detection

An AI-powered web application that detects whether an uploaded image is real or AI-generated/deepfake, using Vision Transformers (ViT).

## Features
- Upload an image and get real-time prediction (Real/Fake) with confidence score
- Vision Transformer (ViT) based deep learning model
- Simple, clean web interface for non-technical users
- REST API backend serving the model

## Tech Stack
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Python (Flask/FastAPI - mention whichever you used)
- **ML Model:** Vision Transformer (ViT)
- **Deployment:** Vercel

## How It Works
1. User uploads an image via the web interface
2. Image is sent to the backend API
3. ViT model processes the image and predicts real/fake
4. Result is displayed with confidence percentage

## How to Run Locally
```bash
git clone https://github.com/sudalaimani733/Deepfake_Shield.git
cd Deepfake_Shield/backend
pip install -r requirements.txt
python app.py
```
Open `frontend/index.html` in browser

## Dataset
Trained on a real vs AI-generated image dataset sourced from Kaggle.

## Future Improvements
- Improve model accuracy with larger dataset
- Add support for video deepfake detection
