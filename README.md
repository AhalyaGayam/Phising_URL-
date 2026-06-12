# Phishing Website Detection System

## Overview

The Phishing Website Detection System is a Machine Learning-based web application that identifies whether a website URL is safe, suspicious, or phishing. The system uses URL feature extraction, an XGBoost classification model, rule-based analysis, and VirusTotal verification to improve detection accuracy.

## Features

- Detects phishing websites from URLs
- Machine Learning prediction using XGBoost
- URL feature extraction
- Rule-based phishing detection
- VirusTotal integration for reputation checking
- Confidence score display
- User-friendly web interface using Flask

## Technologies Used

- Python
- Flask
- XGBoost
- Pandas
- Scikit-learn
- HTML
- CSS

## Project Structure

```text
updated_phishing_project/
│
├── app.py
├── feature_extraction.py
├── train_model.py
├── XGBoost.pkl
├── merged_phishing_dataset.csv
├── requirements.txt
│
├── templates/
│   └── index.html
│
├── static/
│   └── style.css
│
└── __pycache__/
```

## Working Process

1. User enters a website URL.
2. The system performs rule-based checks.
3. URL features are extracted.
4. The trained XGBoost model predicts whether the URL is safe or phishing.
5. VirusTotal reputation data is checked.
6. Final result is displayed as:
   - SAFE ✅
   - SUSPICIOUS ⚠️
   - PHISHING 🚫

## Installation

### Clone Repository

```bash
git clone https://github.com/your-username/phishing-website-detection.git
cd phishing-website-detection
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
python app.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000
```

## Model Training

To retrain the model using the dataset:

```bash
python train_model.py
```

The trained model will be saved as:

```text
XGBoost.pkl
```

## Dataset

The project uses a phishing website dataset containing various URL-based features and class labels used to train the machine learning model.

## Screenshots

Add screenshots here:

- Home Page
- URL Prediction Page
- Safe Website Result
- Phishing Website Result

## Future Enhancements

- Real-time browser extension
- Deep Learning-based detection
- Email phishing detection
- Domain reputation analysis
- Dashboard with analytics

## Applications

- Cybersecurity Awareness
- Website Security Verification
- Educational Projects
- Research in Phishing Detection

## Author

Ahalya

## License

This project is developed for educational and research purposes.
