Cosmetic Product Recommendation System

📌 Project Overview

This project implements and compares multiple **product recommendation models** using a real-world dataset of **cosmetic product reviews**. The goal is to analyze user–product interactions and textual reviews to build effective recommender systems that can suggest relevant cosmetic products to users.

The project was developed as part of the **Applied Machine Learning** course and focuses on applying core ML concepts to a practical recommendation problem.

---

📂 Dataset

* **Source:** Cosmetic Product Reviews Dataset
* **Contents:**

  * Product information (brand, category, etc.)
  * User ratings and reviews
  * Textual feedback provided by customers

The dataset is preprocessed to handle missing values, normalize text, and structure user–item interactions suitable for recommendation algorithms.

---

🛠 Models Implemented

The following recommendation approaches are implemented and analyzed:

1️⃣ Content-Based Filtering

* Uses textual features from product reviews
* TF-IDF vectorization applied to review text
* **Cosine similarity** used to measure product similarity
* Recommends products similar to those a user liked previously

2️⃣ Collaborative Filtering

* Utilizes user–item interaction patterns
* Recommendations based on similarities between users or items
* Captures collective user preferences

3️⃣ Model Comparison

* Models are evaluated based on recommendation relevance and interpretability
* Strengths and limitations of each approach are discussed

---

📊 Evaluation Strategy

* Qualitative analysis of recommendations
* Similarity score comparisons
* Practical effectiveness in generating meaningful suggestions

Due to the nature of recommender systems, emphasis is placed on **recommendation quality and logic** rather than traditional classification accuracy.

---

💻 Technologies Used

* Python
* Pandas, NumPy
* Scikit-learn
* Natural Language Processing (TF-IDF)
* Jupyter Notebook

---

▶️ How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/cosmetic-product-recommendation.git
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook:

   ```bash
   jupyter notebook Product\ Recommendation.ipynb
   ```
4. Run all cells sequentially.

---

🚀 Future Improvements

* Incorporate deep learning–based recommenders
* Add hybrid recommendation techniques
* Deploy as a web-based recommendation service
* Include quantitative metrics (Precision@K, Recall@K)

---

🎓 Academic Context

This project was completed as part of the **Applied Machine Learning** course at FAST-NUCES. It is intended for educational and demonstration purposes.

---

👤 Author

Omer Khalid
Software Engineering Student – FAST NUCES

---

⭐ If you find this project useful, feel free to star the repository!
