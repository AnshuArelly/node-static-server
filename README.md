# 🔥 Mini Static File Server in Node.js (Nginx‑like Fundamentals)

A lightweight static file server built using Node’s core modules — **without Express**.  
This project was created to understand how real web servers (like **Nginx or Apache**) work internally.

### 🎯 Why I built this
Most developers use Express or frameworks without understanding **HTTP servers under the hood**.  
So, I built my own static file server from scratch using:

- `http` → Handle incoming requests  
- `fs` → Read files from disk  
- `path` → Resolve safe absolute paths  
- MIME types → Serve correct content types  
- Custom 404 handler  
- Basic routing logic  

This helped me learn exactly how Nginx serves HTML, CSS, JS, images, etc.



## 🚀 Features
- ✔ Serves static files (`.html`, `.css`, `.js`, `.png`, `.jpg`, etc.)
- ✔ Automatically serves `index.html` for root path (`/`)
- ✔ Custom 404 “file not found” page
- ✔ Correct content-type headers for all files
- ✔ UTF-8 support for text files
- ✔ Graceful error handling
- ✔ Clean server code using native Node modules

- ## 🛠️ Tech Stack
- **Node.js**
- Native modules: `http`, `fs`, `path`
- HTML/CSS/JS (static assets)

---

## ▶️ Running the Project
```bash
node server.js
