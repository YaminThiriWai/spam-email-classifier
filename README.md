
# Email Spam Classification using Support Vector Machines

This Python script demonstrates a simple email spam classification using a Support Vector Machine (SVM) model. The model is trained on a dataset of emails labeled as spam or not spam.

## Requirements

- Python 3.x
- pandas
- scikit-learn

## Getting Started

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/YaminThiriWai/spam-email-classifier

2. Install the required Python libraries:

   ```bash
   pip install -r requirements.txt
   ```

   Make sure you have [pip](https://pip.pypa.io/en/stable/installation/) installed.

3. Download the spam dataset (`spam.csv`) and place it in the project directory.

4. Run the script:

   ```bash
   python spam_classifier.py
   ```

   This script reads the spam dataset, performs train-test split, vectorizes the email text using CountVectorizer, trains an SVM model, and evaluates its accuracy.

## Usage

1. Modify the `spam.csv` dataset or provide your own dataset for training and testing.

2. Customize the `new_email_text` variable with your own email text to predict whether it is spam or not.

## Results

After running the script, you will see the model's accuracy on the test set and the predicted label for the new email text.

## Notes

- Ensure that the required Python libraries are installed before running the script.

- If you encounter any issues or have questions, feel free to open an issue on GitHub.
