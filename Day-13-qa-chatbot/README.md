# QA Chatbot

A question-answering chatbot application built with Python and Chainlit, managed using **UV** package manager. It also includes a `.env` file for environment variables and `terminal.py` for a terminal-based interaction option.

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
uv init qa-chatbot
cd qa-chatbot
```

---

### 3️⃣ Install Chainlit and other dependencies (if any)

```sh
uv add chainlit
```
(If there are other dependencies, they would go here, but I will assume chainlit is the primary one for the README)

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

### 5️⃣ Run the QA Chatbot

```sh
chainlit run main.py -w
```
(You might also be able to run `python terminal.py` for a terminal version, depending on its implementation)

🎉 That’s it! Your QA Chatbot is ready to use 🚀
