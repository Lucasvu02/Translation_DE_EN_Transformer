Translation Model README

This project trains a German-to-English translation model using an LSTM-based encoder-decoder architecture with TensorFlow and Keras.

Steps

Data Preparation:
Load translatedataset.csv.
Clean, tokenize, and pad the text sequences.
Model Training:
Train the model for 10 epochs, saving the best version based on validation loss.
Model Saving:
The trained model is saved as translation_model_final.keras for future use.
Requirements

Python
TensorFlow
Pandas
