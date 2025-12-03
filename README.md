# Deepfake Image Detection

A full-stack AI-powered application for detecting deepfake and AI-generated images using deep learning.

## 🚀 Features

- **AI-Powered Detection**: Uses EfficientNet-B0 deep learning model for accurate deepfake detection
- **Real-time Analysis**: Fast inference with confidence scores and detailed results
- **Modern UI**: Clean, professional React/Next.js frontend with drag-and-drop support
- **High Accuracy**: Trained on 140K real and fake face images dataset
- **Responsive Design**: Works seamlessly on desktop and mobile devices

## 📋 Prerequisites

- Python 3.8+
- Node.js 18+
- pip (Python package manager)
- npm

## 🛠️ Installation

### Backend Setup

1. Navigate to the API directory:
    ```bash
    cd AI/api
    ```

2. Create a virtual environment:
    ```bash
    python -m venv venv
    ```

3. Activate the virtual environment:

    **Windows:**
    ```bash
    venv\Scripts\activate
    ```
    
    **macOS/Linux:**
    ```bash
    source venv/bin/activate
    ```

4. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

5. Ensure the trained model is placed at:
    ```
    AI/models/model.pth
    ```

### Frontend Setup

1. Navigate to the frontend directory:
    ```bash
    cd frontend
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

## 🚀 Running the Application

### Start the Backend Server

1. Navigate to the API directory:
    ```bash
    cd AI/api
    ```

2. Activate virtual environment (if not already activated)

3. Start the server:
    ```bash
    python main.py
    ```

The API will be available at `http://localhost:8000`

### Start the Frontend

1. Navigate to the frontend directory:
    ```bash
    cd frontend
    ```

2. Start the development server:
    ```bash
    npm run dev
    ```

The application will be available at `http://localhost:3000`
