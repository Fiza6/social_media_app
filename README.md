

### 📘 **README.md**

# 💬 Social Media App (Python + Tkinter + SQLite)

A desktop-based **Social Media Platform** built using **Python, Tkinter, and SQLite**.
It allows users to register, log in, post updates, view feeds, and interact with others — all in an easy-to-use graphical interface.

---

## 🧰 Features

* 👥 **User Registration & Login**
  Secure authentication with password hashing.

* 📰 **Post Feed System**
  Users can create, edit, and delete posts.

* 💬 **Comment & Interaction Support**
  Real-time post interaction system.

* 👨‍💻 **Admin Panel**
  Manage users, monitor posts, and moderate content.

* 🗄️ **Local Database (SQLite)**
  No setup required — runs instantly with a built-in database file.

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/<OWNER_USERNAME>/social_media_app.git
cd social_media_app
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the App

```bash
python main.py
```

A window will appear — start by creating your first account!

---

## 🌿 Branching Workflow

| Branch      | Purpose                                                                    |
| ----------- | -------------------------------------------------------------------------- |
| `main`      | Stable and tested version                                                  |
| `feature-*` | Individual work branches (e.g., `feature-login-ui`, `feature-feed-system`) |

---

## 🚀 How to Contribute (Self-Managed)

Each team member is responsible for **their own code and pull requests**.

1. **Create a feature branch**

   ```bash
   git checkout -b feature-your-task-name
   ```

2. **Work locally**, then commit and push

   ```bash
   git add .
   git commit -m "Added login validation"
   git push origin feature-your-task-name
   ```

3. **Open a Pull Request on GitHub**

   * Compare `feature-your-task-name` → `main`
   * Review and merge **your own PR** after testing.

4. **Sync with latest changes**

   ```bash
   git checkout main
   git pull origin main
   git merge main
   ```

---

## 🧩 Team Roles

| Member                 | Responsibility                                    |
| ---------------------- | ------------------------------------------------- |
| 👑 **Owner**           | Repo setup, database structure, and admin UI      |
| 👩‍💻 **Team Members** | Individual feature development & testing          |
| 🧠 **Everyone**        | Keeps their branch updated and merges responsibly |

---

## 🧾 Collaboration Rules

* Test your branch before merging into `main`.
* Use clear branch names and meaningful commit messages.
* Don’t overwrite another member’s work.
* Communicate major updates in the team group.

---

## 💡 Tech Stack

* **Language:** Python 3.10+
* **GUI:** Tkinter
* **Database:** SQLite
* **Version Control:** Git + GitHub

---

## 🏁 Quick Commands Reference

| Action        | Command                          |
| ------------- | -------------------------------- |
| Clone repo    | `git clone <repo-url>`           |
| Create branch | `git checkout -b feature-branch` |
| Push changes  | `git push origin feature-branch` |
| Merge main    | `git merge main`                 |
| Run project   | `python main.py`                 |

---

## 🧭 Related Docs

* 📄 [COLLABORATION_GUIDE.md](./COLLABORATION_GUIDE.md) — full Git workflow & merge rules
* 📘 `requirements.txt` — project dependencies

---

