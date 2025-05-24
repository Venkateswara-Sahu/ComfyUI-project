# ComfyUI AI Model Deployment

## 🚀 Project Overview
This project focuses on deploying AI models using **ComfyUI** with support for **LoRA models, Stable Diffusion, Fooocus, TensorFlow, PyTorch**, and more. It includes a backend API for integration and serves AI-generated outputs efficiently.

## 🔥 Features
- ✅ **ComfyUI Workflows** for AI image processing.
- ✅ **LoRA & Checkpoint Integration** for enhanced AI-generated outputs.
- ✅ **FastAPI Backend** for AI model inference via REST APIs.
- ✅ **CUDA Acceleration (if available)** for optimized performance.
- ✅ **Real-time AI Image Processing & Deployment**.

## 🛠️ Technologies Used
- **ComfyUI**
- **Stable Diffusion / Fooocus**
- **LoRA & Checkpoints**
- **FastAPI / Flask (Backend APIs)**
- **TensorFlow / PyTorch**
- **CUDA (if available)**
- **Docker & Deployment Tools**

## 📂 Project Structure
```
ComfyUI-project/
│── api_server/       # Backend API for model inference
│── comfy/            # AI processing engine
│── models/           # AI models, LoRA, and checkpoints
│── notebooks/        # Jupyter notebooks for experimentation
│── scripts/          # Utility scripts for AI processing
│── README.md         # Project Documentation
```

## 🚀 Setup & Installation
### 🔹 Clone the Repository
```bash
git clone https://github.com/Venkateswara-Sahu/ComfyUI-project.git
cd ComfyUI-project
```

### 🔹 Install Dependencies
```bash
pip install -r requirements.txt
```

### 🔹 Run the ComfyUI Backend
```bash
python main.py
```

### 🔹 Start the API Server
```bash
uvicorn api_server.main:app --host 0.0.0.0 --port 8000
```

## 🎯 API Endpoints
| Endpoint          | Method | Description                |
|------------------|--------|----------------------------|
| `/generate`      | POST   | Generates AI images       |
| `/upload_model`  | POST   | Uploads custom LoRA model |
| `/status`        | GET    | Checks API health         |

