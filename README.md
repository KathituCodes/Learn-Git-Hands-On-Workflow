# Learn-Git-Hands-On-Workflow

# Learn Git: Hands-On Workflow

## 🚀 Project Overview
This project is designed to help you **practice and reinforce your Git workflow skills** by running through a series of essential Git commands. By following the instructions, you'll gain hands-on experience with initializing repositories, staging and committing files, managing commits, and configuring Git settings.

## 🎯 Objective
After learning the basics of Git workflow, this project serves as a practical. You will:
- Execute fundamental Git commands.
- Capture screenshots for each step.
- Push these screenshots to a GitHub repository as proof of completion.

## 📜 Instructions
Follow these steps carefully to complete the project:

1. **Create a new folder** named `learn_git`.
2. **Navigate into the folder** using:
   ```sh
   cd learn_git
   ```
3. **Create a new file** named `third.txt`:
   ```sh
   touch third.txt
   ```
4. **Initialize an empty Git repository**:
   ```sh
   git init
   ```
5. **Add `third.txt` to the staging area**:
   ```sh
   git add third.txt
   ```
6. **Commit the change with a message**:
   ```sh
   git commit -m "adding third.txt"
   ```
7. **Check your commit history**:
   ```sh
   git log
   ```
8. **Create another file** named `fourth.txt`:
   ```sh
   touch fourth.txt
   ```
9. **Add `fourth.txt` to the staging area**:
   ```sh
   git add fourth.txt
   ```
10. **Commit the change with a message**:
    ```sh
    git commit -m "adding fourth.txt"
    ```
11. **Remove `third.txt`**:
    ```sh
    rm third.txt
    ```
12. **Stage this deletion**:
    ```sh
    git add .
    ```
13. **Commit the removal**:
    ```sh
    git commit -m "removing third.txt"
    ```
14. **Check your commit history again**:
    ```sh
    git log
    ```
15. **Change your global settings** to disable pagination when viewing logs:
    ```sh
    git config --global core.pager cat
    ```
16. **List all your global Git configurations**:
    ```sh
    git config --global --list
    ```

## 📸 Submission Requirement
Make sure to take **screenshots** of each step in the process and push them to your GitHub repository as part of your project documentation.



