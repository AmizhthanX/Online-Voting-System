# 🗳 Online Voting System

## 📌 Overview
This is an **Online Voting System** developed using **Flask (Python Web Framework)** and hosted on **Render.com**. The system allows voters to **cast their votes securely** and provides an **admin panel** to manage voters, candidates, and view results.

---

## 🌟 Features
✅ **Voter Login** - Secure authentication for voters.  
✅ **Voting System** - Voters can cast a vote only once.  
✅ **Admin Panel** - Manage candidates & voters.  
✅ **Live Results** - View election results instantly.  
✅ **Delete Candidates & Voters** - Admin can remove entries if needed.  
✅ **Auto-Hosted on Render** - Accessible from anywhere online.  

---

## 🛠 Installation & Setup

### 🔹 Step 1: Clone the Repository
```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
```

### 🔹 Step 2: Install Dependencies
```bash
pip install -r requirements.txt
```

### 🔹 Step 3: Run the Application Locally
```bash
python app.py
```

🚀 Open your browser and go to: **http://127.0.0.1:5000/**

---

## ☁ Deploy on Render
1️⃣ **Push the code to GitHub**.  
2️⃣ Go to **Render.com** → **Create New Web Service**.  
3️⃣ Connect to your **GitHub repository**.  
4️⃣ Set:
   - **Build Command** → `pip install -r requirements.txt`
   - **Start Command** → `gunicorn app:app`
5️⃣ Click **Deploy** 🚀

---

## 🔑 Admin Login
👤 **Username:** `admin`  
🔒 **Password:** `admin123`  

---

## 🏗 Tech Stack
- **Backend:** Flask (Python)  
- **Database:** SQLite  
- **Frontend:** HTML, CSS (Bootstrap optional)  
- **Deployment:** Render.com  

---

## 🚀 Future Enhancements
🔹 Improve UI using **Bootstrap**.  
🔹 Add **Email-based Voter Registration**.  
🔹 Implement **Two-Factor Authentication**.  
🔹 Store votes securely using **PostgreSQL instead of SQLite**.  

---

## 📜 License
This project is **open-source** under the **MIT License**.

---

## 🤝 Contribution
Feel free to **fork the repo** and submit **pull requests** to improve the system!  

---

### 👨‍💻 Developed By: **AmizhthanX**

🚀 **If you find this project useful, don't forget to ⭐ star the repo!** 🔥
