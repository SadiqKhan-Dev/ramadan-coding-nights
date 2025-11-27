# Pakistani Joke Generator

A simple API that generates random Pakistani jokes, built with Python, UV, and FastAPI.

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
uv init pakistani-joke-generator
cd pakistani-joke-generator
```

---

### 3️⃣ Install FastAPI (Dependency)

```sh
uv add fastapi uvicorn
```

---

### 4️⃣ Activate UV Virtual Environment (Windows)

```sh
.venv\Scripts\activate
```

For Linux/macOS:

```sh
source .venv/bin/activate
```

---

### 5️⃣ Run the Joke Generator API

```sh
uvicorn main:app --reload
```

### 6️⃣ Test the API

Paste the following into your browser:

```sh
http://127.0.0.1:8000/joke
```

or via Swagger UI:

```sh
http://127.0.0.1:8000/docs
```

🎉 That’s it! Your Pakistani Joke Generator API is ready to use 🚀


