# 🎉 git-viewer - Easy Way to Visualize Git Logs

## 📥 Download & Install

[![Download git-viewer](https://img.shields.io/badge/Download%20git--viewer-v1.0.0-blue)](https://github.com/yogesh-cmd/git-viewer/releases)

To get started, you need to download the application. Visit this page to download: [git-viewer Releases](https://github.com/yogesh-cmd/git-viewer/releases).

## 🚀 Getting Started

### Step 1: Install Node.js and Git

To run git-viewer, you must have Node.js and Git installed on your computer. Follow these steps:

1. **Install Node.js**: Go to [Node.js download page](https://nodejs.org/) and choose the version marked "LTS". Download it and follow the installation instructions for your operating system.

2. **Install Git**: Go to [Git download page](https://git-scm.com/downloads) and download the installer for your system. Follow the instructions provided to complete the installation.

### Step 2: Open Your Terminal

After you have installed Node.js and Git, open your terminal. If you are using Windows, search for "Command Prompt" or "PowerShell". If you are on macOS, open "Terminal".

### Step 3: Run git-viewer

You are now ready to run git-viewer. In the terminal, enter the following command:

```bash
pnpm dlx git-viewer [path]
```

Here, replace `[path]` with the path to the directory containing your Git repository. If you want to view the current directory, simply run:

```bash
pnpm dlx git-viewer
```

Once the application starts, open your web browser and go to `http://localhost:44100`.

## 🌟 Usage Examples

- To view the Git logs of the current directory:
```bash
pnpm dlx git-viewer
```

- To view a specific repository located in `~/projects/my-app`:
```bash
pnpm dlx git-viewer ~/projects/my-app
```

## 🔍 Features

- **Branch Graph Visualization**: See a clear layout of your branches.

- **Browse Local and Remote Branches**: Easily navigate through branches.

- **Search Commits**: Find commits based on message, author, or SHA.

- **Diff View with Syntax Highlighting**: Inspect changes in your code.

- **Filter Commits by Branch**: Focus on commits in a particular branch.

## ⚙️ Requirements

- **Node.js**: Version 20 or higher is required.
- **Git**: Make sure you have Git installed on your machine.

## 📂 Exploring the Interface

When you access `http://localhost:44100`, you will see several sections:

1. **Branch Graph**: At the top, view a visual graph of your branches and their relationships.

2. **Commits List**: Below the graph, a list of commits allows you to search or filter for specifics.

3. **Diff Display**: Click on any commit to see detailed changes with highlighted syntax for easy reading.

## 🎓 Additional Tips

- **Stay Updated**: Keep your Node.js and Git versions up to date for the best experience.

- **Learn Git Basics**: Familiarize yourself with basic Git concepts to navigate better.

- **Community Support**: If you face issues or need help, consider joining discussions in Git forums or communities.

## 📃 License

This project is licensed under the MIT License. Feel free to use and modify it as needed.

## 🔗 More Information

For more details, visit the [git-viewer Releases page](https://github.com/yogesh-cmd/git-viewer/releases) to download the latest version and find additional resources. 

Now you are ready to visualize your Git logs with ease. Enjoy using git-viewer!