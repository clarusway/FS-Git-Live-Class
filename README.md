# Scenario: Collaborative Web Development Project

## Background - Updated:

You and your classmates are working on a collaborative web development project to create a simple website. The project is hosted on a Git repository. Each student will be responsible for a specific feature or page on the website.

## Tasks:

1. **Clone the Repository:**

   - Each student should open a terminal on their computer.

   - Navigate to the directory where you want to store the project.

   - Clone the project repository:

     ```bash
     git clone https://github.com/clarusway/FS-Git-Live-Class.git
     ```

2. **Create a Feature Branch:**

   - Navigate into the project directory:

     ```bash
     cd FS-Git-Live-Class/
     ```

   - Create a new branch for your feature (e.g., "feature-barry"):

     ```bash
     git branch feature-barry
     ```

   - Switch to your new branch:

     ```bash
     git checkout feature-barry
     ```

   Alternatively, combine the above two commands:

   ```bash
   git checkout -b feature-barry
   ```

3. **Make Changes to Your Feature:**

   - Create a file with your name such as barry.txt
   - Open an editor and add some text into this file and save the file.

4. **Stage and Commit Your Changes:**

   - Stage your changes:

     ```bash
     git add .
     ```

   - Commit your changes with a meaningful message:

     ```bash
     git commit -m "Add barry feature"
     ```

5. **Push Your Branch to the Remote Repository:**

   - Push your branch to the remote repository:

     ```bash
     git push origin feature-barry
     ```

6. **Create a Pull Request:**

   - Visit the project repository on GitHub in your web browser.
   - Click on the "Pull requests" tab.
   - Click the "New pull request" button.
   - Select your feature branch as the "compare" branch and the main branch as the "base" branch.
   - Create the pull request with a meaningful title and description.

7. **Review and Merge:**

   - Senior developer or github admin should review your pull request and provide feedback.
   - After addressing any feedback, the project manager (instructor) can merge your pull request into the main branch.

8. **Update Local Repository:**

   - Once your pull request is merged, update your local repository:

     ```bash
     git checkout main
     git pull origin main
     ```
# git-lab
