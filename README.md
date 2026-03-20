# 🚀 GitHub Pages Deployment with GitHub Actions

## 📌 Project Overview

This project demonstrates how to use **GitHub Actions** to automatically deploy a static website to **GitHub Pages**. It is a simple implementation of **Continuous Integration (CI)** and **Continuous Deployment (CD)** using a single HTML file.

The workflow ensures that any changes made specifically to the `index.html` file are automatically deployed to a live website.

---

## 🔗 Project Reference

This project is based on the official DevOps roadmap challenge:
https://roadmap.sh/projects/github-actions-deployment-workflow

---

## 🎯 Objectives

* Understand the basics of **GitHub Actions**
* Learn how to configure **CI/CD pipelines**
* Automate deployment to **GitHub Pages**
* Practice writing workflow files using YAML

---

## 🛠️ Tech Stack

* **HTML5** – Static website
* **GitHub Actions** – CI/CD automation
* **GitHub Pages** – Hosting platform

---

## 📂 Project Structure

```
gh-deployment-workflow/
│
├── index.html
├── README.md
└── .github/
    └── workflows/
        └── deploy.yml
```

---

## ⚙️ How It Works

1. A change is pushed to the `main` branch
2. GitHub Actions checks if `index.html` was modified
3. If true, the workflow is triggered
4. The updated site is deployed to GitHub Pages
5. The live site updates automatically

---

## 🔄 Workflow Trigger

The deployment workflow runs only when:

* A push is made to the `main` branch
* The `index.html` file is modified

---

## 🌐 Live Demo

Once deployed, the website will be available at:

```
https://<your-username>.github.io/gh-deployment-workflow/
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/<your-username>/gh-deployment-workflow.git
cd gh-deployment-workflow
```

### 2. Make changes

Edit the `index.html` file.

### 3. Push changes

```bash
git add .
git commit -m "Update index.html"
git push origin main
```

### 4. Watch deployment

Go to the **Actions tab** on GitHub to see the workflow run.

---

## 📄 Example HTML

```html
<!DOCTYPE html>
<html>
<head>
  <title>GitHub Actions Demo</title>
</head>
<body>
  <h1>Hello, GitHub Actions!</h1>
</body>
</html>
```

---

## 🧠 Key Concepts Learned

* Continuous Integration (CI)
* Continuous Deployment (CD)
* Workflow automation
* Event-based triggers in GitHub Actions

---

## 📌 Future Improvements

* Add a CSS-styled UI
* Integrate a static site generator (e.g., Jekyll, Hugo, Astro)
* Deploy a personal portfolio website
* Add automated testing before deployment

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository and submit a pull request.

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 👤 Author

**FG Okeke**
DevOps & Cloud Engineering Enthusiast

---

## ⭐ Acknowledgements

* GitHub Documentation
* DevOps learning community
* Open-source contributors
