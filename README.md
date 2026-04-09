# SpeechFix: Speech Emotion & Confidence Analyzer

**SpeechFix** is a deep learning-based web application that analyzes speech signals to detect emotions and assess speaker confidence levels. It helps public speakers, educators, and professionals improve their communication skills through actionable insights.

## 🚀 Features

- 🎤 **Speech Analysis** – Analyze uploaded or recorded speech samples.
- 😊 **Emotion Classification** – Detects emotions like Happy, Sad, Angry, and Neutral.
- 📊 **Confidence Assessment** – Rates speaker confidence as High, Medium, or Low.
- 🧠 **Deep Learning Model** – Uses a CNN-LSTM architecture for accurate classification.
- 🎵 **Audio Feature Extraction** – Employs Librosa (MFCC, pitch, tone, energy).
- 🌐 **Interactive Web Interface** – Built with React (frontend) and Flask (backend).
- 🧹 **Noise Reduction** – Preprocessing step to improve prediction accuracy.

## 🧪 How It Works

1. User uploads or records a speech sample.
2. Audio is preprocessed (noise reduction, normalization).
3. Features like MFCCs, pitch, tone, and energy are extracted.
4. The CNN-LSTM model predicts:
   - **Emotion** (Happy, Sad, Angry, Neutral)
   - **Confidence** (High, Medium, Low)
5. Results are displayed in an easy-to-understand visual format.

## 🛠️ Tech Stack

| Layer       | Technology                          |
|-------------|-------------------------------------|
| Frontend    | React                               |
| Backend     | Flask                               |
| ML Framework| TensorFlow / Keras (CNN-LSTM)       |
| Audio Processing | Librosa                        |
| Language    | Python                              |

## 📁 Project Structure
speechfix/
├── backend/
│ ├── app.py # Flask server
│ ├── model.py # Load and run CNN-LSTM model
│ ├── preprocess.py # Noise reduction & feature extraction
│ └── requirements.txt
├── frontend/
│ ├── src/
│ ├── public/
│ └── package.json
├── models/
│ └── emotion_confidence_model.h5
├── README.md
└── demo/ # Screenshots / demo assets

## 📸 Screenshots

### Home Page
![Home Page](demo/homepage.png)

### Audio Upload/Record Page
![Upload Page](demo/upload.png)

### Result Analysis Page
![Result Page](demo/result.png)

## 📈 Performance Evaluation

The model achieves high accuracy in both emotion recognition and confidence level estimation. Feature extraction using MFCC and deep learning-based classification ensures robust performance across different speakers and environments.

## 🧠 Model Architecture

- **CNN Layers** – Extract spatial features from MFCC spectrograms.
- **LSTM Layers** – Capture temporal dependencies in speech.
- **Dense Layers** – Output emotion and confidence predictions.

## 🔮 Future Enhancements

- Real-time speech analysis
- Enhanced noise reduction algorithms
- Support for more emotions and confidence levels
- Multilingual speech support

## 📚 References

Key research papers that inspired this project (see full list in project presentation):

1. He et al. – MF-BERT for multimodal sentiment analysis (IEEE, 2022)
2. Zhang et al. – AdaMoW for multimodal sentiment analysis (IEEE, 2023)
3. Xu et al. – CMJRT for multimodal sentiment analysis (2022)
4. Wu et al. – Multimodal Multi-loss Fusion Network (IEEE, 2022)
5. Kumar et al. – Sentiment-aware ASR for SER (ACII, 2022)
6. Lee et al. – TrustSER: Fine-tuning pre-trained speech embeddings (ICASSP, 2021)

> Full reference list available in the project documentation.

## 👥 Team

- **Mrs. Saumya Sadanandan** – Assistant Professor (Project Guide)
- **B.Tech Project Team (2021–2025)**

## 📄 License

This project is for academic and research purposes.

---

## 🙏 Acknowledgments

Special thanks to all researchers whose work contributed to the development of SpeechFix.

---

⭐ If you find this project useful, consider giving it a star on GitHub!
