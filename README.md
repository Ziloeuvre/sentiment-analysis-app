# Sentiment Analysis App

This is a Streamlit web application for sentiment analysis using a pretrained DistilBERT model.

## Overview

The Sentiment Analysis App allows users to input text and analyzes its sentiment using a pretrained DistilBERT model. It provides a prediction of whether the sentiment is positive or negative, along with a confidence score.

## Usage

To use the app, follow these steps:

1. Clone this repository to your local machine.
2. Install the required dependencies using pip:
    ```
    pip install -r requirements.txt
    ```
3. Run the Streamlit app:
    ```
    streamlit run sentiment_analysis_app.py
    ```
4. Enter text in the provided text area.
5. Click the "Analyze" button to perform sentiment analysis.
6. View the sentiment prediction and confidence score.

## Dependencies

- `transformers`: For accessing pretrained DistilBERT model.
- `streamlit`: For building the web application interface.

## About the Pretrained Model

The pretrained DistilBERT model used in this app is `distilbert-base-uncased-finetuned-sst-2-english`. It has been fine-tuned on the SST-2 (Stanford Sentiment Treebank) dataset for sentiment analysis tasks.

## Credits

- **Streamlit**: The web application framework used for building the user interface.
- **Hugging Face Transformers**: For providing access to pretrained transformer models.

## License

This project is licensed under the [MIT License](LICENSE).
