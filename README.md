
# 🗳️ Online Voting System

This is a Python-based E-Voting System built using socket programming and multithreading. It provides a secure interface for voters and administrators to participate in an election process digitally. Built as an academic project at IIIT Vadodara.

## 📌 Features

- ✅ Admin and Voter login system
- 🔐 Secure authentication
- 🧾 One vote per voter enforcement
- 📤 Real-time voting via TCP socket
- 📊 View results from admin panel
- 👥 Multiple concurrent client support using threads
- 🗂️ Data stored in CSV files

## 🛠️ Tech Stack

| Component          | Technology         |
|-------------------|--------------------|
| Programming       | Python             |
| Networking        | Socket Programming |
| Protocol          | TCP                |
| GUI               | Tkinter            |
| Data Storage      | CSV Files          |
| Data Handling     | pandas             |
| Subprocess Calls  | subprocess module  |

## 📦 Requirements

- Python 3.x
- `pandas`
- `tkinter`
- `socket`
- `subprocess`

Install dependencies (if needed):

```bash
pip install pandas
```

## 🚀 How to Run

1. Open terminal or command prompt.
2. Navigate to the project folder:
   ```bash
   cd Voting
   ```
3. Run the home page:
   ```bash
   python homePage.py
   ```
4. The GUI window will open. Follow the workflow to use admin or voter functions.

## 🔑 Login Credentials

**Admin Login:**
- ID: `Admin`
- Password: `admin`

**Voter Login:**
- IDs: `10001` to `10005`
- Password: `abcd`
- Ensure the server is running before voter login.

## 🔄 Workflow

1. Launch `homePage.py`.
2. Admin logs in and starts the server.
3. Register new voters and note their ID.
4. Voter logs in and casts a vote.
5. Admin can view votes using "Show Votes".
6. Multiple voters can vote concurrently via separate windows.

## 🧪 Test Cases

- ✅ Valid voter can vote once and only once.
- ❌ Invalid voters are denied access.
- 🔁 Multiple clients can connect and vote concurrently.

## 🗃️ Database

- Voter data and candidate data are stored in CSV files and handled via pandas.

## 🧾 Conclusion

This project demonstrates how to use Python socket programming and multithreading to implement a secure and efficient online voting system with a user-friendly GUI. Developed as part of coursework at IIIT Vadodara.

---

## 👥 Authors

- Saiyam

📍Global Institute of Technology and Management  
🗓️ 7th November 2024

