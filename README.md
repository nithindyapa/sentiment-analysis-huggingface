# Sentiment Analysis using Hugging Face Transformers

## Project Overview
This project performs sentiment analysis on text using a pretrained Transformer model from Hugging Face. It classifies input text as positive or negative and provides a confidence score for the prediction.

## Technologies Used
- Python
- Hugging Face Transformers
- PyTorch
- Google Colab

## Features
- Sentiment classification of individual text inputs
- Positive and negative sentiment prediction
- Confidence score for each prediction
- Testing on multiple text samples

## How It Works
1. Load the pretrained sentiment analysis pipeline.
2. Provide input text.
3. Pass the text to the model.
4. Retrieve the predicted sentiment and confidence score.
5. Display the results.

## Example
**Input:**
"I love learning Artificial Intelligence!"

**Output:**
- Sentiment: POSITIVE
- Confidence: Model-generated confidence score

## How to Run
1. Open `sentiment_analysis.ipynb` in Google Colab.
2. Run the installation cell.
3. Execute the remaining cells.
4. Modify the input text to test different sentences.

## Repository Structure
```text
sentiment-analysis-huggingface/
│
├── sentiment_analysis.ipynb
└── README.md
```

## Learning Outcome
Learned how to use Hugging Face Transformers pipelines for a practical Natural Language Processing (NLP) application.
