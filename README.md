Contextual LSTM Pathfinder 📖
LSTM-based Literary Language Modeling and Word Prediction

This project implements a deep learning-based language model using Long Short-Term Memory (LSTM) networks to generate context-aware next-word predictions. The model is trained on Shakespeare’s Hamlet to learn literary language patterns and produce coherent text suggestions.

## Overview

The goal of this project is to explore sequence modeling using LSTMs for natural language processing tasks. The model learns contextual dependencies between words and predicts the next word given an input sequence, demonstrating the ability of recurrent neural networks to model language structure.

## Features
Next-word prediction using LSTM-based sequence modeling
Trained on Shakespearean text (Hamlet)
Tokenization and sequence generation pipeline
Interactive interface using Gradio for real-time predictions
Ability to generate context-aware text suggestions

## Model Architecture
Embedding Layer – Converts words into dense vector representations
LSTM Layers – Captures sequential dependencies in text
Dense Output Layer – Predicts probability distribution over vocabulary

## Tech Stack
Python – Core programming language
TensorFlow / Keras – Model building and training
NumPy – Data processing
Gradio – Interactive UI for predictions

## Project Structure
```

├── Project.ipynb        # Model training and experimentation  
├── run.py               # Script to run predictions  
├── LSTM_word.keras      # Trained model  
├── tokenizer.pickle     # Tokenizer for preprocessing  
├── hamlet.txt           # Training dataset  
```

## Installation
```bash
git clone https://github.com/saketpol10/Contextual-LSTM-Pathfinder-Decoding-Literary-Language-Patterns.git
cd Contextual-LSTM-Pathfinder-Decoding-Literary-Language-Patterns
python -m venv .venv
source .venv/bin/activate   # On Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

## Usage

Run the application:
```bash
python run.py
```

Author

Saket Pol

GitHub: https://github.com/saketpol10
LinkedIn: https://www.linkedin.com/in/saket-pol
