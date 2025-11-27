# Personal Library Manager

A simple command-line application to manage your personal library, built with Python and managed using **UV** package manager. It uses `books_data.json` to store book information.

## Getting Started

### 1️⃣ Install UV

First, install **UV** (if not already installed):

```sh
curl -LsSf https://astral.sh/uv/install.sh | sh
```

For Windows:

```sh
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

Verify installation:

```sh
uv --version
```

---

### 2️⃣ Create and Initialize the Project

```sh
uv init personal-library-manager
cd personal-library-manager
```

---

### 3️⃣ Activate UV Virtual Environment (Windows)

```sh
.venv\Scripts\activate
```

For Linux/macOS:

```sh
source .venv/bin/activate
```

---

### 4️⃣ Run the Personal Library Manager

```sh
uv run python main.py
```

🎉 That’s it! Your Personal Library Manager is ready to use 🚀
