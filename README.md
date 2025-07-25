# 🌟 Nova: Your Playful AI Chatbot

Nova is a playful and fun chatbot that helps you with anything — from casual chats to coding queries. Built for smooth interaction and learning, Nova blends personality with productivity.
---

## 🎬 Demo Coming Soon

[![Watch Demo](https://drive.google.com/file/d/1PBd8IUlHWd7uGIkhehmxCn2YXDgMpKoo/view?usp=sharingw)




---

## 📖 About the Project

In an age where AI is rapidly transforming how we interact with technology, **Nova** aims to demonstrate how you can seamlessly integrate language models into a simple web-based chatbot using Python and Hugging Face.

Unlike traditional bots, Nova is designed to simulate meaningful, thoughtful conversations. It accepts user input via a web interface, generates AI responses via a Hugging Face model, and stores feedback through an integrated feedback form and local SQLite database.

---

## ✨ Key Features

- ⚡ **Hugging Face Transformers**: Uses a Hugging Face model for real-time, intelligent responses.
- 🧠 **Local Feedback Collection**: Captures user ratings and comments using a simple feedback form.
- 🌐 **Web-Based UI**: Clean, responsive frontend using HTML, CSS, and internal JavaScript.
- 🐍 **Flask Backend**: Lightweight and easy to deploy with Python and Flask.
- 💾 **Local SQLite DB**: Stores feedback locally without the need for cloud services.

---

## 🛠️ Tech Stack & Architecture

| Layer       | Tools Used                    |
|-------------|-------------------------------|
| Frontend    | HTML, CSS, JavaScript (inline)|
| Backend     | Python, Flask                 |
| AI Model    | Hugging Face Transformers     |
| Database    | SQLite                        |

### 🔁 Application Flow

1. User sends a message via the chat interface.
2. Flask receives the message and calls a Hugging Face model via `new.py`.
3. The model response is rendered back to the frontend.
4. Users can rate the experience via a feedback form (`feedback.html`).
5. Feedback is saved locally into `feedback.db`.

---

## 🚀 Getting Started

Follow these steps to run Nova locally.

###  Prerequisites

- Python 3.7+
- `pip` (Python package manager)

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/nova.git
   cd nova


2. **Create a Virtual Environment (optional but recommended)**:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate


3. **Install Requirements**:
    ```bash
    pip install -r requirements.txt

4. **Run** :
     ```bash
     python app.py
5. **Open your browser at: http://127.0.0.1:5000**


## 🛤️ Roadmap & Ideas

- Add support for model switching (multiple LLMs)
- Improve UX with streaming responses or animations
- Add admin dashboard to review feedback
- Optional cloud deployment via Hugging Face Spaces or Render

---

## 🤝 How to Contribute

Whether you're a developer, designer, or just curious — contributions are welcome!

**You Can Help With:**

- 💻 Improving UI/UX  
- 🧠 Enhancing prompt logic or adding NLP features  
- 🐛 Fixing bugs or optimizing code  
- 📝 Improving docs and adding usage guides  

Fork the repo, make your changes, and open a Pull Request 🚀

---

## 📄 License

MIT License. See the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgements

- 🤗 Hugging Face for their amazing open-source models  
- 🌐 Flask team for the simple and powerful web framework  
- 💫 Your curiosity for exploring Nova  
