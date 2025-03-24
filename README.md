# Speech-Synthesis


# **Low-Resource Language Identification using TTS-Generated Data**  

## **Overview**  
This project explores the use of TTS-generated speech to enhance low-resource spoken language identification (LID). The approach involves transcribing real-world speech, generating synthetic speech using TTS models, and evaluating the quality of generated audio using PESQ scores. Additionally, human-generated and TTS-generated speech are analyzed using three LID models—EPACA, EPACATDNN, and Wave2Vec—to evaluate the effectiveness of TTS models based on accuracy, F1-score, and other LID performance metrics.   

## **Workflow**  
1. **Transcription:** 150 Speech data of English, Hindi and Chinese from [VoxLingua107](https://cs.taltech.ee/staff/tanel.alumae/data/voxlingua107/) is transcribed using Whisper AI.  
2. **TTS Generation:** Transcriptions are converted to speech using multiple TTS models.  
3. **Evaluation:** PESQ scores are calculated to compare the quality of original and generated speech.
4. **LID Model Testing:** Three LID models—EPACA, EPACATDNN, and Wave2Vec—are used to classify human-generated and TTS-generated speech.
5. **Performance Metrics Calculation:** Accuracy, F1-score, Cavg, and Equal Error Rate (EER) are computed for each language and TTS model using LID models.
6. **Analysis & Comparison:** Results are compiled into spreadsheets to review model performance and speech variations. 

## **Models & Tools Used**  
- **Speech Transcription:** Whisper AI  
- **TTS Models:** Generates speech from transcriptions using Tacotron2, XTTS, and RainyEdge2 
- **Evaluation:** PESQ Score for objective speech quality assessment
- **LID Models:** EPACA, EPACATDNN, and Wave2Vec
- **Evaluation Metrics:** PESQ for speech quality assessment, accuracy, F1-score, Cavg, and EER for LID evaluation

 ## **Drive Link for Audio Data & PESQ Scores**  
📂 [Google Drive - Audio Data & PESQ Scores](https://drive.google.com/drive/folders/1t9bLSbJXKImJqzgOHpy7FfpEM9PKCZ-H?usp=drive_link)  

### **Folder Structure** 
```
📂 Transcriptions/
├── 📂 English Transcriptions/
├── 📂 Hindi Transcriptions/
└── 📂 Chinese Transcriptions/
📂 Human Generated Audio/
├── 📂 English/ (150 audio files from VoxLingua)
├── 📂 Hindi/ (150 audio files from VoxLingua)
└── 📂 Chinese/ (150 audio files from VoxLingua)
📂 Machine Generated Audio/
├── 📂 Tacotron2/
│   ├── 📂 English/ (150 machine-generated audios)
│   ├── 📂 Hindi/ (150 machine-generated audios)
│   ├── 📂 Chinese/ (150 machine-generated audios)
│   └── 📄 PESQ Scores
├── 📂 XTTS/
│   ├── 📂 English/ (150 machine-generated audios)
│   ├── 📂 Hindi/ (150 machine-generated audios)
│   ├── 📂 Chinese/ (150 machine-generated audios)
│   └── 📄 PESQ Scores
└── 📂 RainyEdge/
    ├── 📂 English/ (150 machine-generated audios)
    ├── 📂 Hindi/ (150 machine-generated audios)
    ├── 📂 Chinese/ (150 machine-generated audios)
    └── 📄 PESQ Scores
📂 LID Evaluation/
├── 📂 EPACA/
│   ├── 📄 Accuracy, F1-score, Cavg, EER
├── 📂 EPACATDNN/
│   ├── 📄 Accuracy, F1-score, Cavg, EER
└── 📂 Wave2Vec/
    ├── 📄 Accuracy, F1-score, Cavg, EER
```

## **Team Members**  
<p align="center">
    <a href="https://github.com/Somie12">
        <img src="https://github.com/Somie12.png" width="80" height="80" style="border-radius: 50%;" alt="Somie12">
    </a>
    <a href="https://github.com/ash3-codes">
        <img src="https://github.com/ash3-codes.png" width="80" height="80" style="border-radius: 50%;" alt="ash3-codes">
    </a>
    <a href="https://github.com/Debidutta3">
        <img src="https://github.com/Debidutta3.png" width="80" height="80" style="border-radius: 50%;" alt="Debidutta3">
    </a>
    <a href="https://github.com/HimansuMuduli1">
        <img src="https://github.com/HimansuMuduli1.png" width="80" height="80" style="border-radius: 50%;" alt="HimansuMuduli1">
    </a>
    <a href="https://github.com/UtpalikaAcharya">
        <img src="https://github.com/UtpalikaAcharya.png" width="80" height="80" style="border-radius: 50%;" alt="UtpalikaAcharya">
    </a>
</p>

