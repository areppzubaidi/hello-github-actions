
# 👋 Hello GitHub Actions

This is a beginner-friendly project that demonstrates how to use **GitHub Actions** with a simple Python script.

## 🚀 What it does

- Runs a Python script (`hello.py`) automatically whenever you push code to the `main` branch using GitHub Actions.

## 🗂 Project Structure

```

hello-github-actions/
├── .github/
│   └── workflows/
│       └── main.yml     # GitHub Actions workflow file
├── hello.py             # Simple Python script
└── README.md            # Project documentation

```

## ⚙️ GitHub Actions Workflow

GitHub Actions is configured in `.github/workflows/main.yml`.

Here’s what it does:

- Trigger: On every `push` to the `main` branch
- Steps:
  1. Checks out the code
  2. Sets up Python
  3. Runs `hello.py`

## 🧪 How to Use

1. **Fork this repository** or clone it.
2. Modify or push any file to the `main` branch.
3. Go to the **"Actions"** tab in your GitHub repository.
4. You will see a workflow run — click into it to view logs.

## 📜 Sample Output

The `hello.py` script prints:

```

👋 Hello from GitHub Actions!

```

## 💡 What to Try Next

- Add more Python scripts and automate them.
- Schedule workflows with `on: schedule`.
- Add CI tests (e.g., `pytest`).
- Try building and deploying a static site automatically.

---

✅ **Made for learning GitHub Actions basics.**

Happy Coding! 🎉
```

---

Let me know if you'd like a version for **Node.js**, **Docker**, or a different language next!
