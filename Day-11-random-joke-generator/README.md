# Random Joke Generator

A simple command-line application that generates random jokes, built with Python and managed using **UV** package manager.

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
uv init random-joke-generator
cd random-joke-generator
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

### 4️⃣ Run the Random Joke Generator

```sh
uv run python main.py
```

🎉 That’s it! Your Random Joke Generator is ready to use 🚀
