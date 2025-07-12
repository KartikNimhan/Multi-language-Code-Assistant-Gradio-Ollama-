````markdown
# 🧠 Multi-language Code Assistant (Gradio + Ollama)

A lightweight, interactive **code assistant** built using [Gradio](https://www.gradio.app/) for the frontend and a locally hosted **LLM (`codeguru`)** served via [Ollama](https://ollama.com/) on the backend.

---

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/Multi-language-Code-Assistant-Gradio-Ollama-.git
   cd Multi-language-Code-Assistant-Gradio-Ollama-
````

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Start the Ollama server with your model**

   ```bash
   ollama run codeguru
   ```

4. **Run the Gradio app**

   ```bash
   python app.py
   ```

---

## 🧪 Usage

* Type your **code question or instruction** in the prompt box.
* The assistant responds using a **local LLM** (via Ollama).
* Prompt history is retained for better contextual understanding.

---

## 📁 Project Structure

```
multilanguage-code-assistant/
│
├── app.py               # Main application code (Gradio + API call)
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
```

---

## 💬 Example Prompt

```text
How do I write a Python function to reverse a string?
```

---

## 🔧 Notes

* Ensure that [Ollama](https://ollama.com/) is installed and running.
* Confirm the `codeguru` model is available locally:

  ```bash
  ollama run codeguru
  ```
* This project assumes the Ollama API is available at:

  ```
  http://localhost:11434
  ```

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 🙌 Acknowledgements

* [Gradio](https://www.gradio.app/)
* [Ollama](https://www.ollama.com/)

```

