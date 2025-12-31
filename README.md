# 🎤 Speech Emotion Detection using TESS Dataset

A data-driven system that classifies emotions from speech signals using the **TESS (Toronto Emotional Speech Set)** dataset. The project extracts meaningful audio features (MFCC, Chroma, Mel Spectrogram) and trains machine learning models to recognize emotional states from voice inputs.

---

## 🔍 Why this matters today

Emotion-aware speech systems are increasingly relevant in:

- **Defense & Security monitoring** (detecting stress, panic, or hostile intent in voice communications)
- **Call analytics & mental-state assessment** in customer support, helplines, and interview platforms
- **Human-computer interaction (HCI)** for adaptive AI assistants
- **Healthcare & wellness tech** for non-intrusive emotional state tracking
- **Forensics & surveillance audio analysis**

This project demonstrates strong fundamentals in **audio data processing, pattern analysis, and model-based decision making**, making it valuable for roles involving **SIEM-like monitoring, threat analysis, data interpretation, and AI strategy**.

---

## ✨ Key Features

- Pre-processing of `.wav` speech samples
- Extraction of:
  - **MFCC (Mel Frequency Cepstral Coefficients)**
  - **Chroma Features**
  - **Mel Spectrogram**
- Model training and evaluation using **supervised learning classifiers**
- Emotion categories recognized:
  - *Happy, Sad, Angry, Fear, Disgust, Neutral, Pleasant Surprise*

---

## 🧠 System Workflow


---

## 🛠️ Feature Engineering

Extracted audio features:

- **MFCC (Mel Frequency Cepstral Coefficients)** — primary emotion differentiator  
- **Chroma Features** — captures tonal variations  
- **Mel Spectrogram** — reflects energy distribution across frequencies  

---

## 🧰 Tech Stack

| Component | Used Tools / Libraries |
|---|---|
| Dataset | TESS Speech Emotion Corpus |
| Audio Processing | Librosa, NumPy |
| ML Classifiers | Scikit-Learn Models |
| Visualization | Matplotlib |
| Development | Jupyter Notebook (`.ipynb`) |

---

## 🚀 Setup & Usage

1. Clone the repository:
```bash
git clone <repo-link>
