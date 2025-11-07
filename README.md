# 🎬 Movie Recommendation System (Content-Based)

This project is a **Movie Recommendation System** that suggests similar movies based on content such as:
- Genres
- Keywords
- Cast
- Crew (Director)

It uses **Cosine Similarity** to measure how close movies are in the feature-space created from their metadata.

---

## ✅ Features
✔ Content-based movie recommendations  
✔ Top 5 similar movie suggestions  
✔ TMDB API integration for posters
✔ Streamlit web-app interface  
✔ Real-time prediction system  

---

## 🧠 How It Works
1️⃣ Movie metadata is collected and cleaned  
2️⃣ Important features are combined into **tags**  
3️⃣ Text data is transformed using **CountVectorizer**  
4️⃣ **Cosine similarity matrix** is built  
5️⃣ Given a movie → it finds closest matches  
6️⃣ Displays top 5 recommendations with their posters

---

## 🚀 Tech Stack

| Component | Technology |
|---------|------------|
| 💻 Programming | Python |
| 🧮 ML/Similarity | Cosine Similarity, NLP |
| 🎯 Web Framework | Streamlit |
| 🛠 Libraries | Pandas, NumPy, Scikit-learn, NLTK |
| 🎥 Movie Posters | TMDB API |

---

## 📂 Project Structure
| Folder Name | Content |
|---------|------------|
| app.py | Streamlit App |
| movie_list.pkl | Movie dataset for UI |
| similarity.pkl | Precomputed similarity matrix |
| requirements.txt | Project dependencies |
| README.md | Documentation |

---

## ▶️ How to Run Locally

pip install -r requirements.txt
streamlit run app.py

---

## 🌐 Deployment

This app can be deployed easily using Streamlit Cloud:

📌 https://share.streamlit.io

---

## 🔧 Future Enhancements
✅ Include Movie overview and ratings
✅ Add hybrid recommendations (content + collaborative filtering)

---
