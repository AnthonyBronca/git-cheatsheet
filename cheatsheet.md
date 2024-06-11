# GIT Commands

Change Directory - `cd <file path>` Example: `cd ./appacademy/projects/problems`

Go up a directory - `cd ..`

Go to Home Directory - `cd`

List Files - `ls`

List all files (includes hidden files) - `ls -a` (note, if you see a `.git` file, this is what tracks to a repo)

Check node version - `node -v`

Check nvm version - `nvm -v`

Install using Node Package Manage - `npm install <package name>`

Run command using Node Compiler - `node <file name>` (this is how we can read javascript files)

Open a file in vscode - `code <file path>` Example: `code .` or `code ./appacademy/projects/problems`

# Github specific Git Commands


- Check the address of a project's repo - `git remote --v`

- Add current directory changes - `git add .`

- Commit changes - `git commit -m ""` Example: `git commit -m "added notes"`

- Push commited changes to Github - `git push`

- Clone a repo - `git clone <github url> <optional-rename`

    Example 1: Cloning with out renaming:

        git clone https://www.github.com/yourusername/someRepo

    Example 2: Clone with a rename

        git clone https://www.github.com/yourusername/someRepo newRepo

    The folder created by `git clone` will be called "newRepo" and not "someRepo'

    Example 3: Clone with a branch:

        git clone --branch <branch-name> <github url> <optional rename>
        git clone --branch part-time https://www.github.com/appacademy/someRepo newRepo

- Get changes from Github - `git pull`

- See every day github commands `git help everyday`
