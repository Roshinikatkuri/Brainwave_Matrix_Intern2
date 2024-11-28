# Brainwave_Matrix_Intern2
This is my task 2 - Sentiment Analysis using NLP

*Sentiment Analysis Project: Unveiling Insights from Twitter Data with BERT and NLP*
  
🔍 *Why BERT?*  
BERT (Bidirectional Encoder Representations from Transformers) was chosen for its ability to understand context in text better than traditional models. Its bidirectional nature allows it to grasp nuanced meanings, making it ideal for analyzing short, context-rich Twitter data.  

📂 *Steps in the Project*:  
1️⃣ *Preprocessing the Data*:  
   - Cleaned and processed the Twitter dataset (smileannotationsfinal.csv) with techniques like tokenization, stemming, lemmatization, and POS tagging using Python (nltk and spaCy).  

2️⃣ *Data Exploration and Labeling*:  
   - Visualized sentiment category distributions and encoded labels for classification.  

3️⃣ *Model Setup*:  
   - Used the *BERT tokenizer* and fine-tuned a *pre-trained BERT model* to classify sentiments effectively.  

4️⃣ *Performance Optimization*:  
   - Integrated an optimizer and learning rate scheduler to enhance training.  
   - Evaluated performance using key metrics: *F1 Score* and *Accuracy*.  

📈 *Results*:  
The model's performance improved over 5 epochs, showcasing its learning ability:  
- *Training Loss* decreased from 1.18 to 0.45.  
- *Validation Loss* remained stable, ensuring minimal overfitting.  
- *Weighted F1 Score* improved consistently, reaching *0.79+*.  

Class-wise accuracies reflected strengths in identifying dominant categories, with notable accuracies:  
- Class 0: 91%  
- Class 1: 89%  

🎯 *Conclusion*:  
This project reinforced my understanding of modern NLP techniques and the capabilities of *BERT* in sentiment analysis. With a final *Weighted F1 Score of 79.4%*, it highlights the potential of pre-trained transformers for solving real-world challenges.  
