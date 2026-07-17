# 🧠 NeuronIQ – AI Study Assistant

NeuronIQ is an AI-powered study assistant that transforms lengthy notes into structured learning material within seconds. Simply paste your notes, and the application generates concise summaries, interactive flashcards, and quizzes to make studying faster and more effective.

---

## ✨ Features

- 📄 AI-generated study summaries
- 🧠 Interactive flashcards for quick revision
- ❓ Automatically generated quizzes
- ⚡ Fast and responsive user interface
- 🎨 Modern dark-themed dashboard
- 📱 Fully responsive design

---

## 🛠️ Tech Stack

### Frontend
- React
- Vite
- CSS3
- JavaScript (ES6)

### Backend
- Node.js
- Express.js

### AI
- OpenRouter API
- Google Gemini API (Fallback)

---

## 📂 Project Structure

```
NeuronIQ/
│
├── client/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/
│   ├── src/
│   ├── routes/
│   ├── services/
│   ├── .env
│   └── package.json
│
└── README.md
```

---

## 🚀 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/uditanshu01/NeuronIQ.git
```

```bash
cd NeuronIQ
```

---

### 2. Install Dependencies

#### Client

```bash
cd client
npm install
```

#### Server

```bash
cd ../server
npm install
```

---

## ⚙️ Environment Variables

Create a `.env` file inside the **server** directory.

```env
OPENROUTER_API_KEY=your_openrouter_api_key
OPENROUTER_MODEL=google/gemini-2.5-flash

GEMINI_API_KEY=your_gemini_api_key

PORT=8000

CLIENT_ORIGIN=http://localhost:5173
```

---

## ▶️ Running the Application

### Start Backend

```bash
cd server
npm run dev
```

### Start Frontend

```bash
cd client
npm run dev
```

Visit:

```
http://localhost:5173
```

---

## 📸 Preview

- AI Notes Generator
- Smart Study Summary
- Interactive Flashcards
- Practice Quiz

---

## 📈 Future Improvements

- User Authentication
- Study History
- PDF Upload Support
- Export Notes as PDF
- Multiple AI Model Support
- Progress Tracking
- Dark/Light Theme Toggle

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create your feature branch

```bash
git checkout -b feature/NewFeature
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push to the branch

```bash
git push origin feature/NewFeature
```

5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub to support future development.

---

Made with ❤️ using React, Node.js, Express, and AI.
