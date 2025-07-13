# Hello GitHub Actions

This is a minimal example to demonstrate how GitHub Actions runs a Python script.

## 📁 Project Structure

```
hello-github-actions/
├── .github/
│   └── workflows/
│       └── main.yml
├── hello.py
├── requirements.txt
└── README.md
```

## 🚀 How It Works

When you push to `main`, GitHub Actions will:
1. Checkout the repo
2. Set up Python
3. Install dependencies
4. Run `hello.py`

## 💻 Run Locally

```bash
python hello.py
```
