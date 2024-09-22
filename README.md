# Sentiment_Analysis

# Sentiment Analysis

### Project Overview
This project focuses on sentiment analysis using the IMDB movie reviews dataset. It applies 2 ML models: **Decision Tree** and **Random Forest**, to classify reviews as either positive or negative. 

### Environment Setup
1. Clone the repository:
```bash
https://github.com/Michelia235/Sentiment_Analysis.git
cd Sentiment_Analysis
```
2. Download the dataset and place it in the root folder.

### Dataset
The dataset used is the IMDB movie reviews dataset, consisting of movie reviews labeled as either positive and negative. Each review is a unit of text with a corresponding sentiment label.

### Data Preprocessing
The raw text data undergoes extensive preprocessing to ensure high-quality input for the models:
- **HTML Tag Removal**: Cleans text from any HTML formatting
- **Contractions Expansion**: Expands shortened forms of words (e.g., "don't" to "do not")
- **Stopwords Removal**: Removes common stopwords (e.g., "and", "the") that add little meaning to sentiment analysis
- **Lemmatization**: Converts words to their base forms (e.g., "running" to "run")

### Modeling
The project implements 2 supervised ML models:
1. **Decision Tree**: A classification model based on the entropy criterion
2. **Random Forest**: An ensemble learning method using multiple decision trees to improve classification accuracy

### Text Vectorization
**TF-IDF** (Term Frequency - Inverse Document Frequency) is used to transform the cleaned text data into numerical vectors. This method assigns higher weight to words that are frequent in a review but rare across all reviews

### Results
The results show the following accuracy scores:
- **Decision Tree**: ```0.72%```
- **Random Forest**: ```0.84%```
The Random Forest classifier generally outperforms the Decision Tree in terms of accuracy, demonstrating the power of ensemble methods in text classification


# Additional Information

For any questions or issues, please open an issue in the repository or contact me at [truonghongkietcute@gmail.com](mailto:truonghongkietcute@gmail.com).

Feel free to customize the project names, descriptions, and any other details specific to your projects. If you encounter any problems or have suggestions for improvements, don't hesitate to reach out. Your feedback and contributions are welcome!

Let me know if there’s anything else you need or if you have any other questions. I’m here to help!
