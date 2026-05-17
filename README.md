🎬 Movie Recommender System (Streamlit App)
📌 Overview

This is an interactive Movie Recommender System web app built using Streamlit and Machine Learning.
It recommends similar movies based on user selection using content-based filtering and cosine similarity.

🚀 Live App Features
🎯 Select a movie from dropdown
🎬 Get top similar movie recommendations instantly
⚡ Fast and lightweight Streamlit UI
🧠 ML-based similarity engine
📊 Precomputed similarity matrix for efficiency
🛠️ Tech Stack
Python 🐍
Streamlit 🎈
Pandas
NumPy
Scikit-learn
Pickle
📁 Project Structure

movie-recommender-system/
│
├── app.py                      # Streamlit application
├── movie-recommender-system.ipynb  # Model building notebook
├── movies_dict.pkl             # Processed movie dataset
├── similarity.pkl              # Cosine similarity matrix
├── README.md                   # Project documentation

⚙️ How It Works
Movie dataset is cleaned and preprocessed
Important features are combined into a "tags" column
Text vectorization is applied
Cosine similarity is calculated between all movies
Streamlit app uses this matrix to recommend similar movies
▶️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/your-username/movie-recommender-system.git
cd movie-recommender-system
2️⃣ Install dependencies
pip install streamlit numpy pandas scikit-learn
3️⃣ Run the Streamlit app
streamlit run app.py
🎬 How to Use
Open the app in browser (usually http://localhost:8501)
Select a movie from dropdown menu
Click Recommend
Get top similar movies instantly 🎉
📊 Example Output

Input Movie:
👉 Avatar

Recommended Movies:

Avatar 2
John Carter
Guardians of the Galaxy
Interstellar
The Avengers
🧠 Machine Learning Concept Used

This project uses:

Content-Based Filtering
Cosine Similarity
TF-IDF / Feature Engineering (tags-based system)
👩‍💻 Author

Khushi Kumari
B.Sc Computer Science, IIT Patna

🚀 Future Improvements
Add poster images using TMDB API 🎥
Deploy on Streamlit Cloud ☁️
Add user login system 🔐
Improve recommendation using deep learning 🤖
⭐ If you like this project

Give it a ⭐ on GitHub and feel free to fork it!
