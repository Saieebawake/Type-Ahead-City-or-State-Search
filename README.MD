# 🔍 Type Ahead Search

A simple **Type Ahead Search** project built using HTML, CSS, and JavaScript. The application allows users to search for cities or states and displays matching results along with their population.

## 📌 About the Project

This project demonstrates how JavaScript can be used to create a dynamic search experience. As the user types in the search box, matching cities and states are filtered from a dataset and displayed instantly.

The matching text is also highlighted to make the results easier to identify.

## ✨ Features

- Search for cities or states
- Displays matching results dynamically
- Shows population of each city
- Highlights the searched text
- Real-time search as the user types
- Uses external JSON data

## 🛠️ Tech Stack

- HTML5
- CSS3
- JavaScript
- Fetch API
- JSON

## 📂 Project Structure

```text
Type-Ahead/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

## ⚙️ How It Works

- City data is fetched from an external JSON dataset using the `fetch()` API.
- The data is stored in a JavaScript array.
- When the user enters a search term, the application filters the dataset for matching city or state names.
- Matching results are displayed dynamically on the page.
- Regular Expressions are used to find and highlight the searched text.
- The population of each matching city is displayed alongside the result.

## 🧠 Concepts Practiced

- Fetch API
- Promises
- JSON data
- DOM manipulation
- Event listeners
- Array methods
- `.filter()`
- `.map()`
- Regular Expressions
- Template literals
- String methods
- Dynamic HTML rendering

## 📚 Data Source

The project uses a public `cities.json` dataset containing city, state, and population information.

## 🎯 Learning Outcome

This project helped me understand how to work with external JSON data and use JavaScript to build a dynamic search interface.

It also strengthened my understanding of **DOM manipulation, array methods, Regular Expressions, event handling, and the Fetch API**.

## 🔮 Future Improvements

- Add keyboard navigation for search suggestions
- Add a "No results found" message
- Improve mobile responsiveness
- Add search result sorting
- Add debounce for optimized searching

## 👩‍💻 Author

**Saiee Bawake**

Frontend Development Practice Project