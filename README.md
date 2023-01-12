# Fix-GitIgnore-Redemption
Here's a step-by-step guide on how to fix the mistake of not using a `.gitignore` file before uploading files to your repository:
 
 1. Locate a suitable .gitignore file [Here](https://github.com/github/gitignore) and download it .
 2. Add the `.gitignore` file to your repository .
 3. Open Git Bash .
 4. Use the command `cd /path/to/your\ repository` to navigate to your repository's directory. For example: `cd /d/Projects/Git/My\ Git/Magical-Vending-Machine` .
 5. Run the command `git rm -r --cached .` .
 6. Run the command  `git add .` .
 7. Run the command `git commit -m "Drop files from .gitignore"` .
 
 Note: If you have a folder with a space in its name, such as `My Git`, make sure to include the `\` character before the space in the path, like this: `My\ Git`.
 
 
