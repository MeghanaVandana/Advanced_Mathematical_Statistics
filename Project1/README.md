This project applies K-Nearest Neighbors (KNN) to predict fatalities in U.S. violent demonstrations using ACLED data (2020–2024).
Training data includes events from 2020–2022, and testing is performed on 2023 demonstrations.
Features used are event date (numeric), latitude, and longitude.
Models are evaluated for odd k values (1–25) using accuracy, precision, recall, and F1-score.
The script loads data directly from the GitHub RAW link and outputs performance metrics and plots.
