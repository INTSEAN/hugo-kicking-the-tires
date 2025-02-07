# hugo-kicking-the-tires

Welcome to my first Hugo-powered website! 🚀 Built with **Hugo**, a fast and  
flexible static site generator, this project is part of an assignment to develop
hands-on experience with static site generation and deployment.

The site is built with Go (Golang) and this is my first time making use of
 it in my front-end development journey.

This project includes:

- 🏠 **Home Page** – A welcoming introduction to the site

- 👤 **About Page** – Learn more about me and my background
  
- 📬 **Contact Page** – Reach out and connect with me

---

## 🌍 Errors Log

> 🔗 **[Visit the Website](https://docs.google.com/document/d/1VuPnYZdIjyPaO3etkuSn9U-n8zmApg2fRW9JQy4Lcnw/edit?usp=sharing)**  

---

## 📌 Features

✅ **Built with Hugo** – A powerful static site generator.  
✅ **Minimal & Clean Design** – Focused on readability and user experience.  
✅ **Fully Responsive** – Works seamlessly on desktop and mobile.  
✅ **GitHub Pages Deployment** – Learn how to publish static sites effortlessly.  

---

## 🛠 Installation & Setup

Follow these steps to set up your environment and run the site locally:

### **Part I: Configuring Your Environment**

#### **Step 1: Install Visual Studio Code**

- Download and install **[VS Code](https://code.visualstudio.com/)**.
- Recommended extensions:
  - GitHub Copilot
  - markdownlint
  - Hugo Language Support

#### **Step 2: Install a Package Manager**

- **macOS**: `brew install hugo`
- **Windows**: `winget install Hugo.Hugo.Extended`
- **Linux**: `sudo apt install hugo`

#### **Step 3: Install and Configure Git**

- **macOS**: `brew install git`
- **Windows**: `winget install --id Git.Git -e --source winget`
- **Linux**: `sudo apt install git`

### **Part II: Setting Up Your Project**

#### **Step 1: Clone the Repository**

```sh
 git clone https://github.com/yourusername/hugo-mock-landing-page.git
 cd hugo-mock-landing-page
```

#### **Step 2: Run Hugo Locally**

```sh
 hugo server -D
```

Visit [http://localhost:1313](http://localhost:1313) to preview the site.

---

## 🚀 Deployment

This site will be deployed using **GitHub Pages**. Follow these steps:

1. Initialize a GitHub repository (`hugo-mock-landing-page`).
2. Push your Hugo project to the repository.
3. Enable **GitHub Pages** in the repository settings.

To publish:

```sh

hugo
cd public
git add .
git commit -m "Deploy site"
git push origin main
```

---

## 🛠 Troubleshooting & Errors Log

### **Initial Process**

I tried to install Hugo with the command:

```sh
brew install hugo
```

After downloading **36%** of the Hugo package, I encountered errors:

### **Errors Encountered**

1. **Unexpected method 'appcast' called on Cask adoptopenjdk8**
   - This error suggested checking Homebrew’s documentation and updating the cask.
2. **Curl: (56) Recv failure: Connection reset by peer**
   - This occurred while downloading Hugo, stopping the process at **34.6%**.

### **Resolution Attempts**

1. **Searched for solutions online** – Used ChatGPT to confirm the latest fixes.
2. **Reinstalled Hugo** – Attempted `brew install hugo` again, but the error persisted.
3. **Changed Terminal** – Noticed I was running the command in **Visual Studio Code’s integrated terminal** instead of the **macOS Terminal app**.
4. **Ran the command in Terminal App** – Successfully installed Hugo without issues.

#### **Key Takeaways**

- Running **Homebrew commands** in **VS Code’s terminal** can sometimes cause issues.
- When encountering errors, **checking the installation environment** is important.
- Switching to the **native Terminal app** resolved my issue instantly.

---

## 🎯 Achieved Learning Objectives

✔ Learn to configure development environments.  
✔ Gain experience working with static site generators.  
✔ Understand how to manage repositories and version control.  
✔ Publish and host static sites using GitHub Pages.  
✔ Work publicly and build a portfolio showcasing your skills.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify it!

---

## 📞 Contact

📧 **Email:** [seanovan@seas.upenn.edu](seanovan@seas.upenn.edu)
🐦 **Twitter:** [@yourhandle](https://x.com/SeanDonovan04)  
🔗 **LinkedIn:** [Your Profile](https://linkedin.com/in/seandonovan-upenn)

~ Building together 🚀
