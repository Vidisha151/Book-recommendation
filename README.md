# Book Recommendation System

## Overview
This project is a **Book Recommendation System** that suggests books based on popularity and similarity. It uses **machine learning models** and is deployed as a **web application**.

## Features
- Recommends books based on **popularity** and **similarity scores**.
- **Web interface** built using Flask.
- **Preprocessed data** stored in pickle (`.pkl`) files.
- Deployment-ready with **Heroku support**.

## Project Structure
```
📁 book-recommender-system-master
│-- app.py                    # Main application script (Flask)
│-- book-recommender-system.ipynb # Jupyter Notebook (ML Model)
│-- requirements.txt          # Dependencies
│-- Procfile                  # For Heroku Deployment
│-- templates/                # HTML templates for frontend
│-- books.pkl, popular.pkl, pt.pkl, similarity_scores.pkl  # Preprocessed Data
```

## Installation & Setup
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/YourUsername/book-recommender-system.git
cd book-recommender-system
```

### 2️⃣ Create a Virtual Environment (Optional but Recommended)
```bash
python -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate     # Windows
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Application
```bash
python app.py
```
The application will be available at: **http://127.0.0.1:5000/**

## Deployment (Heroku)
### 1️⃣ Install Heroku CLI (if not installed)
```bash
https://devcenter.heroku.com/articles/heroku-cli
```

### 2️⃣ Login & Create a Heroku App
```bash
heroku login
heroku create book-recommender-app
```

### 3️⃣ Deploy to Heroku
```bash
git init
git add .
git commit -m "Initial commit"
heroku git:remote -a book-recommender-app
git push heroku main
```

## License
This project is **open-source** and available under the **MIT License**.

## Contact
For any queries, reach out via **YourEmail@example.com** or create an **issue** on GitHub.

---
Happy Coding!

