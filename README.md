
# 📝 Simple Notes App

A simple full-stack Notes App built with **React (frontend)** and **Spring Boot (backend)**.  
The app supports **CRUD operations**: Create, Read, Update, and Delete notes.  

---

## 📂 Repository Structure

- **[notes-app-backend]([../notes-app-backend](https://github.com/DeepankSingh/notes-app-backend))** → Spring Boot backend code  
- **[notes-app-frontend]([../notes-app-frontend](https://github.com/DeepankSingh/notes-app-frontend))** → React frontend code  
- **[mono-repo (this repo)](https://github.com/DeepankSingh/SimpleNotes)** → Documentation and links  

---

## 🚀 Live Demo

- **Frontend (Netlify)** → [Click Here](https://your-netlify-link)  
- **Backend (Render)** → [Click Here](https://your-render-link)  

---

## ⚙️ Features

- Add a new note (title + content)  
- View all notes  
- Edit existing notes  
- Delete notes  
- Responsive, minimal UI  

---

## 📡 API Endpoints (Backend)

Base URL → `https://render-link/api/notes`

| Method | Endpoint         | Description          | Request Body               |
|--------|-----------------|----------------------|----------------------------|
| GET    | `/api/notes`    | Fetch all notes      | –                          |
| POST   | `/api/notes`    | Create new note      | `{ "title": "", "content": "" }` |
| PUT    | `/api/notes/{id}` | Update a note       | `{ "title": "", "content": "" }` |
| DELETE | `/api/notes/{id}` | Delete a note       | –                          |

---

## 🛠️ Tech Stack

- **Frontend** → React, Axios, TailwindCSS  
- **Backend** → Spring Boot, REST API  
- **Database** → PostgreSQL (or H2 for testing)  
- **Deployment** → Netlify (frontend), Render (backend)  

---

## 📖 How to Run Locally

### Backend
```bash
git clone https://github.com/DeepankSingh/notes-app-backend.git
cd notes-app-backend
./mvnw spring-boot:run
````

### Frontend

```bash
git clone https://github.com/DeepankSingh/notes-app-frontend.git
cd notes-app-frontend
npm install
npm start
```

---

## 👨‍💻 Author

Developed by **Deepank Singh**.

```

