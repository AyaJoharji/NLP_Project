# NLP_Project
# Sentiment Analysis on Arabic Text from Twitter

Sentiment analysis on Arabic text from Twitter presents a challenging task due to the unique linguistic characteristics and diverse expressions found in social media content. In this project, we address this task by employing a comprehensive approach that combines natural language processing techniques, feature extraction methods, and machine learning models.

## Approach

1. **Preprocessing:**
   - **Emoji and Special Character Removal:** Clean the text data by removing unnecessary emojis and special characters.
   - **Lowercase Conversion:** Standardize text to lowercase for uniformity.
   - **Stopword Elimination:** Remove common words that do not contribute to sentiment analysis.
   - **Stemming and Lemmatization:** Reduce words to their root forms to ensure consistent analysis.

2. **Feature Extraction:**
   - **TF-IDF:** Capture term importance in the text.
   - **Word2vec Embeddings:** Capture semantic relationships between words.

3. **Model Training:**
   - **Logistic Regression:** A baseline model providing simplicity and interpretability.
   - **Deep Neural Network (DNN):** An advanced model for improved accuracy in capturing sentiment nuances.

## Results

Our experiments were conducted on a Twitter dataset comprising Arabic text:

- **Logistic Regression:**
  - Accuracy: 75.97%

- **Deep Neural Network (DNN):**
  - Accuracy: 91.04%
  - Test Loss: 0.22695

The results support the hypothesis that more complex models, such as DNNs, significantly outperform simpler models like logistic regression. However, logistic regression serves as a useful baseline, offering insights into model performance with simpler techniques.

## Conclusion

The findings underscore the importance of leveraging advanced deep learning techniques, particularly in scenarios with complex data and high-dimensional feature spaces. This research contributes to a deeper understanding of sentiment analysis in Arabic text from Twitter and highlights the effectiveness of advanced machine learning models in capturing sentiment nuances in social media content.
