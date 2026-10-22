# Credit Card Fraud Detection

A machine-learning project that detects fraudulent credit-card transactions using a **Random Forest classifier**, built in a Jupyter Notebook with scikit-learn.

## What this project does

- Explores a highly imbalanced transactions dataset with Pandas, NumPy, Seaborn and Matplotlib
- Splits the data into training and test sets and trains a Random Forest classifier to flag fraudulent transactions
- Evaluates the model properly for imbalanced data — not just accuracy, but **precision, recall, F1 score, Matthews correlation coefficient and a confusion matrix** with a full classification report

On fraud data, accuracy alone is misleading (predicting "not fraud" for everything scores ~99%), which is why this project reports the full set of metrics above.

## Dataset

Credit-card transactions dataset: https://drive.google.com/file/d/1AG6OAAofWribN62XgOVZ4BaQHJHr375i/view?usp=sharing

## Tech stack

Python · Pandas · NumPy · Scikit-learn (Random Forest) · Seaborn · Matplotlib · Jupyter Notebook

## How to run

1. Clone this repository
2. Install the tools above (`pip install pandas numpy scikit-learn seaborn matplotlib jupyter`)
3. Download the dataset from the link above
4. Open `Credit_Card_Fraud_Detection.ipynb` and run the cells top to bottom

## Author

**Vivek Saini** — Data Analyst
- LinkedIn: https://www.linkedin.com/in/vivek-saini-815b321b0/
- GitHub: https://github.com/Viveksaini108
- Email: vivek.saini.analyst@gmail.com
