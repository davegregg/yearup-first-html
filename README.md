# YearUp: First HTML Project


Note: Do `git status` between all git commands.
1. **Stage** the changes (`git add .` or `git add insert-filename-here`).
2. **Commit** the changes with a commit message (`git commit -m "insert description of changes here"`).
3. **Push** the commit(s) to the GitHub repo ("origin remote"). `git push origin main`


**Note**: Do `git status` between all git commands to follow what is happening.
1. **Stage** the changes: Preparing the changes to be committed.
    - *Terminal way:* `git add .` or `git add insert-filename-here`
    - *VS Code Source Control panel way:* For each change listed, press the ➕ button to stage it (which will appear when hovering over the filename).
2. **Commit** the changes with a commit message, describing the changes.
    - *Terminal way:* `git commit -m "insert description of changes here"`
    - *VS Code Source Control panel way:* Press the "Commit" button. A new file called "COMMIT_EDITMSG" will be opened automatically. Write your commit message at the top of this file. When you are done, save the file, and close it to continue.
3. **Push** the commit(s) to the GitHub repo.
    - *Terminal way:* `git push origin main`
      - `main` here is the name of your current branch. In the case of `main`, it is the "main timeline" of your project.
      - `origin` here is a remote repo. `origin` is the default name of the official GitHub repo for your project.
    - *VS Code Source Control panel way:* Press the "Sync Changes" button, and then "OK" when prompted.