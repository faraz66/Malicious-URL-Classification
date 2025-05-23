Malicious URL Detection - For Newly Generated Domains

Overview

This project implements detection of malicious URLs, focusing on newly generated domains. It covers dataset exploration, feature engineering, outlier detection, multiple machine learning models, severity scoring (both ML-based and rule-based), integration with Google Safe Browsing, and visualization of results.

Features
	•	Load and preprocess URL dataset
	•	Lexical, distributional, and advanced feature engineering (n-grams, typo-squatting, obfuscation metrics)
	•	Outlier detection using Z-score and Isolation Forest
	•	Machine learning classifiers: Logistic Regression, Random Forest, SVM
	•	Severity scoring with ML models and rule-based Google Safe Browsing checks
	•	Visualization of severity vs Google Safe Browsing score

Requirements
	•	Python 3.8+
	•	pandas
	•	numpy
	•	python-whois
	•	requests
	•	tldextract
	•	scikit-learn
	•	python-dateutil
	•	matplotlib (optional for additional plots)

Installation

git clone <repository_url>
cd <repo_folder>
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt

Usage

Open and run the Jupyter notebook:

jupyter notebook Malicious_URL_Detection_and_Classification.ipynb

Follow the notebook sections to execute data loading, preprocessing, feature engineering, model training, scoring, and visualization.

Notebook Structure
	1.	Overview & FAQ: Project introduction and common questions
	2.	Dataset Information: Description and source of the URL dataset
	3.	Feature Engineering: Domain extraction, lexical features, character distribution, entropy, third-party features, n-grams
	4.	Outlier Detection: Z-score and Isolation Forest methods
	5.	Machine Learning Models: Training and evaluation of Logistic Regression, Random Forest, and SVM classifiers
	6.	Severity Scoring: Assigning severity levels using ML predictions and rule-based Google Safe Browsing API checks
	7.	Visualization: Plotting severity scores against Google Safe Browsing results

Contributing

Contributions are welcome! Please open issues or submit pull requests.

License

Specify your license here (e.g., MIT License)

Contact

Maintainer: Faraz Shaikh
Email: farazshaikh66@gmail.com
