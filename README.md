# 🎥 Movie Zone

## Overview

**Movie Zone** is a simple and interactive web application that allows users to search for movies, view detailed information, and save their favorite titles. It integrates the **OMDB API** to fetch real-time movie data and stores user preferences using the browser's **localStorage**.

---

## 🚀 Tech Stack

| Technology        | Description                                                                 |
|-------------------|-----------------------------------------------------------------------------|
| **HTML5**         | Markup language used for structuring the app content.                      |
| **CSS3**          | Used for styling the app and ensuring a responsive UI.                     |
| **JavaScript (ES6)** | Handles DOM manipulation, API integration, and localStorage functionality. |
| **OMDB API**      | External API used to fetch movie data based on user search.                |

---

## ✨ Features

- 🔍 **Search Movies**: Search by title using the OMDB API.
- 📄 **View Movie Details**: View key information like poster, plot, release year, and rating.
- ❤️ **Save Favorites**: Save your favorite movies locally using `localStorage`.
- 🗑️ **Remove Favorites**: Dynamically add or remove movies from your favorites list.
- 🔁 **Persistent Storage**: Favorites remain saved even after reloading the page.

---

## 🔧 Installation & Usage

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/moviezone.git
   cd moviezone
   ```

2. **Set up your API Key**
   - Get a free API key from [OMDB API](http://www.omdbapi.com/apikey.aspx).
   - Open the `script.js` file and replace the placeholder with your API key:
     ```js
     const API_KEY = 'your_api_key_here';
     ```

3. **Run the Application**
   - Simply open the `index.html` file in any modern browser:
     ```bash
     open index.html
     ```
   > No server or build tools required – it’s a fully static web application!

---

## 🧩 Folder Structure

```
moviezone/
├── index.html       # Main HTML file
├── style.css        # Stylesheet
├── script.js        # Main JavaScript logic
└── README.md        # Project documentation
```

---

## 📌 Future Improvements

- Add movie categories (e.g., trending, top-rated).
- Implement user login for cross-device favorite sync.
- Add pagination for search results.
- Improve UI/UX with frameworks like Bootstrap or Tailwind CSS.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🙌 Acknowledgments

- [OMDB API](http://www.omdbapi.com/) for providing open movie data.
