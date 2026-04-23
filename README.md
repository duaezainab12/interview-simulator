
# 🎯 AI Interview Simulator

A real-time AI-powered interview practice tool that generates personalized interview questions and gives instant scored feedback — built with HTML, CSS, JavaScript, and the Anthropic Claude API.

---

## ✨ Features

- 🤖 **AI-generated questions** — unique questions every session, no repeats
- 📊 **Instant scored feedback** — score out of 10 with strengths, improvements & a pro tip
- 🎭 **4 role types** — Software Engineer, Product Manager, Data Scientist, UX Designer
- 📈 **3 experience levels** — Junior, Mid-level, Senior
- 🔀 **4 interview focuses** — Behavioral, Technical, Mixed, Culture Fit
- 🏁 **Results dashboard** — full breakdown with average score, best score & per-question ratings
- 🌗 **Dark/light mode** — fully adaptive UI

---

## 🖥️ Demo

> Coming soon — deploy your own using the steps below

---

## 🚀 Getting Started

### Prerequisites

- A modern web browser
- An [Anthropic API key](https://console.anthropic.com/)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/ai-interview-simulator.git
   cd ai-interview-simulator
   ```

2. **Add your API key**

   Open `index.html` and find this line:
   ```js
   headers: { 'Content-Type': 'application/json' }
   ```
   Add your key:
   ```js
   headers: {
     'Content-Type': 'application/json',
     'x-api-key': 'YOUR_ANTHROPIC_API_KEY',
     'anthropic-version': '2023-06-01'
   }
   ```

3. **Open in browser**
   ```bash
   open index.html
   ```
   Or just double-click the file.

---

## 🌐 Deploy on GitHub Pages

1. Push your code to GitHub
2. Go to **Settings → Pages**
3. Set source to `main` branch
4. Your app will be live at:
   ```
   https://YOUR_USERNAME.github.io/ai-interview-simulator
   ```

> ⚠️ **Security note:** Never expose your API key in a public repository. For production, move API calls to a backend server (Node.js, Python, etc.) and store the key in environment variables.

---

## 📁 Project Structure

```
ai-interview-simulator/
├── index.html       # Main app (HTML + CSS + JS in one file)
└── README.md        # You are here
```

---

## 🛠️ Built With

- **HTML / CSS / JavaScript** — no frameworks, no build tools
- **[Claude API](https://www.anthropic.com/)** — Anthropic's claude-sonnet model for question generation and feedback
- **Google Fonts** — Playfair Display + DM Sans

---

## 📸 Screenshots

> Add screenshots here after deployment

---

## 🤝 Contributing

Pull requests are welcome! Here are some ideas to extend the project:

- Add voice input support
- Save session history to localStorage
- Add more role types (Marketing, Sales, Finance)
- Add a timer per question
- Export results as PDF

---

## 📄 License

MIT License — free to use, modify and distribute.

---

## 👤 Author

**Your Name**
- GitHub: [@YOUR_USERNAME](https://github.com/YOUR_USERNAME)

---

> Built with ❤️ using Claude AI
