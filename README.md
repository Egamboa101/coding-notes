# Coding Notes

## Working with Git and Github

### Creating and Cloning my Repository

1. On [Github.com](github.com) create a new repository.
   - Click + button in top right corner> "New Repository"
   - Repository name should be all lower case and dashes for spaces.
2. In the newly created repository in [Github.com](github.com):
   - Click the "SSH" button
   - Click the copy button. This copies an <SSH URL> to your repository.
3. On my desktop in the `Emily Coding Projects` folder right click and select Git Bash Here.
4. In Git bash type the following `git clone <ssh url>` and press enter

### Working with Git Commits

1. Make all the desired edits to my files
2. Open the command terminal in vs code ctrl + `
3. In the terminal type the following commands:
   - `git status` - Checks what files have changed in the editing stage
   - `git commit -m "Summary of changes here"` - Officially track the changes I have made
   - Optional: `git status` - Check that files were tracked
   - `gut push origin main` - Pushed the tracked changes up to GitHub
