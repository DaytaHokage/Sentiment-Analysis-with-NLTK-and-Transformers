# Sentiment-Analysis-with-NLTK-and-Transformers

## Overview
This project explores sentiment analysis using a combination of natural language processing (NLP) techniques and advanced machine learning models. Starting with NLP basics, such as tokenization, POS tagging, and named entity recognition (NER) using NLTK, it progresses to building and evaluating sentiment analysis models using:

- **VADER Sentiment Scoring**: A rule-based sentiment analysis tool.
- **ROBERTA Pretrained Model**: A transformer-based model leveraging Hugging Face's library.
- **Custom Transformer**: Fine-tuning a transformer model from Hugging Face for sentiment analysis.

## Features
- **Exploratory Data Analysis (EDA)**: Insights into the dataset, including distributions and basic trends.
- **Sentiment Analysis Models**: Comparison between traditional (VADER) and transformer-based approaches (ROBERTA).
- **Visualization**: Graphical representation of sentiment distributions and model correlations.
- **Transfer Learning**: Utilizing pretrained transformer weights for efficient and accurate sentiment classification.

## Workflow
1. **Data Loading and Preprocessing**
   - Loaded the `Reviews.csv` dataset.
   - Preprocessed text data, including stopword removal and tokenization.

2. **EDA**
   - Visualized distributions of text length, sentiment scores, and other features.

3. **VADER Sentiment Analysis**
   - Applied the VADER model for quick sentiment scoring.
   - Highlighted its limitations in understanding word relationships.

4. **Transformer-Based Sentiment Analysis**
   - Utilized Hugging Face's ROBERTA model for sentiment analysis.
   - Compared its performance against VADER.
   - Fine-tuned the transformer model on the dataset.

5. **Visualization and Comparison**
   - Plotted correlations and distributions of sentiment scores across models.
   - Demonstrated the advantages of transformer-based approaches over rule-based methods.

## Installation and Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/DaytaHokage/sentiment-analysis-nlp.git
   cd sentiment-analysis-nlp
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Download necessary NLTK data:
   ```python
   import nltk
   nltk.download('punkt')
   nltk.download('vader_lexicon')
   nltk.download('words')
   nltk.download('averaged_perceptron_tagger')
   nltk.download('maxent_ne_chunker')
   ```

## Usage
Run the notebook to reproduce the analysis and visualizations. Key sections include:
- **EDA**: Gain insights into the dataset.
- **VADER Analysis**: Understand rule-based sentiment scoring.
- **ROBERTA Analysis**: Explore transformer-based sentiment classification.

## Results
- **VADER Model**: Effective for basic sentiment scoring but fails to capture nuanced word relationships.
- **ROBERTA Model**: Demonstrated superior performance by leveraging contextual understanding of text.
- **Visualizations**: Highlighted key differences and correlations between model outputs.

## Contributing
Contributions are welcome! If you have ideas for improvement or additional features, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
- **NLTK** for providing essential NLP tools.
- **Hugging Face** for the ROBERTA model and transformer utilities.
- Dataset sourced from `Reviews.csv`.

