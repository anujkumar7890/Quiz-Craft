# Quizz Craft

Quizz Craft is an advanced, AI-driven quiz platform that generates quizzes from various prompts. Our innovative solution seamlessly extracts questions from PDFs and creates ready-to-use quizzes for educators, students, and professionals.

---

## Features

- **AI-Powered Quiz Generation:** Create quizzes from text prompts or PDF documents using OpenAI or Gemini APIs.
- **PDF to Quiz:** Automatically extract questions from PDF files.
- **Multiple Quiz Modes:** Supports different quiz formats and review modes.
- **User-Friendly Interface:** Clean, responsive UI for easy quiz creation and participation.

---

## Directory Structure

- **public/**  
  Contains all static assets (images, CSS, JS) served to the client.
  - `asset/img/` - Logos, illustrations, icons, and images.
  - `css/` - Stylesheets for various pages and components.
  - `js/` - Client-side JavaScript for interactivity.

---

## Installation

1. **Clone the repository:**
   ```
   git clone <repository-url>
   cd Quizz-Craft
   ```

2. **Install dependencies:**
   ```
   npm install
   ```

---

## Environment Variables

Create a `.env` file in the root directory and add the following variables:

```
GEMINIAPIKEY=Paste Gemini API Key here
OPENAIAPIKEY=Paste OpenAI API Key here
DB=Paste MongoDB server URL here
PORT=3000
```

- `GEMINIAPIKEY` - Your Gemini API key (optional, if using Gemini).
- `OPENAIAPIKEY` - Your OpenAI API key (optional, if using OpenAI).
- `DB` - MongoDB connection string.
- `PORT` - Port number for the server (default: 3000).

---

## Usage

1. **Start the server:**
   ```
   npm start
   ```
2. **Open your browser and visit:**  
   [http://localhost:3000](http://localhost:3000)

---

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## License

This project is licensed under the MIT License.

---