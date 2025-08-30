
---

# **MOVIES-GPT App**

**MOVIES-GPT** is an AI-driven platform that enhances the Netflix experience. It leverages **OpenAI's GPT-3.5** model to provide **personalized content recommendations**. This project is designed for Netflix enthusiasts seeking a **more engaging and customized streaming experience**.

It empowers users to:

* Explore content effortlessly
* Engage in natural language interactions
* Gain deeper insights into their favorite shows and movies

Whether you're a seasoned Netflix user or just starting your streaming journey, this app will make your entertainment experience **more enjoyable and enriching**.

---

## **Features**

* **GPT-Search** — AI-powered content search and recommendations
* **Authentication** — Secure login and user management
* **Internationalisation** — Multi-language support
* **TMDB API Integration** — Fetch movies, TV shows, and metadata
* **Memoisation** — Optimized performance for repeated searches

---

## **🎨 Color Reference**

| Color               | Hex       |
| ------------------- | --------- |
| **Primary Color**   | `#E50914` |
| **Secondary Color** | `#0f0d0e` |
| **Accent Color**    | `#fcba28` |
| **Text Color**      | `#ffffff` |

---

## **🔑 Environment Variables**

To run this project, you will need to add the following variables to your `.env` file:

```
VITE_OPENAPI_KEY=your_openai_api_key
VITE_TMDB_KEY=your_tmdb_api_key
VITE_FIRE_BASE_API_KEY=your_firebase_api_key
```

---

## **🧰 Getting Started**

### **‼️ Prerequisites**

* [Install Node.js](https://nodejs.org/) on your computer
* [Setup Firebase](https://firebase.google.com/)
* Get your [OpenAI API key](https://platform.openai.com/)
* Get your [TMDB API key](https://developer.themoviedb.org/)

---

### **🏃 Run Locally**

Clone the project:

```bash
git clone https://github.com/gyandeeparyan/netflix-gpt
```

Go to the project directory:

```bash
cd netflix-gpt
```

Install dependencies:

```bash
npm i
```

Start the development server:

```bash
npm run dev
```

---

## **🚩 Deployment**

To deploy this project using Firebase:

```bash
firebase deploy
```

## **SET-UP Project from my end**

1. Created React+Vite App (npm create vite@latest netmirror)
2. Configure Tailwind-CSS 
3. Configure React Router (npm i -D react-router-dom)
4. Header Component
5. SignIn/Up form
6.


## **Features for the Application**

- Login/SignUp
    - Sign In / Sign Up Form
    - redirect to Browse Page

- Browse (after authentication)
    - Header
    - Main Movie
        - Trailer in Background
        - Title & Description
        - Movie Suggestions
        
- NetMirrorGPT
    - Search Bar
    - Movie Suggestions

---

