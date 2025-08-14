# Fake Profile Detector

Detecting fake social media profiles using *Machine Learning* on behavioral and profile features.

## Project Overview
With the exponential growth of social media, fake accounts are increasingly used for scams, spreading misinformation, and malicious activities.  
This project leverages *behavioral* and *profile-based features* to classify accounts as *real, **bot, **scam* or *spam* using supervised machine learning techniques.

Our goal is to create a reliable detection pipeline that can assist in:
•⁠  ⁠Flagging suspicious accounts
•⁠  ⁠Enhancing online safety
•⁠  ⁠Supporting moderation teams

---

## Features
•⁠  ⁠Preprocessing of profile and behavioral datasets
•⁠  ⁠Feature extraction from account metadata
•⁠  ⁠Model training using multiple ML algorithms
•⁠  ⁠Evaluation using precision, recall, F1-score, and accuracy
•⁠  ⁠Visualization of key insights

## Methodology
1.⁠ ⁠*Data Loading* – Load the dataset into Pandas (dataset not included in repository).
2.⁠ ⁠*Data Preprocessing* – Handle missing values, encode categorical variables, normalize numerical features.
3.⁠ ⁠*Feature Engineering* – Extract meaningful features such as:
   - Profile Picture
   - Engagement Score
   - Followers/Following ratio
   - Posting frequency
   - Bio completeness

4.⁠ ⁠*Model Training* – Test algorithms like:
   - K Nearest Neighbours (KNN)
   - Support Vector Machine (SVM)
5.⁠ ⁠*Evaluation* – Compare models using:
   - Accuracy
   - Precision
   - Recall
   - F1-score

## Example Results
| Model          | Accuracy   | Precision | Recall | F1-score |
|--------------- |------------|-----------|--------|----------|
| KNN            | 0.97       | 0.96      | 0.97   | 0.97     |
| SVM            | 0.84       | 0.87      | 0.84   |  0.83    |

(Results may vary depending on dataset and tuning.)

## Conclusion
This project shows how machine learning can effectively detect fake social media profiles using behavioral and profile-based features.
It provides a solid foundation for improving online safety, with potential to expand into deep learning, network analysis, and AI-generated content detection for even greater accuracy.

## 🛠 Installation & Usage

###  Clone the repository
```bash
git clone https://github.com/Vedansh-code/fake-profile-detector.git
cd fake-profile-detector

