# Sentiment analysis from reviews

## Description

**Sentiment analysis from reviews** is a Python-based tool designed to perform sentiment analysis on Amazon product reviews. It leverages the `spaCy` NLP library and the `spaCyTextBlob` extension to automatically classify customer feedback into positive, negative, or neutral categories. This tool is essential for businesses looking to gain insights into consumer sentiment at scale, enabling data-driven decisions to enhance product offerings and customer satisfaction.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)

## Installation

To install **Sentiment analysis from reviews** locally, follow these steps:

1. Ensure you have Python 3.6 or higher installed on your system.
2. Clone the repository to your local machine:
git clone https://github.com/dav-wu/finalCapstone.git
3. Navigate into the project directory:
cd \sentiment analysis from reviews\
4. Install the required dependencies:
pip install -r requirements.txt

## Usage

After installation, you can use **Sentiment analysis from reviews** to analyze sentiment in Amazon product reviews as follows:

1. Load your dataset. Ensure it's in CSV format with at least one column containing review texts.
2. Run the sentiment analysis script:
python sentiment_analysis.py
3. To preprocess text and analyze sentiment for specific reviews, use the `preprocess_text` and `analyze_sentiment` functions respectively.

## Credits

This project was developed by <Davide>.

- [Davide](https://github.com/<dav-wu>)

For questions or contributions, please contact me through GitHub or submit a pull request.
