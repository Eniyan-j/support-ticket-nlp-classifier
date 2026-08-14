Markdown

 Support Ticket NLP Classifier

An NLP-based machine learning project that automatically classifies customer support tickets into four categories: **Billing and Payments, Human Resources, Technical Support, and General Inquiry**.

The project uses **TF-IDF** for text feature extraction and **Logistic Regression** for multi-class classification.

📌 Project Overview

Customer support teams receive a large number of tickets every day. Manually routing these tickets to the correct department can be time-consuming.

This project aims to automatically identify the appropriate department based on the content of a support ticket.

### Supported Categories

- Billing and Payments
- Human Resources
- Technical Support
- General Inquiry

🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Regular Expressions (`re`)
- Jupyter Notebook
- TF-IDF
- Logistic Regression
- Matplotlib

📂 Dataset

The dataset used for this project was obtained from Kaggle.

The original dataset contains multiple support-ticket categories. For this project, four categories were selected:

| Category | Samples |
|---|---:|
| Technical Support | 5,824 |
| Billing and Payments | 2,086 |
| Human Resources | 338 |
| General Inquiry | 263 |

The dataset is not included in this repository. Please download the dataset separately from Kaggle.

🔄 Project Workflow

Dataset
   ↓
Data Exploration
   ↓
Select Four Classes
   ↓
Handle Missing Values
   ↓
Combine Subject + Body
   ↓
Convert Text to Lowercase
   ↓
Remove Punctuation
   ↓
Remove Extra Whitespace
   ↓
Train/Test Split
   ↓
TF-IDF Vectorization
   ↓
Class Weight Balancing
   ↓
Logistic Regression
   ↓
Prediction
   ↓
Model Evaluation
