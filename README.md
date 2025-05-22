# 📱 SocialNetwork - Facebook-like Social Network

A full-featured social networking web app inspired by Facebook. This project includes user authentication, profile management, posts, groups, chat, and notifications. Built with a Go backend using SQLite and a modern JavaScript frontend framework. Docker is used for containerizing both frontend and backend.

---

## 📦 Features

- ✅ User registration and login (with session and cookies)
- ✅ Profile pages with profile picture support
- ✅ Follow/unfollow other users
- ✅ Create and view posts with optional images (JPEG, PNG, GIF)
- ✅ Join and create groups
- ✅ Real-time private chats using WebSockets
- ✅ Notifications for followers, likes, and group activity
- ✅ Fully responsive frontend
- ✅ Database migrations using `golang-migrate`
- ✅ SQLite as the database engine
- ✅ Dockerized deployment

---

## 🛠️ Tech Stack

**Frontend:**
- JavaScript (Vue.js)
- HTML5 & CSS3
- Axios for HTTP requests
- WebSockets for real-time chat

**Backend:**
- Go (Golang)
- net/http or lightweight Go web framework (e.g. Chi, Gin)
- gorilla/sessions for cookie-based sessions
- gorilla/websocket for real-time communication
- SQLite as the database
- golang-migrate for handling migrations

**DevOps:**
- Docker
- Docker Compose
