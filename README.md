# Sentiment Analysis on Tweets

This project is inspired by the [Machine Learning project list](https://docs.google.com/document/d/1-CQHiW1V2yzZB0NS2lOPA8A7udNoUF8p884Q14J13q8/mobilebasic). The goal is to create a text classification model to determine if a tweet’s sentiment is positive or negative.

## Table of Contents
- [Previous Configurations](#previous-configurations)
- [Data Preprocessing](#data-preprocessing)
- [Feature Engineering](#feature-engineering)
- [Model](#model)
- [Contributing](#contributing)
- [License](#license)

## Previous Configurations

In order to run this script, you will need:

- The necessary libraries installed
- A `.env` file with the required environment variables
- Input files obtained from the original source: []()

### Installing the Libraries

The script works with the following versions:
- python `3.11.5`
- pandas `2.1.0`
- numpy `1.25.2`
- matplotlib `3.7.2`
- python-dotenv `1.0.0`
- scikit-learn `1.3.0`
- seaborn `0.12.2`
- scipy `1.11.2`

To install the necessary libraries, run:
```sh
pip install -r requirements.txt
```

### Environmental Variables

The `.env` file should include:
```sh

```

## Data Preprocessing

This line cleans the text in the data['text'] column by removing Twitter-style mentions (e.g., @user), hashtags (e.g., #topic), and URLs using a regular expression, and stores the cleaned version in a new column called cleaned_text.

## Feature Engineering


## Model


## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
