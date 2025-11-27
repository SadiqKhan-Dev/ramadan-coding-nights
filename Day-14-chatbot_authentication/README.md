# Chatbot with Authentication

A chatbot application with authentication features, built with Python and Chainlit, managed using **UV** package manager. It uses `chainlit.yaml` for configuration.

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
uv init chatbot-authentication
cd chatbot-authentication
```

---

### 3️⃣ Install Chainlit (Dependency)

```sh
uv add chainlit
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

### 5️⃣ Run the Chatbot with Authentication

```sh
chainlit run main.py -w
```

🎉 That’s it! Your Chatbot with Authentication is ready to use 🚀
