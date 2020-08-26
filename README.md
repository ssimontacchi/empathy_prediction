### Models to Detect Empathy and Sentiment with Bert, Distilbert, and traditional NLP techniques


# Empathy Prediction
#### Most important priority: Predict polarity (positive, neutral, or negative empathy sentiment). 
To accomplish this, I trained many sentiment analysis models in increasing complexity.

#### Secondary goal: Predict empathy from a sentence (happy, tired, angry, etc.). 
As there are 62 possible labels, this is a more challenging task that will be dealth with in a secondary model. If this model performed very well, though it could be used as the only model, but otherwise both would be necessary.

What I did:

- Pull data
- Minor data cleaning
- Checked for class balances
- Visualize and Inspect Data by label with pre-trained sentence vectors
- Message length and label
- Baseline model with TF-IDF and Naive-Bayes
- Second model was pre-trained sentence embeddings through ~15 classifiers
- Third model was fine-tuning BERT to predict positive, neutral, negative
- Fourth model was fine-tuning BERT to predict empathy labels
- Analyzed residuals
