# Deepfake Image Detection Tool Using Xception Architecture

This project is a web-based Deepfake Image Detection Tool developed for Apex Broadcasting Network Ltd to verify the authenticity of digital images before publication. The system uses a deep learning model based on the Xception architecture to accurately distinguish between real and manipulated images.

## Features
- Image upload and deepfake detection
- Xception-based deep learning detection engine
- Confidence score for each prediction
- Deepfake literacy and awareness content
- Secure image handling with CSRF protection and rate limiting

## Technology Stack
- Backend: Python (Flask)
- Frontend: HTML, CSS, JavaScript
- Deep Learning Model: Xception (TensorFlow/Keras)
- Security: CSRF protection, rate limiting, secure headers

## Project Structure
- `app.py` – Flask backend and detection logic  
- `templates/index.html` – User interface  
- `static/` – Images and frontend assets  
- `best_xception_model_finetuned.keras` – Trained model  
- `uploads/` – Temporary image storage  

## How to Run Locally
```bash
pip install -r requirements.txt
python app.py
