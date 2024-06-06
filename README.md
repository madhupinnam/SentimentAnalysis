# Sentiment Analysis of Tweets

## Description
This project performs sentiment analysis on a dataset of tweets using the VADER SentimentIntensityAnalyzer. The analysis determines the overall sentiment (Positive, Negative, or Neutral) of the tweets and visualizes the sentiment distribution.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Acknowledgements](#acknowledgements)

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your_username/your_project.git
   cd your_project
   ```

2. Create a virtual environment (optional but recommended):
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage

1. Prepare your dataset in CSV format. Ensure the tweet text is in a column with "text" in its name.

2. Run the script:
   ```sh
   python sentiment_analysis.py
   ```

3. Follow the prompts to enter the path to your CSV dataset and the number of tweets you want to analyze.

## Features

- **Sentiment Analysis**: Analyze the sentiment of tweets and classify them as Positive, Negative, or Neutral.
- **Multiprocessing**: Utilize multiprocessing to speed up the sentiment analysis of large datasets.
- **Visualization**: Visualize the sentiment distribution of the analyzed tweets using a pie chart.

## Contributing

Contributions are welcome! Please read the [CONTRIBUTING.md](CONTRIBUTING.md) file for guidelines on how to contribute to this project.

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Madhu Pinnam - [pinnammadhu02@example.com](mailto:pinnammadhu02@example.com)

## Acknowledgements

- [VADER Sentiment Analysis](https://github.com/cjhutto/vaderSentiment)
- [pandas](https://pandas.pydata.org/)
- [matplotlib](https://matplotlib.org/)

## Example Output

![Sentiment Distribution](example_pie_chart.png)
```

### Additional Files

- **requirements.txt**: List of dependencies to install.
- **CONTRIBUTING.md**: Guidelines for contributing to the project.
- **LICENSE**: License file for the project.

### Example Requirements File

Create a `requirements.txt` file with the following content:

```txt
pandas
matplotlib
vaderSentiment
```

### Example Contributing File

Create a `CONTRIBUTING.md` file with guidelines for contributing:

```markdown
# Contributing to Sentiment Analysis of Tweets

Thank you for considering contributing to this project! Here are some guidelines to get started:

## How to Contribute

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Make your changes.
4. Submit a pull request with a detailed description of your changes.

## Code of Conduct

Please adhere to the [Contributor Covenant Code of Conduct](https://www.contributor-covenant.org/version/2/0/code_of_conduct/).
```

### Example License File

Create a `LICENSE` file with the MIT License:

```markdown
MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

...

```

Tailor the details to your specific project and include any additional sections or files as necessary.
