# 🎵 Music Recommendation App

Welcome to the **Music Recommendation App** — a smart music suggestion system built with **Streamlit** and **Machine Learning**, using Spotify’s metadata!

---

## 🚀 Features

- 🎧 Recommends songs based on user-selected input
- 🤖 ML-based similarity using TF-IDF and cosine similarity
- 📊 Preprocessing and clean-up of metadata from Spotify
- 🖥️ Web interface built with **Streamlit**
- 📂 Lightweight — heavy dataset zipped separately

---

## 🛠️ Tech Stack

- **Python 3.11**
- **Streamlit**
- **Pandas**, **Scikit-learn**, **Numpy**
- **TF-IDF Vectorizer**
- **Cosine Similarity**
- Dataset: `spotify_millsongdata.csv` (zipped for GitHub)

---

## 📁 Project Structure

```
Music_Recommendation_App/
│
├── src/
│   ├── main.py                # Streamlit app entry point
│   ├── preprocess.py          # Data cleaning & preparation
│   ├── recommend.py           # Recommendation logic
│   ├── spotify_millsongdata.zip  # Zipped dataset (manual unzip required)
│
├── requirements.txt           # Python dependencies
├── Music_Recommendation_App.ipynb  # Jupyter experiments
├── start_app.txt              # Optional run instructions
├── .gitignore
└── README.md
```

---

## ⚙️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/saranya-B-23/Music_Recommendation_python.git
   cd Music_Recommendation_python
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv .venv
   .venv\Scripts\activate   # On Windows
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Unzip the dataset**
   - Navigate to `src/`
   - Extract `spotify_millsongdata.zip` to get `spotify_millsongdata.csv`

5. **Run the app**
   ```bash
   streamlit run src/main.py
   ```

---

## 👩‍💻 Author

- **Saranya B**  
- GitHub: [saranya-B-23](https://github.com/saranya-B-23)
