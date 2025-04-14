# Jenkins Assignment – Module 2

## 📌 Objective
This project demonstrates how to configure a Jenkins pipeline that reads and prints the content of a `hello.txt` file from a GitHub repository to the Jenkins build logs.

---

## 📁 Project Structure
### 1. GitHub Repository Setup
- Created a GitHub repository with the following files:
  - `hello.txt`
  - `Jenkinsfile`
  - `README.md`

### 2. SSH Authentication
- Configured Jenkins to use SSH protocol for accessing the GitHub repository securely.
- Added the SSH public key to GitHub and private key to Jenkins credentials.

### 3. Jenkins Pipeline Job Setup
- Created a **Pipeline Job** in Jenkins named `ReadHelloPipeline`.
- Selected **"GitHub hook trigger for GITScm polling"** as the trigger method.
- In the **Pipeline section**, selected **Pipeline Script** and wrote the script directly in the Jenkins UI.
