# 📖 Cozy Book Journal

A full stack book tracking web app built with Django REST Framework and Vanilla JavaScript.  
Users can create accounts, log in, and manage their personal reading lists — all with their data securely stored in the backend.

## ✨ Features

- 🔐 User registration and login with JWT authentication
- 📚 Add books with title, author, notes, star rating and cover image
- 📋 Organise books into three lists: To Be Read, Currently Reading, and Finished
- 🔄 Update a book's status from any list
- 🗑️ Delete books
- 📊 Stats page showing totals, average rating, top rated and recently added books
- 🔒 Each user only sees their own books (private data per account)
- 🔁 Auto token refresh — stays logged in for 7 days

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | HTML, CSS, Vanilla JavaScript |
| Backend | Python, Django, Django REST Framework |
| Authentication | JWT via djangorestframework-simplejwt |
| Database | SQLite |
| CORS | django-cors-headers |

## 💡 Why I built this

I wanted to challenge myself beyond front-end projects and learn how a real application works end-to-end — from the database and API, all the way through to the user interface. This project taught me how frontend and backend communicate, how to secure routes with authentication, and how to structure a full stack project properly.

## 🚀 How to Run Locally

### 1. Clone the repository
```bash
git clone https://github.com/LynellGovender/Cozy-book-journal.git
cd Cozy-book-journal
```

### 2. Install backend dependencies
```bash
cd backend
pip install -r requirements.txt
```

### 3. Set up the database
```bash
python manage.py makemigrations books
python manage.py migrate
```

### 4. Start the backend server
```bash
python manage.py runserver
```

### 5. Open the frontend
Open `frontend/index.html` with VS Code Live Server at `http://127.0.0.1:5500`

## 🔌 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/api/auth/register/` | Create a new account |
| POST | `/api/auth/login/` | Login and receive JWT tokens |
| POST | `/api/auth/refresh/` | Refresh access token |
| GET | `/api/books/` | Get all your books |
| GET | `/api/books/?status=TBR` | Filter books by status |
| POST | `/api/books/` | Add a new book |
| PATCH | `/api/books/<id>/` | Update a book |
| DELETE | `/api/books/<id>/` | Delete a book |
| GET | `/api/stats/` | Get your reading statistics |

## 👩‍💻 Author
**Lynell Govender** — [GitHub](https://github.com/LynellGovender)

# Quest Logbook 📖

An interactive web app where users can create, track, and complete personal quests or goals — think of it as a to-do list with a fun twist.

## 🔍 What it does

- Add a new quest with a title and description
- View all your active quests in one place
- Mark quests as completed
- Track your progress over time
- Clean, aesthetic UI that works directly in the browser — no install needed

## 💡 Why I built this

I wanted to build something more interactive than a static website. This project helped me practice JavaScript DOM manipulation, event handling, and dynamic content updates.

## 🛠️ Built With

![HTML](https://img.shields.io/badge/HTML5-E34C26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-264DE4?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F0DB4F?style=flat&logo=javascript&logoColor=black)

## 🚀 How to run it

1. Clone or download this repository
2. Open `index.html` in your browser
3. Start adding quests!

## 📚 What I learned

- JavaScript event listeners and DOM manipulation
- Dynamically creating and removing HTML elements with JS
- Structuring a project with separate HTML, CSS, and JS files

- # Calculator App 🧮

A clean, fully functional calculator built from scratch using HTML, CSS, and JavaScript.

## 🔍 What it does

- Performs addition, subtraction, multiplication, and division
- Handles decimal numbers
- Clear button to reset the display
- Responsive layout that works on desktop and mobile

## 💡 Why I built this

The calculator is a classic beginner project — it forces you to think through logic, handle edge cases, and connect a UI to real functionality with JavaScript.

## 🛠️ Built With

![HTML](https://img.shields.io/badge/HTML5-E34C26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-264DE4?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F0DB4F?style=flat&logo=javascript&logoColor=black)

## 🚀 How to run it

1. Clone or download this repository
2. Open `index.html` in your browser
3. Start calculating!

## 📚 What I learned

- JavaScript functions and conditional logic
- Handling user input and button click events
- Building a grid layout with CSS

  # My Superhero App 🦸

A multi-page website showcasing Marvel superheroes — their powers, backstory, and personal details.

## 🔍 What it does

- Displays a gallery of Marvel characters on the homepage
- Click any hero to view their individual detail page
- Each page includes name, abilities, and background info
- Includes an About page and Contact page

## 💡 Why I built this

This was my first multi-page website project. I wanted to practice linking multiple HTML pages together, structuring content, and styling with CSS.

## 🛠️ Built With

![HTML](https://img.shields.io/badge/HTML5-E34C26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-264DE4?style=flat&logo=css3&logoColor=white)

## 🚀 How to run it

1. Clone or download this repository
2. Open `index.html` in your browser
3. Click on any superhero to explore!

## 📚 What I learned

- Structuring a multi-page HTML website
- CSS styling and layout with classes
- Linking between pages and embedding images

  # Pinecity Zoo 🦁

A website for a fictional zoo that showcases the animals and different areas of the zoo.

## 🔍 What it does

- Displays different zoo sections and animal exhibits
- Clean layout with images and descriptive content
- Easy to navigate between sections

## 💡 Why I built this

I used this project to practice building a real-world style website — the kind a small business or organisation might actually use.

## 🛠️ Built With

![HTML](https://img.shields.io/badge/HTML5-E34C26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-264DE4?style=flat&logo=css3&logoColor=white)

## 🚀 How to run it

1. Clone or download this repository
2. Open `index.html` in your browser

## 📚 What I learned

- Page layout and content structure with HTML
- Styling sections and images with CSS
- Designing a site that feels like a real product

<!--
**LynellGovender/LynellGovender** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
