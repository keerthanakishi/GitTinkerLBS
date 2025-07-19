# 🚀 **GitHub Basics Guide**

Welcome to **GitHub Basics** – your beginner-friendly guide to version control, collaboration, and modern development workflows. This README is styled to be easy to follow and visually appealing.

---

## 📌 **What You'll Learn**

* **What is Git?** A time machine for your projects – track changes, revert mistakes, and collaborate effortlessly.
* **What is GitHub?** A cloud-based home for your Git repositories – like Google Drive, but built for developers.
* **Core Skills:**

  * Install & configure Git.
  * Create repositories & commits.
  * Branching and merging.
  * Forking, cloning, and pull requests.
  * Resolving conflicts and collaborating.

---

## 🔧 **Setup and Installation**

1. **Install Git:**

   * Download from [git-scm.com/downloads](https://git-scm.com/downloads).
   * Follow default installation steps.
   * Verify installation:

     ```bash
     git --version
     ```

2. **Configure Git:**

   ```bash
   git config --global user.name "Your Name"
   git config --global user.email "you@example.com"
   ```

   **Check your details:**

   ```bash
   git config --global user.name
   git config --global user.email
   ```

---

## 📝 **Your First Repository**

1. Log into [GitHub](https://github.com).
2. Click **New Repository** and name it `my-first-repo`.
3. Add a README and click **Create Repository**.
4. Clone it locally:

   ```bash
   git clone <repo-link>
   ```
5. Create a file, commit, and push:

   ```bash
   echo "Hello World" > hello.txt
   git add hello.txt
   git commit -m "My first commit"
   git push origin main
   ```

---

## 🌿 **Branching and Merging**

* Create a new branch:

  ```bash
  git branch feature-1
  git checkout feature-1
  ```
* Merge changes:

  ```bash
  git checkout main
  git merge feature-1
  ```

---

## 🤝 **Collaboration & Pull Requests**

* **Fork** a repository: Make a personal copy on GitHub.
* **Clone** your fork:

  ```bash
  git clone <forked-repo-link>
  ```
* **Pull Request (PR):** Push your changes and click **New Pull Request** to propose updates.
* **Resolve Conflicts:** Use GitHub’s built-in editor or run `git merge` locally.

---

## 🎯 **Quick Activity**

1. Fork a sample repo.
2. Clone it to your computer.
3. Create a new branch, add a file, and commit.
4. Push changes and open a Pull Request.

---

## 🚀 **Next Steps**

* Explore GitHub Issues & Discussions.
* Contribute to open-source projects.
* Host your first site with **GitHub Pages**.

---

> **Tip:** Treat commits like journal entries – small, clear messages that tell the story of your project.

---

**Happy Coding!** ✨
