# Intrusion Detection System (IDS) Project

This project implements an Intrusion Detection System (IDS) aimed at identifying malicious activity within network traffic. The system utilizes machine learning techniques to classify network traffic and detect potential intrusions or attacks. The project includes various preprocessing steps, feature selection methods, and machine learning models to ensure accurate and efficient detection.

## Features
- **Data Preprocessing:** Utilizes One-Hot Encoding for categorical data, followed by normalization to ensure balanced feature contribution.
- **Feature Selection:** Employs Univariate Feature Selection (ANOVA F-test) and Recursive Feature Elimination (RFE) to identify the most relevant features for accurate intrusion detection.
- **Machine Learning Models:** Decision Tree model is used to classify network traffic and identify anomalies or attacks.
- **Performance Metrics:** The system evaluates model performance using metrics such as accuracy, recall, F-measure, and confusion matrix. A 10-fold cross-validation is applied for robust validation.
- **Attack Categories:** Detection of various attack types such as DoS (Denial of Service), Probe, R2L (Remote to Local), and U2R (User to Root).

## Installation
To install and run the project locally, clone the repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/IDS-project.git
cd IDS-project
pip install -r requirements.txt
```
## Usage

## Usage
To train the model and evaluate its performance:

```bash
python train_and_evaluate.py
```
## Data
The dataset used in this project is derived from network traffic data, containing multiple attack categories and normal traffic samples. The dataset is preprocessed to handle categorical features, and feature selection techniques are applied to enhance the model's detection capabilities.

## Contributing
Feel free to fork the repository and contribute by adding new features, improving the model, or fixing bugs. Please submit issues or pull requests if you have suggestions or enhancements.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
