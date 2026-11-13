# Overview
This project develops an AI-assisted forensic workflow for identifying potential IPv4 address evidence in simulated mobile-device configuration data.

It combines regex extraction, strict IPv4 validation, and machine-learning classification to distinguish genuine IP candidates from misleading strings such as software versions and malformed addresses.

**Technologies**
1. Python 3.10+
2. Pandas
3. Scikit-learn
4. Matplotlib
5. Jupyter Notebook

**Key Activities**
1. Evidence preservation using SHA-256 hashing.
2. Dataset inspection and preprocessing.
3. Regex-based IP candidate extraction.
4. IPv4 validation using Python ipaddress.
5. TF-IDF and Logistic Regression classification.
6. Rule-based baseline comparison.
7. Model evaluation using accuracy, precision, recall, F1-score, and confusion matrices.
8. Forensic analysis and intelligence reporting.

**Deliverables**
1. Evidence manifest.
2. Candidate review CSV.
3. Model predictions.
4. Reproducible Python scripts/notebooks.
5. Performance charts and confusion matrix.
6. Forensic report and executive briefing
