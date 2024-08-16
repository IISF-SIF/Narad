# Project Overview

## Dynamic Query Resolution System

### Overview
Welcome to the Dynamic Query Resolution System – a robust and scalable solution designed to handle text conversations in all 22 major languages of India. This project integrates cutting-edge technologies, including AI4Bharat ASR & Translational models, FAISS vector database, Gemini API, and various HuggingFace models to deliver efficient and context-aware responses. 🌐✨

### Key Features

1. **Speed Modes**
   - 🚀 Superfast: Provides responses in 40ms using semantic search.
   - 🚄 Fast/Normal: Utilizes semantic search and Large Language Models for context-aware responses.

2. **GPU Utilization**
   - 🎮 All models have undergone quantization and are integrated onto a singular P100 GPU for streamlined and efficient GPU utilization.

3. **Personalization**
   - 🎨 Recommendations based on Contextual Bandits, Collaborative Filtering, Machine Learning, and geo-specific preferences enhance user personalization.

4. **Text and Intention Classification**
   - 🤖 A BERT and Keras based model serves as a multi-class text and intention classifier, augmenting the recommendation system.

5. **Dataset Enhancement**
   - 📊 Fine-tuning and Reinforcement Learning with Transformer Reinforcement Library by HuggingFace on custom-created Bhuvan datasets enhance model performance.

6. **User Interface**
   - 💻 Developed a React-based Web Application with a user-friendly interface capable of receiving multi-modal input, including both textual and voice inputs.

7. **Backend Implementation**
   - 🚀 FastAPI (Python) serves as the hosting platform for models, inferences, and API functionalities.

8. **Deployment**
   - 🚀 Backend deployed on Kaggle, harnessing the computational power of GPU resources.
   - 🔐 Secure private tunnel established between the frontend and backend using Ngrok.

9. **Database Integration**
   - 📂 Firebase, a non-relational database, stores crucial project data, including user conversation history, queries, and preferences. This database plays a key role in enabling optimal context derivation during each session.


## Getting Started

Clone the repository:
   ```
   git clone https://github.com/IISF-SIF/Narad
   ```

## Demonstration Video

   **Watch the demonstration video on Google Drive 🎥**: https://drive.google.com/drive/folders/11ODoqNLnvPUhRi3eZ50uVys6g3HXM468

<div align="center">

# Contributors

**Arav Jain**: Developed the multilingual, multi-speed RAG pipeline for delivering efficient, context-aware responses.

**Vatsal Jha**: Implemented the user-specific recommender system, finetuned and detoxified the models.

**Ayushman Kar**: Led backend implementation, database integration, and deployment.

**Dilshad Sukheswala**: Managed backend development and user interface design.


[![Arav Jain](https://img.shields.io/badge/Arav_Jain-%E2%9D%A4%EF%B8%8F-brightgreen)](https://github.com/AravJain007)
[![Vatsal Jha](https://img.shields.io/badge/Vatsal_Jha-%E2%9D%A4%EF%B8%8F-blue)](https://github.com/Vatsal-Jha256)
[![Ayushman Kar](https://img.shields.io/badge/Ayushman_Kar-%E2%9D%A4%EF%B8%8F-red)](https://github.com/KarAyushman)
[![Dilshad](https://img.shields.io/badge/Dilshad-%E2%9D%A4%EF%B8%8F-orange)](https://github.com/DILSHAD477)

</div>

