
📝 GitHub Cheat Sheet for Local Repo Management

This section contains essential commands to manage your local repo and push changes to GitHub.

1️⃣ Clone a Repository

Use this to get a copy of a GitHub repo on your local machine:

# Using HTTPS
git clone https://github.com/username/repo-name.git

# Using SSH
git clone git@github.com:username/repo-name.git

2️⃣ Check Status

Check which files are changed, staged, or untracked:

git status

3️⃣ Stage Changes

Stage all changes:

git add .


Stage specific files:

git add filename.ext

4️⃣ Commit Changes

Record your changes locally:

git commit -m "Describe your changes here"

5️⃣ Push Changes

Send your committed changes to GitHub:

git push origin main


Replace main with your branch name if it’s different (master or any feature branch).

6️⃣ Quick One-Line Push

For convenience, you can run everything in one line after editing:

git add . && git commit -m "Your commit message" && git push origin main

7️⃣ Pull Changes (Optional)

If your repo has updates on GitHub that you don’t have locally:

git pull origin main

✅ Notes

Always check your branch name (git branch) before pushing.

Use descriptive commit messages for easier tracking.

You can copy this section anywhere for quick reference.