# MOMO movie review sentiment analysis
> Python, NLP, Machine Learning
---

## Context
- **Dataset:** 14K+ user movie reviews collected from the MoMo platform.  
- **Objective:** Apply sentiment analysis to understand user satisfaction.

---

## Steps

### 1. Data Collection & Cleaning
- Collected 14K+ movie reviews from MoMo Cinema using Selenium
- Downsampled to 5,4K reviews to mitigate imbalance

### 2. Preprocessing
- Normalized Unicode, Repeated character, Whitespace, slang
- Removed Punctuation, Stopword, URLs and HTML entities
- Lowercasing
- Feature engineering: Created additional features to support modeling: cleaned_text, has_emoji, length.  

### 3. Sentiment Analysis
- Label reviews with rule-based and manual validation
- Exploratory data analysis
- Train and fine-tuning machine learning models  

---

## Results / Outputs

### Model evaluation
![Demo](https://github.com/user-attachments/assets/2a0a49d6-275e-4a7a-bb28-3fcc893c250f)

---

### Demo: Input
![Demo](https://github.com/user-attachments/assets/f58ba1c7-0d88-4dd9-aa1f-726b0c647231)

---
### Demo: Ouput
![Demo](https://github.com/user-attachments/assets/60d1c10e-b5f1-45e8-ac3c-2fe7a0a834cb)
