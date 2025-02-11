
# 📧 Message Classification & User Experience Enhancement

This repository showcases a Python-based project that uses **synthetic data** 📊 to classify and simulate actions for various types of messages. It's designed to enhance user interactions by automating responses based on message types. 🚀

---

## 💡 Overview

### What This Project Does:
- Uses **synthetically generated messages** across categories for classification and testing.
- Simulates **user-specific actions** to improve the user experience.

### Message Categories:
1. **Spam**: 🚫 Promotional or scam messages.
2. **OTP**: 🔑 One-Time Passwords for verification.
3. **Transactional**: 💳 Utility bills, payments, and reminders.
4. **Logistic**: 📦 Shipment and delivery updates.
5. **Fraud**: ⚠️ Alerts for suspicious activities.

---

## 📂 Features
- **Synthetic Dataset**: Messages are programmatically generated for realistic yet customizable testing.
- **Classification Model**: Employs a **Random Forest Classifier** trained on TF-IDF features.
- **Automated Simulations**:
  - Auto-deletion of expired OTPs.
  - Payment reminders for transactional messages.
  - Fraud alerts and tracking buttons.
- **Performance Metrics**: Generates reports and bar charts showing precision, recall, and F1-score for each category.

---

## 🔧 Tech Stack
- **Programming Language**: Python 🐍
- **Key Libraries**:
  - `pandas` 📑
  - `scikit-learn` 📈
  - `matplotlib` 🎨
  - `numpy` 🔢

---

## 🚀 Getting Started

### Prerequisites:
1. **Clone the repository**:
   ```bash
   git clone https://github.com/nikhil07897/message-classification.git
   cd message-classification
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

### Run the Script:
```bash
python message_classification_and_user_experience_enhancement_task.py
```

---

## 📊 Data and Results

### Data Generation:
- Synthetic data is created for five categories of messages.
- Messages are randomly selected from pre-defined templates for testing.

### Results:
The model performs well in classifying messages and highlights the following metrics:
- **Precision**: Accuracy of positive predictions.
- **Recall**: How well the model captures actual positives.
- **F1-Score**: Balance between precision and recall.

Here's a sample bar chart visualizing the performance:

![Performance Chart](performance_chart.png)

---

## 🤔 How It Works

### Core Steps:
1. **Synthetic Data Creation**:
   - Generates 1,000 sample messages across five categories.
   - Ensures diverse testing scenarios.

2. **Text Vectorization**:
   - Uses **TF-IDF Vectorizer** for n-gram analysis and stop-word filtering.

3. **Classification**:
   - A **Random Forest Classifier** is trained on the synthetic dataset to classify messages.

4. **Simulated Actions**:
   - Identifies actionable keywords (e.g., OTP, Fraud, Track).
   - Automates relevant actions, such as:
     - Displaying "Pay Now" for bills.
     - Auto-deleting expired OTPs.
     - Warning for fraud detection.

---

## 🌟 Future Enhancements
- Extend the synthetic data to include multilingual messages. 🌐
- Integrate with real-world datasets for further testing and validation. 📡
- Deploy a **real-time API** for live message classification. 🔄
- Experiment with deep learning models like **Transformers** for improved performance. 🧠

---

## 🤝 Contributing
Contributions are welcome! Please create a pull request or open an issue for any feature requests or bug fixes.

---

## 📜 License
This project is licensed under the MIT License. Feel free to use and modify the code.

---

### ✨ Created by [Nikhil](https://github.com/nikhil07897)
```

This README highlights the **synthetic data** aspect and outlines the project in an engaging and professional manner. Let me know if you'd like any additional tweaks! 😊
