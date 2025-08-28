# 🐙 Git Init & Push Guide

## 1️⃣ Prerequisites
- Install **Git**
- Create a **GitHub account**
- Install **VS Code**

---

## 2️⃣ Create a GitHub Repository
1. Go to [GitHub](https://github.com) → **New Repo**  
2. Name it (e.g., `my-first-project`)  
3. Leave "Initialize with README" **unchecked**  
4. Click **Create Repository**  

---

## 3️⃣ Setup Git in Local Project
Open project in VS Code → **Terminal** → run:

```bash
git init                  # Initialize Git
git add .                 # Stage files
git commit -m "First commit"   # Commit files

4️⃣ Connect to GitHub
Copy repo URL (e.g., https://github.com/user/repo.git) → run:
git remote add origin https://github.com/username/repo-name.git
git branch -M main        # Rename branch to main (if needed)
git push -u origin main   # Push to GitHub

5️⃣ Future Updates
git add .
git commit -m "your message"
git push

