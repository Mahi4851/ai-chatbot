
# AI ChatBot 🤖

An AI-powered chatbot built using Node.js and OpenAI API that can answer user queries, hold conversations, and deliver a smart chat experience. This project is ideal for learning how to build AI-integrated applications.

---

## 📌 Features

- 💬 AI-powered chat responses using OpenAI GPT
- 🌐 Web-based interface (HTML + JavaScript)
- 🔐 Uses `.env` file to securely store API keys
- 🖥️ Simple Node.js backend
- 🧠 Easily customizable prompts and behaviour

---

## 📁 Project Structure

```
ChatBot/
├── public/
│   └── index.html         # Frontend
├── server.js              # Node.js backend
├── package.json           # Dependencies
├── .env                   # API keys (not uploaded)
├── .gitignore             # Ignore sensitive & unnecessary files
└── README.md              # Project documentation
```

---

## 🛠️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Mahi4851/ai-chatbot.git
cd ai-chatbot
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Set Up Environment Variables

Create a file called `.env` in the root folder and add your OpenAI API key:

```env
OPENAI_API_KEY=your_openai_api_key_here
```

> ⚠️ **Important**: Never commit your `.env` file. It is ignored by `.gitignore`.

---

## 🚀 Run the App

```bash
node server.js
```

Open your browser and go to:  
**http://localhost:3000**

---

## 🧪 Example Prompt

You can ask questions like:

```
- Tell me a joke
- What's the capital of France?
- Explain JavaScript closures
```

---

## 🧩 Technologies Used

- Node.js
- Express
- OpenAI API
- HTML/CSS/JS

---

## ⚠️ Security Note

This project uses OpenAI API keys stored in a `.env` file.  
Never upload `.env` to GitHub or share it publicly.

---

## 📄 License

This project is open source under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

Thanks to OpenAI for providing powerful language models.

---

## 🧑‍💻 Author

- **Name**: Mahi4851
- **GitHub**: [https://github.com/Mahi4851](https://github.com/Mahi4851)
