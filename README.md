# 🎬 NODE_CRUD_API_PROJECT

A simple Node.js-based REST API that allows you to **Add**, **Update**, **Delete**, and **Search** movies using in-memory data stored in a JSON file (`movies.json`). Built using core modules like `http`, `fs`, `path`, and `url` — no external frameworks like Express used!

---

## 🚀 Features

- ✅ Add a movie
- ✅ Get all movies
- ✅ Get a single movie by ID
- ✅ Update a movie by ID
- ✅ Delete a movie by ID
- ✅ Search/filter movies by name or genre

---

## 📦 Technologies Used

- **Node.js Core Modules**
  - `http` – to create the server
  - `fs` – to read/write movie data
  - `path` – for file path handling
  - `url` – to parse incoming request URLs
  - `crypto` – to generate unique IDs

---

## 🧪 API Endpoints

| Method | Endpoint              | Description            |
|--------|-----------------------|------------------------|
| GET    | `/api/movies`         | Get all movies         |
| GET    | `/api/movies/:id`     | Get a movie by ID      |
| POST   | `/api/movies`         | Add a new movie        |
| PUT    | `/api/movies/:id`     | Update a movie         |
| DELETE | `/api/movies/:id`     | Delete a movie         |

> All requests and responses are in `application/json` format.





