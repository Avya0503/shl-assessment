# Audio Processing and Grammar Analysis Pipeline

## 📝 Description
This pipeline processes audio files to:
1. Transcribe speech using OpenAI's Whisper
2. Analyze grammar errors using LanguageTool
3. Extract linguistic features
4. Train a regression model to predict quality scores

## 🛠️ Requirements
- Python 3.8+
- CUDA 11.7 (for GPU acceleration)
- FFmpeg (for audio processing)

## 📦 Installation
```bash
# Clone repository
git clone https://github.com/yourusername/audio-analysis-pipeline.git
cd audio-analysis-pipeline

# Create virtual environment
python -m venv venv
source venv/bin/activate  # Linux/Mac
# OR
venv\Scripts\activate     # Windows

# Install dependencies
pip install -r requirements.txt
