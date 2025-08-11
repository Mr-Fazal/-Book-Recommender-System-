
# 📚 Book Recommender System  
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)](https://www.python.org/)  
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org/)  
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)  
[![Kaggle Dataset](https://img.shields.io/badge/Dataset-Kaggle-blue?logo=kaggle)](https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset)  
[![Pandas](https://img.shields.io/badge/Pandas-1.5.0-blue?logo=pandas)](https://pandas.pydata.org/)  
[![Numpy](https://img.shields.io/badge/Numpy-1.23.0-orange?logo=numpy)](https://numpy.org/)  

---

## ✨ Overview  
The **Book Recommender System** is a machine learning project designed to recommend books 📖 based on user preferences, ratings, and past behavior.  
This project leverages **Python**, **Pandas**, **NumPy**, and **Machine Learning algorithms** to train a recommendation model that suggests top-rated and relevant books for a user.  
Built in **Jupyter Notebook**, it’s simple to understand and easy to extend for production use.  
 
The **Book Recommender System** is an intelligent platform that first showcases the **Top 50 most popular books** from a collection of **10,000+ titles** 📚, based on aggregated user ratings and reviews.  

Once the user searches for a specific book, the system leverages machine learning algorithms to **recommend other books with similar themes, genres, or user interest patterns**. This provides a personalized and engaging discovery experience — helping readers explore new books they’re likely to enjoy.  

💡 **Key Highlight:**  
It’s like having your own virtual librarian 🧑‍🏫 who not only tells you what’s trending but also suggests titles tailored to your reading taste.  

 
💡 **Why This Project?**  
In the age of information overload, finding the right book can be overwhelming. This recommender system makes that decision easier — just like Netflix, but for books! 📚❤️  

---

## 🗂 Dataset Information  
We used the **[Book Recommendation Dataset from Kaggle](https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset)** containing:
- **Books.csv** → Book title, author, year, publisher, image URL, etc.  
- **Ratings.csv** → User IDs, ISBNs, ratings given by users.  
- **Users.csv** → Demographic information about the readers.  

📊 **Dataset Size:**
- **Books:** 271,379 entries  
- **Users:** 278,858 entries  
- **Ratings:** 1,149,780 ratings  

---

## 🔍 Project Flow  


graph TD
A[📥 Load Dataset from Kaggle] --> B[🧹 Data Cleaning & Preprocessing]
B --> C[📊 Exploratory Data Analysis (EDA)]
C --> D[⚙️ Model Selection: Collaborative Filtering & Popularity-Based]
D --> E[🧠 Train & Evaluate Model]
E --> F[📈 Generate Recommendations]
F --> G[💻 Display in Jupyter Notebook]

---
## 💻 Development Environment & Deployment  

This project was developed using **PyCharm** as the primary IDE, ensuring a clean, structured, and maintainable codebase.  
After building and validating the machine learning model in **Jupyter Notebook**, the recommendation logic was integrated into a **web application** for a better user experience.  

### 🌐 Web Implementation  
- **Frontend:** Designed using **HTML**, **CSS**, and **Bootstrap** to create a responsive and visually appealing interface.  
- **Backend:** Implemented in **Python** to connect the trained ML model with the frontend.  
- **Functionality:**  
  1. Displays the **Top 50 most popular books** from a collection of 10,000+ titles.  
  2. Allows the user to **search for a specific book**.  
  3. Recommends similar books based on **content similarity & user preference patterns**.  

This transformation from a **Jupyter Notebook prototype** to a **fully functional website** demonstrates end-to-end development skills — from **data science** to **web deployment**. 🚀

| Tool/Library            | Purpose                     |
| ----------------------- | --------------------------- |
| 🐍 Python               | Core programming language   |
| 📓 Jupyter Notebook     | Development & visualization |
| 📊 Pandas               | Data manipulation           |
| ➗ NumPy                 | Numerical operations        |
| 🤖 Scikit-learn         | Machine learning algorithms |
| 🎨 Matplotlib / Seaborn | Data visualization          |


🚀 Features
✅ Popularity-Based Recommender — suggests books based on high ratings & number of ratings.
✅ Collaborative Filtering — recommends books based on similar user tastes.
✅ Data Visualization — insightful charts & graphs for understanding patterns.
✅ User-Friendly — clean notebook structure, ready to run.

📦 Installation & Setup
bash
Copy
Edit
# 1️⃣ Clone the repository
git clone https://github.com/yourusername/Book-Recommender-System.git

# 2️⃣ Navigate into the project directory
cd Book-Recommender-System

# 3️⃣ Install dependencies
pip install -r requirements.txt

# 4️⃣ Run Jupyter Notebook
jupyter notebook
🧠 Model Training Steps
1️⃣ Load Dataset → from Kaggle link.
2️⃣ Clean Data → remove duplicates, handle missing values.
3️⃣ EDA → explore trends, most popular authors, rating distribution.
4️⃣ Feature Engineering → filter users/books with sufficient ratings.
5️⃣ Model Building →

Popularity-based recommender (ranking books by ratings)

Collaborative Filtering using cosine similarity
6️⃣ Evaluation → Check recommendations manually & validate with test data.
7️⃣ Final Output → List of top 5–10 book recommendations per user.

📸 Screenshots
Popular Books Chart	Recommendations Output
<img width="1913" height="966" alt="image" src="https://github.com/user-attachments/assets/9b55ee85-1392-4ad3-90df-db6d33ed8792" />
<img width="1918" height="963" alt="image" src="https://github.com/user-attachments/assets/fd2bf91c-fc7c-4437-a78a-256c09b8c506" />


💡 Future Improvements
🔹 Integrate content-based filtering for hybrid recommendations.

🔹 Deploy as a web app using Streamlit or Flask.

🔹 Add real-time recommendations from user activity.

🏆 Acknowledgements
Dataset: Kaggle - Book Recommendation Dataset

Inspiration: Netflix recommendation system, Goodreads.

📜 License
This project is licensed under the MIT License — you’re free to use, modify, and distribute with attribution.

⭐ If you like this project, consider giving it a star on GitHub!
Happy Reading & Recommending! 📚✨
