Local Development & Git Workflow

This guide explains the basic commands needed to preview your project locally and manage your code using Git.

⸻

1. Start a Local Development Server

python3 -m http.server 8000

Starts a local web server on port 8000, allowing you to preview your project in your browser before making or sharing changes.

⸻

2. Check Your Changes

git status

Displays the current status of your repository, including modified, new, and deleted files. Always run this command first to see what has changed.

⸻

3. Stage Your Changes

git add .

Stages all modified and new files so they are ready to be included in the next commit.

⸻

4. Create a Commit

git commit -m "Your message"

Creates a snapshot of your staged changes. Replace “Your message” with a short, meaningful description of the changes you made.

⸻

5. Push Your Changes

git push

Uploads your committed changes to the remote GitHub repository, making them available to your team.

⸻

6. Create a Pull Request (Optional)

gh pr create

Creates a GitHub Pull Request so your changes can be reviewed and approved before they are merged into the main branch.
