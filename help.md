## Connect Your GitHub Credentials to VSCode

1. **Install the GitHub Pull Requests and Issues Extension**:

   - Open VSCode and click on the extensions panel.
   - Search for "GitHub Pull Requests and Issues".
   - Install the extension.

2. **Authenticate with GitHub**:

   - Once you've installed the GitHub Pull Requests and Issues extension, you'll need to sign in.
   - Follow Getting Started in GitHub Pull Requests

   OR

   - Follow the prompts to authenticate with GitHub in the browser and return to VSCode.
   - If you are not redirected to VSCode, you can add your authorization token manually.

3. **Add Your Authorization Token Manually**:

   - In the browser window, you will receive your authorization token.
   - Copy the token, and switch back to VSCode.
   - Select "Signing in to github.com..." in the Status bar, paste the token, and hit Enter.

4. **Verify Your GitHub Connection**:
   - You can click on the Profile icon at the bottom left corner to see if it says you are logged in to your GitHub account.

Now, you should be able to clone a repository from GitHub using the Git: Clone command in the Command Palette (Ctrl + Shift + P) or by using the Clone Repository button in the Source Control view.

# React JS App Creation and GitHub Connection Tutorial

## 1. Set Up Your Development Environment

- Install **Node.js** and **npm** (comes with Node.js).
- Install **Visual Studio Code** (VSCode).
- Install VSCode extensions for React development: ESLint, Prettier, Reactjs code snippets.

## 2. Create Your React App

- Open VSCode and create a new folder for your project.
- Open a terminal in VSCode and run:

npx create-react-app my-app

- This creates a new React application named `my-app`.

## 3. Run Your React App

- Navigate to your project folder in the terminal and start the app:

cd my-app

npm start

- Your default web browser should open with your running React app.

## 4. Connect to GitHub

- Install the GitHub Pull Requests and Issues extension.
- Authenticate with GitHub.
- Add your authorization token manually.
- Verify your GitHub connection.
- Initialize a new Git repository in your project folder:

git init

- Add all your project files to the repository:

git add .

- Commit the changes:

git commit -m "Initial commit"

- Create a branch main

git branch -M main

- Create a new repository on GitHub and copy its URL (your-github-repo-url)

Note: Can follow Quick Start after create new repository on GitHub

OR

- Link your local repository to the GitHub repository:

Repalce your-github-repo-url and run this command:

git remote add origin your-github-repo-url

- Push your code to GitHub:

git push -u origin main

- When adding new file, help.md for example

git add help.md
git commit -m "new file" --> "new file" is athe message
git push origin main

- Check your GitHub, help.md should be there

## Additional Resources

- React JS Tutorial #1 - Setup React in VSCode & 'Hello World' by Max on Tech.
- How to run React JS app in Visual Studio code tutorial | Download and install react in VS Code 2024 by United Top Tech.
- First React app using create-react-app | VS code | npx | npm by Code With Arjun.

Replace `<your-github-repo-url>` with the actual URL of your GitHub repository when pushing your code.

You can save this content into a .md file using any text editor. When you view this file on a platform that supports Markdown rendering, such as GitHub, it will display with the proper formatting. Happy coding! 🚀

Helpful videos:

https://www.youtube.com/watch?v=LdSwWxVzUpo&ab_channel=VisualStudioCode

https://www.youtube.com/watch?v=VWbHiXN3mno&ab_channel=Bald.Bearded.Builder.

Quick summary:

First create a new repository on GitHub. Copy the link of the repository.

In vscode project terminal, run:

1. git init
2. git remote add origin [copy and paste link here]
3. git branch -M main
4. Go to source control on the sidebar of VSCode, then stage the file, write a commit message, then commit.
5. git push -u origin main, or if you are still inside source control, press the push button below your commit.
