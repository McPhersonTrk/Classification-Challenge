# Classification-Challenge
DU AI & ML, Module 13 Challenge
# Spam Detection Model
### Overview
This project aims to classify email into spam and non-spam categories using a machine learning algorithms. It utilizes a dataset containing various email attributes and content features, such as word frequencies and punctuation marks. The models tested are Logistic Regression and  Random Forest classifier.

### Data Description
##### The dataset comprises email records with 58 features, including:
    - Word frequencies (e.g., word_freq_make, word_freq_address, word_freq_all).
    - Character frequencies (e.g., char_freq_;, char_freq_(, char_freq_[).
    - Capital letter run-length attributes (capital_run_length_average, capital_run_length_longest, capital_run_length_total.)

The target variable (spam) indicating whether the email is spam (1) or not (0).

### Preprocessing
StandardScaler  is used to standardize the feature scales before feeding them into the machine learning models.

### Models and Accuracy Results

##### Logistic Regression
    - Accuracy Score: 92.27%
    - Training Score: 92.58%
    - Testing Score: 92.27%
##### Random Forest

    - Training Score: 99.94%
    - Testing Score: 95.83%
    - Accuracy: 95.83%

The accuracy scores indicate the model's performance on the testing set.

###### NOTE: chatgpt wrote the data description.