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

## 🔧 Used By
This repository is used as the backend for:  📱 [Android Blogs App](https://github.com/CodeInKotLang/AndroidBlogs)  
A Jetpack Compose app that fetches and displays blogs using this GitHub repo as its content source.

---

## ▶️ Tutorial Playlist

📺 Follow the complete step-by-step playlist to build this app from scratch:

🔗 [Watch on YouTube (15-part series)](https://youtube.com/playlist?list=PL1b73-6UjePBW_toAR1FBCmqPK6UudwMX&si=dIMeVmZhtNcWlgaL)
![Playlist](https://raw.githubusercontent.com/CodeInKotLang/AndroidBlogs/refs/heads/master/readme-assets/playlist.JPG)

# :memo: Author :memo:
- [Mohammad Arif](https://github.com/CodeInKotLang)

Check out my Udemy Courses: 
- 📚 [Android Quiz App: Ktor Backend & Jetpack Compose](https://www.udemy.com/course/quiztime/?referralCode=D1F5E08155303110B7A4)  
- 📚 [Android Fitness App: Firebase & Jetpack Compose](https://www.udemy.com/course/measuremate/?referralCode=B3DE352F96BC3C3E9E80)  
 

<a href="https://ko-fi.com/mohammadarif" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>


Happy learning and building amazing Android apps!
