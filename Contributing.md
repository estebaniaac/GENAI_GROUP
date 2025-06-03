# CONTRIBUTING.md

Thank you for your interest in contributing! To keep the project maintainable and collaborative, please follow these guidelines:

---

## 🚀 How to Contribute

1. **Fork the repo** (if external).
2. **Create a new branch** from `main`:

   ```
   git checkout -b feature/my-feature
   ```
3. **Work locally**, commit often with clear messages.
4. **Pull the latest changes** from `main` regularly and **rebase**:

   ```
   git fetch origin
   git rebase origin/main
   ```
5. **Push your branch** and open a **Pull Request (PR)**.
6. **Discuss and communicate** changes **before merging**.
7. **Never merge to `main` without communicating with the team**.
8. Once a PR is reviewed and approved, **merge or ask someone to merge** it.

---

## 🔁 Rebasing Policy

Whenever **anyone merges into `main`**, all contributors must:

* Pull the latest `main`:

  ```
  git fetch origin
  ```
* **Rebase their branch from `main`** before continuing:

  ```
  git rebase origin/main
  ```
* **Resolve conflicts** if any, and force-push:

  ```
  git push --force
  ```

This keeps the history linear and clean.

---

## ✅ Code Style & Commit Messages

* Write clear and concise commits:
  `feat: add search functionality`
  `fix: handle null input in parser`

* Follow existing code conventions and file structure.

---

## 🛠️ Tests

If your contribution includes logic changes, add relevant tests in the `/tests` folder.

---

## 📞 Communication is Key

Always **communicate before merging to `main`**, even if it seems minor. This prevents disruptions and keeps everyone aligned.
