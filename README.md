# Phishing URL Detector

This project is a simple phishing URL detector built with Python. It uses machine learning (Random Forest classifier) to classify URLs as phishing or legitimate based on extracted URL features.

## Features Extracted

- URL length
- Number of dots ('.')
- Number of hyphens ('-')
- Number of '@' symbols
- Number of question marks ('?')
- Number of equal signs ('=')
- Whether the URL uses HTTPS
- Whether the domain is an IP address

## How to Use

1. Prepare two CSV files: one with phishing URLs and one with legitimate URLs. Each file should have a column named `url`.
2. Place the CSV files in the same directory as `main.py`.
3. Update the file names in `main.py` if necessary.
4. Install dependencies:

```bash
pip install -r requirements.txt
