**Week 1 : Linux Basics**

1. Create a directory structure on Linux:

   * Create a folder named projects.
     ```
     mkdir projects
     ```
   * Inside projects, create subfolders: week1, week2.
   * ```
     cd projects
     mkdir week1 week2
     ```
2. Use Linux commands to:

   * Create an empty file named hello.txt inside week1.
   * ```
     cd week1
     touch hello.txt

     ```
   * Copy hello.txt to week2 and rename it to hello_copy.txt.
   * ```
     cp hello.txt week2/hello_copy.txt
     ```
   * Delete the original hello.txt from week1.
   * ```
     rm hello.txt
     ```
3. Write a short paragraph in a text file (about_me.txt) using a command-line text editor vim, describing your motivation for learning Node.js.

   ```
   touch about_me.txt
   vim about_me.txt
   ```
   **Week2 : Git and GitHub:**

   1. Initialize a Git repository:
      * Navigate to your projects folder from Week 1.

        ```
        pwd
        cd weel1
        ```
      * Initialize it as a Git repository (git init).

        ```
        git init
        ```
   2. Add and commit files:
      * Add all files to the staging area (git add .).
        ```
        git add .
        ```
      * Commit the files with a meaningful message (git commit -m “Initial commit”).
        ```
        git commit -m 'my first cmment'
        ```
   3. Push to GitHub:
      * Create a repository on GitHub named my-first-project.
      * 
      * Link the local repository to the remote (git remote add origin `<repository-url>`).

        ```
        git remote -v
        git remote add origin https://github.com/ajiwunmi/my-first-project.git
        ```
      * Push your changes to GitHub (git push -u origin main).

        ```
        git push -u oring main
        ```
   4. Practice cloning:
      * Clone your my-first-project repository to a new folder on your machine.

        ```
        git clone https://github.com/ajiwunmi/my-first-project.git
        ```
   5. Modify and push:
      * Add a new file named goals.txt listing your programming goals.

        ```
        touch goals.txt

        ```
      * Commit and push the changes to GitHub.

        ```
        git add .
        git commit -m "new file adeed"
        git push -u origin main
        ```
