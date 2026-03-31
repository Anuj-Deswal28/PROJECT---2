# PROJECT---2
This is a Transformer based conversation summarizer , uses hugging face and fastapi , fully deployed project .
# STEPS TO BE FOLLOWED
*STEP-1 :- download the main.py file , it contains all the code for training the model 
* STEP-2 :- intall following packages in your system [transformers, pandas, torch, transformer[torch], fastapi ,uvicorn ]
* STEP-3 :- train the model using given data
* STEP-4 :- download and run app.py
* STEP-5 :- in terminal give command [uvcorn app:app --reload] , it will return you a local port that you can open

[**TRAINING ON GPU IS HIGHLY RECOMMENDED**]
[**main.ipynb should be open and used in jupyter-notebook**]
[**after training a new folder should be created named as saved_summary_model**]

# 🧠 Conversation Summarizer (T5-small + FastAPI)

A full-stack AI application that generates concise summaries from conversations using the **T5-small Transformer model** from Hugging Face. The project is deployed with **FastAPI** and includes a simple frontend built with HTML, CSS, and JavaScript.

---

## 🚀 Features

* 🔹 Summarizes long conversations into short, meaningful text
* 🔹 Powered by **T5-small Transformer (Hugging Face)**
* 🔹 Fast and lightweight API using **FastAPI**
* 🔹 Clean and responsive frontend (HTML, CSS, JS)
* 🔹 End-to-end pipeline from input → processing → summarized output

---

## 🛠️ Tech Stack

* **Backend:** FastAPI (Python)
* **Model:** T5-small (Hugging Face Transformers)
* **Frontend:** HTML, CSS, JavaScript
* **Libraries:** Transformers, Torch, Uvicorn

---

## 📂 Project Structure

```
project/
│── main.py                # FastAPI backend
│── saved_summary_model/   # Trained/loaded model (ignored in Git)
│── static/               # CSS, JS files
│── templates/            # HTML files
│── requirements.txt
│── .gitignore
│── README.md
```

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```
git clone https://github.com/your-username/your-repo.git
cd your-repo
```

### 2. Create virtual environment

```
python -m venv venv
venv\Scripts\activate     # Windows
```

### 3. Install dependencies

```
pip install -r requirements.txt
```

### 4. Run the server

```
uvicorn main:app --reload
```

### 5. Open in browser

```
http://127.0.0.1:8000
```

---

## 🧪 How It Works

1. User enters a conversation in the frontend
2. Request is sent to FastAPI backend
3. Backend loads T5-small model
4. Model processes input and generates summary
5. Summary is returned and displayed to user

---

## 📸 Demo

*Add screenshots or demo GIF here*

---

## ⚠️ Note

* Large model files are not included in this repository due to GitHub size limits
* You may need to download/load the model separately

---

## 🔮 Future Improvements

* 🔹 Deploy on cloud (AWS / Render / Vercel)
* 🔹 Add user authentication
* 🔹 Improve summarization accuracy with fine-tuning
* 🔹 Add support for multiple languages

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repo and submit a pull request.

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Author

**Anuj Deswal**
AI/ML Enthusiast | B.Tech CSE

---
