# Sentiment Classification on IMDB Movie Reviews

This project builds three deep learning models to classify IMDB movie reviews as **positive** or **negative**.  
The models used are:

- Simple RNN  
- 1D CNN  
- LSTM  

The IMDB dataset is loaded directly from Keras, where each review is already converted into a sequence of numbers.  
Each number represents a word, and padding is used so all reviews have the same length.

---

## 📌 What the Project Does (Simple Explanation)

1. **Loads the IMDB dataset**  
   - The dataset contains 50,000 movie reviews.  
   - Keras provides it in a “ready-to-use” numerical form.

2. **Preprocesses the data**  
   - Pads all sequences to the same length (e.g., 200 words).  
   - This makes it easier for neural networks to process.

3. **Builds three models**  
   - **Simple RNN:** Learns from the sequence one step at a time.  
   - **1D CNN:** Uses filters to detect important word patterns quickly.  
   - **LSTM:** Remembers information for longer and avoids losing context.

4. **Trains and evaluates all three models**  
   - Accuracy is compared on the test set.  
   - Training time is measured for each model.

5. **Prints a clear comparison**  
   - Which model is most accurate  
   - Which model is fastest  
   - Why their performance differs

---

## 📊 Key Insights (Easy to Understand)

- **LSTM usually performs best**  
  Because it can remember long-term information in the review.

- **CNN usually trains the fastest**  
  Because it processes many words in parallel instead of one at a time.

- **Simple RNN is the simplest**  
  But it often forgets information from earlier words in long reviews.

---

## 📁 File Included

- `sentiment_rnn_cnn_lstm_imdb.ipynb`  
  A beginner-friendly notebook with clear comments and simple code.

---

## 🚀 How to Run

1. Download the notebook  
2. Open it in Jupyter Notebook or Google Colab  
3. Run all cells in order  
4. Check the results and update the conclusion section

---

## ✔ Why This Project is Useful

- Shows how different neural networks behave on the same dataset  
- Helps beginners understand RNNs, CNNs, and LSTMs  
- Provides a clean and simple code structure that is easy to learn from  

---

