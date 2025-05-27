# 📚 Next Word Prediction using LSTM
This project demonstrates a Next Word Prediction model built using LSTM (Long Short-Term Memory) networks in TensorFlow/Keras. The model is trained on the complete text of Jane Austen's Pride and Prejudice — a rich and structured literary dataset ideal for learning the contextual patterns of the English language.

🗂 Dataset
The dataset used is the public domain novel Pride and Prejudice by Jane Austen, sourced from Project Gutenberg. The text provides:

  * Natural language structure
  * Diverse vocabulary
  * Long-form narrative and dialogue
  * Ample training data for sequence modeling tasks

🧠 Model Overview
  * Type: LSTM-based language model
  * Input: Sequences of words
  * Output: Predicted next word
  * Framework: TensorFlow / Keras
  * Goal: Predict the most likely next word in a sentence given the previous context

🚀 Key Features
  * Custom tokenizer and sequence generator
  * Data preprocessing including punctuation removal, lowercasing, and tokenization
  * Sequential LSTM layers trained on a literary corpus
  * Model evaluation and sample next-word predictions

📁 Files
  * Pride and Prejudice.txt – training dataset
  * stacked_lstm.ipynb – model training and evaluation notebook (if still in repo)
  * README.md – project overview (this file)

📝 Output Example
   * Input: "it is a truth"
   * Output: "universally"
