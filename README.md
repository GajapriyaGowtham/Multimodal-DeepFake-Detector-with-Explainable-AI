# Multimodal DeepFake Detector with Explainable AI 🎭🧠

An AI-powered **Multimodal DeepFake Detection System** that detects manipulated **images, audio, and text** using deep learning models with **Explainable AI (XAI)** visualizations.

This project combines multiple AI models into a single Streamlit application to identify fake media and provide transparent explanations using SHAP, heatmaps, and confidence analysis.

---

## 🚀 Features

✅ Detects **Fake vs Real Images**  
✅ Detects **Fake vs Real Audio**  
✅ Detects **AI-generated / Fake Text**  
✅ Interactive **Streamlit Web App**  
✅ Explainable AI Visualizations:
- 🔥 Heatmaps for image/audio
- 🧠 SHAP explanations for text
- 📊 Confidence scores
- 📝 Human-readable reasoning

✅ Multimodal AI pipeline  
✅ User-friendly interface  
✅ Real-time predictions

---

## 🛠️ Technologies Used

- Python
- Streamlit
- TensorFlow / Keras
- PyTorch
- Hugging Face Transformers
- SHAP
- OpenCV
- Librosa
- NumPy
- Matplotlib

---

# 📂 Project Structure

```bash
Multimodal-DeepFake-Detector-with-Explainable-AI/
│
├── app.py
├── deepfake_detector_final.pth
├── audio_deepfake_final_88.keras
├── config.json
├── tokenizer.json
├── tokenizer_config.json
├── model.safetensors
├── logs.txt
├── requirements.txt
│
├── sample_data/
│
└── README.md
```

---

# 🧠 Models Used

| Modality | Model |
|---|---|
| Image Deepfake Detection | CNN / PyTorch Model |
| Audio Deepfake Detection | CNN + Mel Spectrogram |
| Text Fake Detection | BERT Transformer |
| Explainability | SHAP + Heatmaps |

---

# 📸 Explainable AI (XAI)

This project focuses not only on prediction but also on **understanding WHY** the AI predicted something as fake or real.

### 🔥 Image Explainability
- Heatmaps highlight suspicious manipulated regions.

### 🎵 Audio Explainability
- Spectrogram analysis visualizes fake audio patterns.

### 📝 Text Explainability
- SHAP highlights influential words affecting prediction.

Example:
- Positive highlighted words → indicate fake content
- Negative highlighted words → indicate real content

---

# ⚙️ Installation

## 1️⃣ Clone Repository

```bash
git clone https://github.com/GajapriyaGowtham/Multimodal-DeepFake-Detector-with-Explainable-AI.git
cd Multimodal-DeepFake-Detector-with-Explainable-AI
```

---

## 2️⃣ Create Virtual Environment

### Windows

```bash
python -m venv tfenv
tfenv\Scripts\activate
```

### Linux / Mac

```bash
python3 -m venv tfenv
source tfenv/bin/activate
```

---

## 3️⃣ Install Requirements

```bash
pip install -r requirements.txt
```

---

# ▶️ Run the Application

```bash
streamlit run app.py
```

---

# 📊 Sample Predictions

## 🖼️ Image Detection

| Input | Prediction |
|---|---|
| Real Human Face | REAL |
| AI-generated Face | FAKE |

---

## 🎵 Audio Detection

| Input | Prediction |
|---|---|
| Human Voice | REAL |
| AI Voice Clone | FAKE |

---

## 📝 Text Detection

| Input | Prediction |
|---|---|
| Human-written News | REAL |
| AI-generated Fake News | FAKE |

---

# 📈 Future Improvements

- ✅ Video Deepfake Detection
- ✅ Real-time webcam detection
- ✅ Better explainability dashboards
- ✅ Multilingual fake text detection
- ✅ API deployment
- ✅ Cloud deployment

---

# 🎯 Applications

- Fake news detection
- Social media moderation
- Cybersecurity
- Media verification
- Digital forensics
- Voice scam prevention

---

# 🤝 Contributing

Contributions are welcome!

Feel free to:
- Fork the repository
- Create feature branches
- Submit pull requests
- Report bugs
- Suggest improvements

---

# 📜 License

This project is open-source and available under the MIT License.

---

# 👩‍💻 Author

Developed by **Gajapriya Gowtham**

GitHub:  
https://github.com/GajapriyaGowtham

Repository:  
https://github.com/GajapriyaGowtham/Multimodal-DeepFake-Detector-with-Explainable-AI

---

# ⭐ Support

If you found this project useful:

⭐ Star the repository  
🍴 Fork the project  
📢 Share with others

---

# 🛡️ Fighting DeepFakes with Explainable AI

> “AI should not only predict — it should explain.”
