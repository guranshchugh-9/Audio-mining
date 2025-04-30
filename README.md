# 🚀 YouTube Video Intelligence Pipeline

<div align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue" alt="Python">
  <img src="https://img.shields.io/badge/License-MIT-green" alt="License">
  <img src="https://img.shields.io/badge/Workflow-Audio→Text→QA-orange" alt="Workflow">
</div>

## 🌟 Overview
An end-to-end system that transforms YouTube videos into an interactive knowledge base using cutting-edge AI.
![Pipeline Visualization](https://github.com/guranshchugh-9/YouTube-Video-Intelligence-Pipeline/blob/main/data/assets/Certainly!%20Here's%20a%20streamlined%20overview%20of%20your%20fintech%20platform's%20user%20flow_%20-%20visual%20selection-39.png?raw=true)

## IN DEPTH FLOW OF THE PIPELINE
![Pipeline Visualization](https://github.com/guranshchugh-9/Audio-mining/blob/main/data/assets/deepseek_mermaid_20250429_d4f867.png?raw=true)

## ✨ Key Features
| Feature | Description |
|---------|-------------|
| **🎧 Smart Audio Processing** | Download, denoise, and chunk YouTube audio |
| **✍️ AI-Powered Transcription** | Accurate text conversion using Whisper |
| **🧹 Intelligent Text Cleaning** | Remove fillers, segment sentences |
| **🔍 Deep Content Analysis** | Summarization, entity recognition, KWIC |
| **❓ Interactive Q&A** | Get precise answers about video content |

## 🛠️ Installation
```bash
# Clone repository
git clone https://github.com/guranshchugh-9/youtube-ai-pipeline.git
cd youtube-ai-pipeline

# Install dependencies
pip install -r requirements.txt

# Download NLP model
python -m spacy download en_core_web_sm
```

## 🏗️ Project Structure
```bash
youtube-ai-pipeline/
├── notebooks/
│   ├── 1-transcribe.ipynb
│   ├── 2-data_cleaning.ipynb
│   ├── 3-summarise_entity.ipynb
│   ├── 4-KWIC_analysis.ipynb
│   └── 5-Question_Answering.ipynb
├── data/
│   ├── audio_chunks/
│   ├── csv_files/
│   ├── embeddings/
│   ├── json_files/
│   ├── text_files/
│   ├── wav_files/
│   └── embeddings/
├── .env.example
└── requirements.txt
```

## 🚀 Quick Start
1. Get your free Groq API key
2. Create .env file:
```bash 
GROQ_API_KEY=your_key_here
```
3. Run notebooks sequentially:
```bash 
jupyter notebook notebooks/1-transcribe.ipynb
```

## 🧩 Tech Stack
<div align="center"> <img src="https://img.shields.io/badge/Whisper-Transcripts-9cf" height="25"> <img src="https://img.shields.io/badge/spaCy-NLP-red" height="25"> <img src="https://img.shields.io/badge/FAISS-Vector_Search-yellow" height="25"> <img src="https://img.shields.io/badge/Groq-High_Speed_AI-blue" height="25"> <img src="https://img.shields.io/badge/Python-FFmpeg-orange" height="25"> </div>

## 📜 License
Distributed under the MIT License. See LICENSE for more information.

<div align="center"> Made with ❤️ by <b>GURANSH CHUGH</b><br> <a href="https://github.com/username/youtube-ai-pipeline/issues">Report Bug</a> · <a href="https://github.com/username/youtube-ai-pipeline/discussions">Request Feature</a> </div> ```

