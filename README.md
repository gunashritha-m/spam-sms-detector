# spam-sms-detector

git clone https://github.com/gunashritha-m/spam-sms-detector/tree/main
cd spam-sms-detector


python -m venv venv
source venv/bin/activate  # for Windows: venv\Scripts\activate



# Run the Jupyter Notebook
jupyter notebook


Tech Stack:

Python, scikit-learn, pandas, matplotlib, seaborn, nltk

How It Works:

Preprocess the data (cleaning, tokenization)

Convert text to numeric form using TF-IDF

Train & compare models (MultinomialNB, Logistic Regression, SVM)

Evaluate performance using accuracy, F1 score, and confusion matrix

Result:

Best-performing model achieved ~97% accuracy on the test set.
