# 🎬 Sentiment Analysis of Movie Reviews

This project implements **Sentiment Analysis** on movie reviews using **LSTM (Long Short-Term Memory) Networks**.  
The goal is to classify reviews as **positive** or **negative** based on their textual content.  

---

## 📌 Features
- Preprocessing of raw text (tokenization, stopword removal, padding).
- Embedding Layer for word representation.
- LSTM model to capture sequential context in reviews.
- Evaluation using accuracy, confusion matrix, and classification report.
- Visualizations of training accuracy/loss.

---

## 📂 Project Structure
```

├── README.md                         # Project documentation
├── sentiment.ipynb                   # Jupyter Notebook with code
├── SNAPSHOTS.pdf                     # Output snapshots & graphs
├── Sentiment\_Analysis\_LSTM\_Movie\_Reviews.pptx   # Project presentation

````

---

## ⚙️ Tech Stack
- **Python**
- **TensorFlow / Keras**
- **Scikit-learn**
- **NLTK**
- **Pandas / NumPy**
- **Matplotlib / Seaborn**

---

## 🚀 Installation
Clone the repository:
```bash
git clone https://github.com/anchalV194/Sentiment-Analysis-of-Movie-reviews.git
cd Sentiment-Analysis-of-Movie-reviews
````

Install the required dependencies:

```bash
pip install -r requirements.txt
```

*(If requirements.txt is not present, install libraries manually: `tensorflow, scikit-learn, nltk, pandas, numpy, matplotlib`)*

---

## 🧩 Usage

Run the Jupyter Notebook:

```bash
jupyter notebook sentiment.ipynb
```

Steps inside notebook:

1. Load dataset
2. Preprocess text (cleaning + tokenization)
3. Train LSTM model
4. Evaluate performance
5. Visualize results

---

## 📊 Results

* Achieved **high accuracy** on test set.
* LSTM performed well in capturing context of reviews.
* Example:

  * Review: *"The movie was amazing, I loved the performances!"* → **Positive**
  * Review: *"The plot was dull and predictable."* → **Negative**

---

## 📸 Snapshots

Check [`SNAPSHOTS.pdf`](SNAPSHOTS.pdf) for:

* Model training graphs
* Confusion Matrix
* Sample predictions

---

## 🎤 Presentation

A detailed walkthrough of the project can be found in
[`Sentiment_Analysis_LSTM_Movie_Reviews.pptx`](Sentiment_Analysis_LSTM_Movie_Reviews.pptx)

---

## 👩‍💻 Author

**Anchal Verma**
🔗 [GitHub Profile](https://github.com/anchalV194)

---

## ⭐ Contribute

If you'd like to enhance this project:

1. Fork it
2. Create a feature branch
3. Submit a pull request

---
 
Do you want me to also generate a **requirements.txt** file for the dependencies used in your notebook so others can directly run it?
```
