# 🎬 Movie Review Sentiment Analysis with Gradio  

This project is a **Movie Review Sentiment Analysis Application** that predicts whether a given **movie review** is **positive** or **negative** using different ML models trained on the [IMDB Dataset of 50K Movie Reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews).  

## 🚀 Features  
✅ **Trained on a large IMDB dataset (50,000 reviews)**  
✅ **Uses multiple Machine Learning models (Naïve Bayes, Decision Tree, and Random Forest)**  
✅ **Employs Bag-of-Words (BoW) for text classification**  
✅ **Provides an interactive web interface using Gradio**  
✅ **Easily deployable in Google Colab with public sharing**  

---

## 📂 Dataset  
The model is trained on the **IMDB Dataset of 50K Movie Reviews**, which consists of:  
- **50,000** movie reviews  
- **Balanced distribution** (25,000 positive, 25,000 negative)  
- **Pre-labeled sentiment (0 = Negative, 1 = Positive)**  
- **Raw text-based dataset without additional metadata**  

📌 **Source:** [Kaggle - IMDB 50K Movie Reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)  

---

## 🛠️ Installation & Setup  

### **1️⃣ Install Dependencies**  
Run this in **Google Colab**:  

```bash
!pip install -r requirements.txt ```


⚡ Model Performance & Insights
Trained ML Models:
✅ Naïve Bayes
✅ Decision Tree
✅ Random Forest

Performance Comparison
📌 The performance comparison of these models is attached below:

![image](https://github.com/user-attachments/assets/1955781f-040f-488c-a2b7-71c74cec4106)

📌 Key Configuration:

Bag of Words (BoW) with 20,000 max_features
For practice purposes, you can experiment with different values of max_features


**🔥 Example Reviews to Test**
Sarcastic:

"Oh wow, what an amazing movie! If only I had a pillow to sleep through the entire thing."
Mixed Sentiment:

"The cinematography was stunning, but the plot was as thin as a sheet of paper."
Ambiguous:

"It’s one of those movies that makes you think… mostly about why you wasted your time watching it."

🔥 Future Enhancements
🔹 Improve Feature Engineering: Instead of Bag-of-Words, try Tf-Idf weighted Word2Vec for better model performance.
🔹 Deep Learning Approach: Experiment with LSTMs, CNNs, or Transformers to boost accuracy.
🔹 Ensemble Learning: Combine multiple models to enhance robustness.
🔹 Fine-tuning: Use a flagged dataset to fine-tune and refine the model.

🙌 Acknowledgments
Special thanks to Kaggle for the dataset and Gradio for making UI deployment easy! 🎉
