# 🚀 Blog App Backend (GitHub-Powered)

This is a simple **backend for the Android Blogs App**, designed to serve blog data using static files hosted on **GitHub**.

Instead of using a paid or complex backend, we utilize GitHub’s raw file URLs as a **free, version-controlled API-like source**.

> ✅ Perfect for beginners who want to learn how mobile apps can interact with remote data – without setting up a full backend server.

---

## 📁 Project Structure

📦 blog-backend-repo/  
├── blogs/  
│ ├── blog1.md  
│ ├── blog2.md  
│ └── ...other blogs  
├── images/  
│ ├── markdown.jpg  
│ ├── compose.jpg  
│ └── ...other images  
├── blogs.json  
└── README.md  

### ✔️ `blogs/` Folder
Contains all the blog articles in **Markdown format** (`.md` files). Each blog is written in plain Markdown and rendered in the app UI.

### ✔️ `blogs.json`
This is the main metadata file used by the app. It contains an array of blog objects.

---

## 📡 Why This Approach?  
🆓 **Free:** No server costs. GitHub acts as a static file server.  
👶 **Beginner-Friendly:** No backend setup required.  
🚀 **Fast Updates:** Just push to the repo and your blog is live.  
🔒 **Version Control:** Track all blog changes over time.  
🌍 **Accessible:** Raw files can be fetched by any HTTP client.  

---

## 📝 How to Add a New Blog
- Write your blog in Markdown and save it as your-blog.md  
- Add the file inside the /blogs folder  
- Update blogs.json with a new entry:  
- Push your changes to the main branch — your Android app will automatically fetch the new blog 🎉  

---


