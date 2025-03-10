# Git Sandbox Repository

Welcome to the Git Sandbox Repository! 🎉

This repository is a test environment for learning and practicing Git. Use it to clone, modify, pull, and push changes as part of your Git training.

## Getting Started

To begin using this repository, follow these steps:

### 1. Clone the Repository
Copy the repository to your local machine:
```sh
git clone https://github.com/SOAPeople-NessimSaidi/git-introduction.git
cd git-introduction
```

### 2. Create and Switch to a New Branch
Create a new branch for your changes:
```sh
git checkout -b your-name-branch
```

### 3. Modify Files and Stage Changes
Make some changes and prepare them for commit.
This writes a shell output ('echo') into ('>') a file:
```sh
echo "Hello Git!" > hello.txt
git add hello.txt
```

### 4. Commit Your Changes
Save your changes with a descriptive message:
```sh
git commit -m "Added hello.txt with a welcome message"
```

### 5. Push Your Changes to the Remote Repository
Upload your new branch to the repository.
Perform a pull first to get the latest changes. As you just created this branch, 
there will not be a remote version of your branch. But make this a good habit to 
avoid problems while collaborating with others.
```sh
git pull origin your-name-branch
git push origin your-name-branch
```

### 6. Pull Changes from the Remote Repository
Ensure your local repository is up to date:
```sh
git pull origin main
```

### 7. Merge Your Branch (Optional)
If working collaboratively, merge your changes into the main branch:
```sh
git checkout main
git merge your-name-branch
git push origin main
```

### 8. Delete a Branch (Optional)
Once merged, clean up by deleting your branch:
```sh
git branch -d your-name-branch
git push origin --delete my-new-branch
```

## Important Notes
- Always pull the latest changes before pushing your work.
- Use clear commit messages to document what you changed.
- Work in branches to keep the `main` branch clean and stable.
- Have fun experimenting with Git! 🚀

## Need Help?
Refer to the official [Git documentation](https://git-scm.com/doc) or ask your instructor for guidance.

Happy coding! 👩‍💻👨‍💻
