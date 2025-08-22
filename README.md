Got it ✅
I’ll prepare a **README.md** for your GitHub repo so that anyone (including you) can run your Streamlit + MongoDB app smoothly.

Here’s a polished draft:

---

# 📊 CredTech Hackathon – Streamlit + MongoDB Dashboard

This project is a **Streamlit web application** connected to **MongoDB Atlas**, built for the CredTech Hackathon.
It displays data from the `hackathon_db` database and visualizes it in a simple dashboard.

---

## 🚀 Features

* Streamlit-powered interactive dashboard
* MongoDB Atlas integration via `pymongo`
* Displays **scores collection** in a clean table
* Auto-deployable inside **GitHub Codespaces**

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

### 2️⃣ Set up a virtual environment (optional, recommended)

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Configure Secrets

Create a `.streamlit/secrets.toml` file and add your MongoDB credentials:

```toml
MONGO_URI = "mongodb+srv://<username>:<password>@cluster.mongodb.net/?retryWrites=true&w=majority"
DB_NAME = "hackathon_db"
```

---

## ▶️ Running the App

### Locally

```bash
streamlit run app.py
```

### In GitHub Codespaces

This repo includes a **devcontainer setup**:

* When you open it in **Codespaces**, the app will automatically start on port **8501**.
* You’ll see a preview panel or open it via the forwarded ports tab.

---

## ✅ Requirements

* Python 3.9+
* MongoDB Atlas Cluster
* Packages in `requirements.txt`:

  * `streamlit`
  * `pymongo`
  * `pandas`

---

## 📸 Screenshot

*(Add a screenshot of your running Streamlit app here)*

---

## 👩‍💻 Author

Developed by **Anushka Sarkar** ✨

