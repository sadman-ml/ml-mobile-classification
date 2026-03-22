#  Mobile Price Classification & Prediction

**About:** I analyzed a dataset of 2,000 mobile phones to understand how hardware specs like RAM, Battery, and Camera affect the price. Using Machine Learning, I built a system that can predict which price category (**Low, Medium, High, or Very High**) a phone belongs to with **96.5% accuracy!**

---

###  Tech Stack & Tools:
* **Language:** Python 
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **ML Framework:** Scikit-Learn (Classification & Tuning)
* **Environment:** Google Colab / Jupyter Notebook

---

###  Files in This Repo:
* **`mobile_classification.ipynb`** - Main code, Data Cleaning, and ML Models.
* **`train.csv`** - The dataset containing 2,000 mobile phone records.
* **`best_model.pkl`** - My best-performing trained model (ready to use!).
* **`visualizations/`** - Folder containing all the cool charts and heatmaps.

---

###  What I Discovered?
* **RAM is the King:** My analysis shows that **52%** of a phone's price depends solely on its RAM. It's the biggest factor! 
* **Battery & Screen:** After RAM, Battery power (~7.3%) and Pixel resolution are the next most important things for a higher price tag. 
* **Logistic Regression Wins:** Among all models (SVM, Random Forest, etc.), Logistic Regression performed the best with a whopping **96.5% accuracy**. 
* **Tuning Matters:** I used `GridSearchCV` to tune my Random Forest model, which improved its performance. 

---

### How to Check My Work:
1. Open **Google Colab** or **Jupyter**.
2. Upload the `.ipynb` file and the `train.csv` dataset.
3. Run the cells step-by-step (**Shift + Enter**).
4. You will see all the data cleaning, the 96% accuracy result, and the colorful charts!

---

###  Why I Made This?
I am a **CSE student** and I'm deeply interested in **Machine Learning and Data Science**. I wanted to learn how real-world products (like phones) are priced based on their features. This project helped me practice data preprocessing, feature importance, and model saving. **Learning by doing!**

---

###  Contact & Support
If you find this project helpful or interesting, please give it a **Star**! ⭐

**Sadman Ahmed** *Computer Science & Engineering Student*
