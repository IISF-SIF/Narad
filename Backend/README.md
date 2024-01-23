# Project Overview

This repository houses an advanced Voice-Activated Assistant, seamlessly integrating state-of-the-art technologies to offer a comprehensive user experience. The project is divided into three main notebooks:

## 1. Finetune.ipynb
In this notebook, we fine-tuned the NousResearch/Llama-2-7b-hf model from Hugging Face on our custom dataset available at VATSAL1729/BhuvanSFTData. The fine-tuning process enhances the model's capabilities and tailors it to our specific needs.

## 2. Recommender.ipynb
The Recommender notebook focuses on providing personalized recommendations to users. We employed various recommendation strategies:
- **Basic Statistics:** Utilized mode-based recommendations.
- **Machine Learning Models:** Implemented k-nearest neighbors for recommendation.
- **Geospatial Recommendations:** Incorporated geopy for location-based suggestions.
- **Contextual Bandit Recommendations:** Leveraged user feedback and collaborative filtering for context-aware recommendations. 

We also created a synthetic dataset specifically tailored for Bhuvan to facilitate a comprehensive evaluation of our recommendation strategies.

## 3. backend-f3.ipynb
This notebook encompasses the entire pipeline necessary for our Voice-Activated Assistant to function seamlessly. The key components include:
- **Indic ASR Model:** Enabling Automatic Speech Recognition for Indic languages.
- **Translational Model:** Facilitating translation between Indic and English languages.
- **FAISS Vector Database:** Utilized for efficient vector search.
- **Large Language Models (LLMs):** Employed for advanced context-aware responses.
- **Gemini API:** Integrated as the primary Large Language Model.
- **TTS Model:** Text-to-Speech functionality for a complete user interaction.

Additionally, the notebook contains the code for running a hosted website on Kaggle using ngrok, ensuring accessibility and ease of use for users.

## Getting Started
Navigate to individual notebooks and follow the instructions within for execution.

Feel free to delve into each notebook to understand the intricacies of the project and contribute to its enhancement. Your feedback and contributions are highly appreciated!

## Acknowledgments
We extend our gratitude to the Hugging Face community and to AI4Bharat for providing such great Open Source models and we would like to thank google for free Gemini API.
