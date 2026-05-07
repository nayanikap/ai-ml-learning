# Sentiment Analysis using VADER and Pre-trained NLP Models

This notebook demonstrates a sentiment analysis workflow using Natural Language Processing (NLP) techniques in Python.

The project explores sentiment detection using:

* VADER sentiment analysis
* Visualization of sentiment scores
* Pre-trained transformer-based sentiment models

---

# 📌 Objective

The goal of this project is to analyze textual data and determine sentiment polarity such as:

* Positive 🙂
* Negative 🙁
* Neutral 😐

This project is part of my AI/ML learning journey toward transitioning into AI Engineering.

---

# 🧠 Key Learning Areas

Through this notebook, I explored:

* Basic NLP preprocessing
* Sentiment analysis using VADER
* Visualization of sentiment scores
* Using pre-trained NLP models
* Comparing rule-based and model-based sentiment analysis approaches

---

# ⚙️ Workflow Implemented

## 1. Importing Libraries

Libraries used include:

* `pandas`
* `numpy`
* `matplotlib`
* `seaborn`
* `nltk`
* `transformers`

---

## 2. Text Preprocessing

The preprocessing performed in this project was intentionally minimal.

### ✔ Lowercasing

Text was converted to lowercase for consistency.

### ✔ Stopword Removal Not Applied

Stopwords were intentionally retained.

Reason:
In sentiment analysis, words such as:

* "not"
* "no"
* "never"

carry important contextual meaning.

Removing them can alter the actual sentiment of the sentence.

Example:

Input:

```id="inputsent1"
"I do not like this product"
```

If stopwords are removed:

```id="outputsent1"
["like", "product"]
```

This changes the sentiment interpretation incorrectly.

---

## 3. Sentiment Analysis using VADER

The notebook uses the VADER (Valence Aware Dictionary and Sentiment Reasoner) package from NLTK.

VADER is a rule-based sentiment analysis tool optimized for:

* Social media text
* Short reviews
* Informal language

The sentiment polarity scores generated include:

* Positive
* Negative
* Neutral
* Compound score

---

## 4. Visualization of Results

The sentiment scores were visualized using plots and graphs to better understand sentiment distribution and polarity trends.

Visualization helps in:

* Understanding dataset sentiment balance
* Comparing sentiment categories
* Interpreting model outputs

---

## 5. Pre-trained Sentiment Analysis Model

The notebook also explores sentiment prediction using a pre-trained transformer-based NLP model.

This demonstrates how modern NLP models can perform contextual sentiment understanding beyond rule-based approaches.

---

# 📊 Comparison of Approaches

| Approach                      | Type                                   |
| ----------------------------- | -------------------------------------- |
| VADER                         | Rule-based sentiment analysis          |
| Pre-trained Transformer Model | Deep learning based sentiment analysis |

---

# 🧪 Example

## Input

```id="inputsent2"
"I absolutely loved the experience and the support was amazing."
```

## Predicted Sentiment

```id="outputsent2"
Positive
```

---

# 🚀 Key Learnings

This project helped me understand:

* Why preprocessing decisions depend on use case
* How VADER performs sentiment analysis
* Difference between rule-based and transformer-based sentiment analysis
* Importance of preserving contextual meaning in NLP
* Basic NLP visualization workflows

---

# 🔥 Future Enhancements

Planned future improvements include:

* Training custom sentiment classification models
* Fine-tuning transformer models
* Real-world dataset evaluation
* Deployment using Flask/FastAPI
* Building sentiment analysis APIs

---

# 📂 Repository Structure

```id="reposent2"
NLP/
 └── sentiment-analysis/
      ├── sentiment-analysis.ipynb
      └── README.md
```

---

# 👩‍💻 Author

Part of my AI/ML deep learning journey focused on transitioning from Backend Engineering to AI Engineering.
