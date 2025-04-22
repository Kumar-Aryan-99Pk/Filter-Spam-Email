# Filter-Spam-Email
# 📧 Spam Email Detection Using Structured Metadata

This project uses machine learning to classify emails as **spam** or **not spam** based solely on structured metadata — without analyzing the full content of the emails. It offers a lightweight, privacy-respecting alternative to traditional NLP-based spam filters.

---

## 🚀 Features

- Classifies emails using features like:
  - Number of links
  - Number of attachments
  - Sender reputation score
- Trained using a Random Forest Classifier
- Evaluated with:
  - Accuracy, Precision, Recall
  - Confusion matrix with heatmap
- Easy-to-understand, customizable Python code

---

## 🧠 Dataset

The dataset should be a CSV file with the following columns:

| Feature            | Description                              |
|--------------------|------------------------------------------|
| `num_links`        | Number of hyperlinks in the email        |
| `num_attachments`  | Number of attached files                 |
| `sender_reputation`| A float score between 0 (bad) and 1 (good) |
| `is_spam`          | Email label: `yes` or `no`               |

Make sure to save your dataset as `spam_metadata.csv` or update the script with your file path.

---

## 📦 Installation

Clone the repo and install the required Python packages:

```bash
git clone https://github.com/yourusername/spam-metadata-detector.git
cd spam-metadata-detector
pip install -r requirements.txt
