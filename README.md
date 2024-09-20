

---

#  Multi-Lingual Text Detection System

## **Overview**
This project aims to develop a multi-lingual text detection system that enhances the ability to process and search sentences containing both Hindi and English words.Suppose if a sentence has both English and Hindi words, it is very difficult to covert this sentence in a single lamguage sentence. The system utilizes machine learning models to accurately detect the language of individual words in mixed-language text.

## **Features**
- **Mixed-Language Support:** Detects and processes sentences containing words from multiple languages.
- **Machine Learning Models:** Utilizes Multinomial Naive Bayes and Support Vector Machine (SVM) for robust text classification.
- **Efficient Preprocessing:** Implements `CountVectorizer` for text vectorization and removes stopwords, symbols, and punctuations.

## **Tech Stack**
- **Programming Language:** Python
- **Libraries:**
  - **Scikit-learn:** For implementing machine learning models (Multinomial Naive Bayes and SVM).
  - **Pandas & NumPy:** For data manipulation and numerical computations.
  - **Jupyter Notebook:** For development, testing, and visualization.


## **Usage**
1. **Preprocess the Data:**
   - Use `CountVectorizer` to convert text data into a numerical matrix.
   - Remove stopwords, symbols, and punctuations to clean the data.

2. **Train the Models:**
   - Train the **Multinomial Naive Bayes** model for word count-based classification.
   - Train the **SVM (SVC)** model for precise classification in higher-dimensional spaces.

3. **Evaluate and Test:**
   - Evaluate the models on mixed-language datasets.
   - Test the system on real-world sentences to ensure accurate detection of languages in mixed-language text.

