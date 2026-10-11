#SentimentScope: Movie Review Sentiment Analysis

#Project Overview

SentimentScope is a Natural Language Processing (NLP) project that uses a Transformer-based deep learning model to classify movie reviews as positive or negative.

The project uses the IMDb movie review dataset and the DistilBERT pretrained model to understand the sentiment expressed in text reviews.

#Objectives

- Analyze movie reviews using NLP techniques.
- Classify reviews into positive and negative sentiments.
- Fine-tune a pretrained Transformer model for sentiment classification.
- Evaluate model performance using test accuracy.

#Technologies Used

- Python
- Google Colab
- Hugging Face Transformers
- Hugging Face Datasets
- PyTorch
- IMDb Movie Review Dataset
- DistilBERT

#Dataset

The project uses the IMDb movie review dataset, which contains movie reviews labeled as positive or negative.

Dataset: "stanfordnlp/imdb"

#Project Workflow

1. Load the IMDb dataset.
2. Prepare training, validation, and test datasets.
3. Tokenize movie reviews using the DistilBERT tokenizer.
4. Create PyTorch datasets and DataLoaders.
5. Fine-tune the DistilBERT model for sentiment classification.
6. Evaluate the trained model using the test dataset.
7. Save the trained model for future inference.

#Results

- Test Accuracy: 86%
- Target Accuracy: 86%

The model achieved 86% test accuracy in the completed experiment.

#How to Run

1. Open the project notebook in Google Colab.
2. Install the required Python libraries.
3. Load the IMDb dataset.
4. Run the preprocessing and tokenization steps.
5. Train and evaluate the model.

#Project Structure

SentimentScope/
├── README.md
├── SentimentScope.ipynb
├── requirements.txt
└── model/
    ├── config.json
    ├── model.safetensors
    └── tokenizer files

Note: The model folder structure depends on the files included in your final submission.

#Future Enhancements

- Improve model accuracy through hyperparameter tuning.
- Build a simple web application for sentiment prediction.
- Test the model on user-provided movie reviews.
- Explore other Transformer models for comparison.
