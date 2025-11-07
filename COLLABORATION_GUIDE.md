

### 📘 **COLLABORATION_GUIDE.md**

# 🤝 Social Media App — Collaboration Guide

Welcome to our team project!
This document explains how everyone can **set up, contribute, and merge their own work** using GitHub.

---

## 🧭 1. Accept the Collaboration Invite

* Check your **email or GitHub notifications** for an invite from the repo owner.
* Click **Accept Invitation** before pushing any code.

---

## 💻 2. Clone the Repository

Open VS Code → Terminal → run:

```bash
git clone https://github.com/<OWNER_USERNAME>/social_media_app.git
cd social_media_app
```

---

## 🐍 3. Set Up Your Local Environment

Make sure Python 3.10 + is installed, then:

```bash
pip install -r requirements.txt
```

---

## ▶️ 4. Run the App Locally

Test that it works:

```bash
python main.py
```

If a database file (e.g., `social_media.db`) appears, setup is complete.

---

## 🌿 5. Branch Strategy

| Branch      | Purpose                                                                  |
| ----------- | ------------------------------------------------------------------------ |
| `main`      | Always contains the latest stable version                                |
| `feature-*` | Each member’s work branch (e.g., `feature-login-ui`, `feature-comments`) |

Everyone works on their own branch and merges when tested.

---

## ✏️ 6. Work on Your Own Branch

Before editing files:

```bash
git checkout -b feature-your-task-name
```

Example:

```bash
git checkout -b feature-profile-ui
```

Make changes, then:

```bash
git add .
git commit -m "Added profile UI window"
git push origin feature-profile-ui
```

---

## 🔁 7. Create and Merge Your Pull Request (Self-Managed)

1. Push your branch:

   ```bash
   git push origin feature-your-task-name
   ```
2. On GitHub → **Pull Requests → New Pull Request**
   Compare your branch (`feature-your-task-name`) with `main`.
3. Add a short description of your update.
4. ✅ **Merge your own PR** after verifying that your code runs correctly and doesn’t break existing features.

> Test locally before merging to keep `main` stable.

---

## 💬 8. Stay Up to Date

Before starting new work:

```bash
git checkout main
git pull origin main
```

Then update your feature branch:

```bash
git checkout feature-your-task-name
git merge main
```

---

## ⚠️ 9. Handling Merge Conflicts

If Git flags conflicts:

1. Open the file in VS Code.
2. Decide which version to keep between

   ```
   <<<<<<< HEAD
   your code
   =======
   teammate’s code
   >>>>>>> main
   ```
3. Edit, save, then:

   ```bash
   git add .
   git commit -m "Resolved merge conflict"
   git push
   ```

---

## 🛡️ 10. Project Rules

✅ Each member can merge their own pull requests.
✅ Always test your branch before merging.
✅ Use clear branch names and commit messages.
✅ Inform the team before major changes.
🚫 Don’t edit another member’s feature branch without permission.

---

## 🏁 Quick Recap

> **Clone → Branch → Code → Commit → Push → Pull Request → Merge → Pull Updates**

---

