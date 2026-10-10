# Assignment 01 Solutions - Software Engineering

**Student Name:** Areesha Tasawar  
**Degree:** Bachelor of Science in Software Engineering (5th Semester)  
**Institution:** Fatima Jinnah Women University (FJWU)  

---

## Task 1: Install Gitea and Push a Repository from the Ubuntu Server
- **Step 1.1:** Installed Docker Engine, curl, and Docker Compose plug-in on the Ubuntu server.
- **Step 1.2:** Cloned the Gitea setup repository and started Gitea and PostgreSQL using Docker Compose.
- **Verification:** Confirmed containers are running and verified local Gitea HTTP status (200).
- **Screenshot Reference:** `screenshots/task1_gitea_running.png`, `screenshots/task1_gitea_push.png`, `screenshots/task1_gitea_repository.png`

---

## Task 2: Multi-Remote Git Repository Management
- **Step 2.1:** Configured dual remotes on the Ubuntu server repository to push simultaneously to both Gitea and GitHub.
- **Verification:** Verified remote URLs using `git remote -v`.
- **Screenshot Reference:** `screenshots/task2_remotes.png`, `screenshots/task2_github_push.png`, `screenshots/task2_github_repository.png`

---

## Task 3: Git Large File Storage (LFS) Implementation
- **Step 3.1:** Initialized Git LFS on the server repository.
- **Step 3.2:** Configured LFS tracking for large binary (`.bin`) files and pushed successfully.
- **Screenshot Reference:** `screenshots/task3_lfs_setup.png`, `screenshots/task3_lfs_files.png`, `screenshots/task3_lfs_push.png`

---

## Task 4: Create a Portfolio or CV with GitHub Pages
- **Step 4.1:** Created a public GitHub repository named `areesha-tasawar.github.io` containing `index.html` and `styles.css` with sections: About Me, Education, Skills, and Projects.
- **Step 4.2:** Enabled GitHub Pages deployment under repository settings (`main` branch and root folder).
- **Step 4.3:** Verified the live portfolio website hosted on GitHub Pages.
- **Screenshot Reference:** `screenshots/task4_pages_repository.png`, `screenshots/task4_pages_deployment.png`, `screenshots/task4_portfolio_live.png`
