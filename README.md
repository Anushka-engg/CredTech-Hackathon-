# 📊 CredTech Hackathon – Explainable Credit Intelligence Platform

This project was developed for the **CredTech Hackathon**, organized by **The Programming Club, IITK** and powered by **Deep Root Investments**.

It is an **Explainable Credit Intelligence Platform** that ingests financial data, computes creditworthiness scores, and visualizes them through an interactive **Streamlit dashboard** connected to **MongoDB Atlas**.

---

## 🚀 Features

* 🔗 **Streamlit-powered interactive dashboard**
* 🗄️ **MongoDB Atlas integration** with `pymongo`
* 📊 Displays **scores** collection in a clean table link - [https://redesigned-lamp-pjg55xw4r767f6r5p-8501.app.github.dev/](https://redesigned-lamp-pjg55xw4r767f6r5p-8501.app.github.dev/)
* ⚡ Auto-deployable inside **GitHub Codespaces**
* 🖥️ Easy local setup

---

## 📂 Project Structure

```
├── app.py               # Main Streamlit app
├── requirements.txt     # Python dependencies
├── .devcontainer/       # Devcontainer config for Codespaces
│   ├── devcontainer.json
│   └── start.sh
└── README.md            # This file
```

---

## 🛠️ Setup & Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/CredTech-Hackathon-.git
cd CredTech-Hackathon-
```

### 2️⃣ Set up a virtual environment (recommended)

```bash
python3 -m venv .venv
source .venv/bin/activate   # (Windows: .venv\Scripts\activate)
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```


## ▶️ Running the App

### Locally

```bash
streamlit run app.py
```

### In GitHub Codespaces

* This repo includes a **devcontainer setup**
* When opened in Codespaces, the app will automatically start (default port `8501`)
* Open it via the **Ports tab** or Preview browser
---

## ✅ Requirements

* Python **3.9+**
* Packages from `requirements.txt`:

  * `streamlit`
  * `pymongo`
  * `pandas`

---

## 👩‍💻 Author

Developed by **Anushka Sarkar** ✨

