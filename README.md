# -Image-Caption-Generator-using-CNN-LSTM
This project implements an Image Caption Generator that combines Computer Vision and Natural Language Processing to generate human-like captions for images. It leverages a pre-trained CNN model for image feature extraction and an LSTM-based decoder to generate captions.
# 🖼️ Image Caption Generator using CNN-LSTM

This project implements an **Image Caption Generator** that combines **Computer Vision** and **Natural Language Processing** to generate natural language captions for input images. It leverages a **pre-trained CNN model** for feature extraction and an **LSTM decoder** to generate context-aware image descriptions.

## 📌 Project Overview

This deep learning mini project demonstrates how image captioning can be achieved using a CNN-LSTM architecture built using **TensorFlow** and **Keras** (not from scratch). It includes:

- Image feature extraction using a pre-trained CNN model (e.g., InceptionV3)
- Caption text preprocessing and tokenization
- Sequence padding and train/test split
- CNN-LSTM model architecture
- BLEU Score evaluation
- Result visualization

---

## 🚀 Features

- ✅ Pre-trained CNN (InceptionV3) for visual feature extraction
- ✅ LSTM-based language model for generating image captions
- ✅ BLEU Score evaluation to compare predicted captions with ground truth
- ✅ Text preprocessing, vocabulary building, and caption formatting
- ✅ Visual results showcasing image and generated captions

---

## 🧠 Model Workflow

1. **Image Feature Extraction**  
   Extracts features from each image using a pre-trained CNN model.

2. **Caption Preprocessing**  
   Tokenizes and cleans all captions, building a vocabulary.

3. **CNN-LSTM Architecture**  
   Combines image features with text sequences to predict the next word.

4. **Model Training**  
   Trains the model using padded sequences in batches.

5. **Evaluation**  
   BLEU Score is used to evaluate the model:
   - BLEU > 0.4 indicates good performance
   - Increase training epochs for better results

6. **Caption Generation & Visualization**  
   Displays images with generated captions.

---

## 📈 BLEU Score Evaluation

- BLEU Score is used to compare the generated captions with actual captions.
- A BLEU score above `0.4` is considered a good result.
- Model accuracy improves with increased epochs and dataset size.

---

## 🛠️ Tech Stack

- Python
- TensorFlow & Keras
- NumPy, Pandas
- Matplotlib & PIL
- BLEU Score (NLTK)

---

## 💡 Final Thoughts

- Increasing the number of epochs improves the quality of generated captions.
- Working with large datasets requires significant system resources and time.
- Pre-trained models reduce training time and improve accuracy.

