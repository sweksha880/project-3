# SilentWords - Sign Language Learning Platform

SilentWords is an interactive sign language learning platform powered by AI technology. The application helps users learn and practice sign language through real-time sign detection, personalized tutorials, and sign-to-text conversion. The goal of SilentWords is to make sign language education accessible to everyone and anywhere.

## 🛠️ Tech Stack


### AI Service (Flask API)

- **Flask:** Micro web framework for Python, used for running the AI-based sign language model.
- **TensorFlow/PyTorch (for AI models):** Deep learning frameworks for real-time sign language detection.

## 🚀 Getting Started

### Frontend Setup

Clone the repository and navigate to the frontend directory:

```bash
git clone https://github.com/amardeep-soni/SemicolonHackathon
cd frontend
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Visit `http://localhost:3000` in your browser to access the frontend.

### AI Flask API Setup

Navigate to the model-service directory:

```bash
cd model-service
```

Install Python dependencies:

```bash
pip install -r requirements.txt
```

Start the Flask API:

```bash
python app.py
```

The Flask API will be running at `http://localhost:5000`.

### API Documentation

Once the backend is running, you can explore the API documentation at:

```
https://localhost:7134/swagger/index.html
```

