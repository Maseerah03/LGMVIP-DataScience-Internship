# Next Word Prediction using LSTM

This project was completed as part of my Data Science Internship at LetsGrowMore (October 2023 batch). The objective was to build a neural language model that can predict the next word in a given phrase using Long Short-Term Memory (LSTM) networks.

## Objective

To train a sequential deep learning model capable of predicting the next word in a sentence based on preceding word sequences. The project involves natural language preprocessing, word tokenization, one-step sequence modeling, and training an LSTM-based neural network for text prediction.

## Tools and Libraries Used

- Python  
- TensorFlow / Keras  
- NumPy  
- matplotlib  
- pickle (for tokenizer serialization)

## Summary of Work

- Loaded a custom text corpus and cleaned it by removing newline characters and punctuation.
- Tokenized the text using Keras Tokenizer and created one-step word sequences.
- Encoded the sequences as input (`X`) and output (`y`) pairs and applied one-hot encoding to the labels.
- Built a deep learning model using:
  - Embedding layer for word representations
  - Two stacked LSTM layers (1000 units each)
  - Dense layer with ReLU activation
  - Final softmax output layer for word classification
- Compiled the model using categorical crossentropy loss and the Adam optimizer.
- Trained the model with early stopping and learning rate reduction callbacks.
- Visualized training accuracy and loss using matplotlib.
- Saved the trained model and tokenizer for future use.
- Demonstrated predictions for example text prompts using the trained model.

## Key Outcomes

- Successfully trained an LSTM-based text model to predict the next word in given phrases.
- Implemented full preprocessing pipeline: tokenization, vocabulary indexing, and sequence generation.
- Visualized model training performance using accuracy and loss graphs.
- Gained experience with sequence modeling, embeddings, and LSTM architecture for NLP tasks.

## Files Included

- `Next_Word_Prediction.ipynb` – Google Colab notebook with complete implementation.
- `README.md` – Project overview and methodology.

## Dataset

The input text used for training was a custom `.txt` file uploaded to the Colab environment. It was preprocessed and tokenized within the notebook.  
(Note: The raw text file is not included in this repository.)

## Acknowledgement

This project was developed during my internship at LetsGrowMore under the guidance of Mr. Aman Kesarwani.
