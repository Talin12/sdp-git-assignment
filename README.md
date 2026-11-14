# sdp-git-assignment

A small two-page website (`index.html` and `about.html`) that I used to practise the Git workflow for my Software Development Practices assignment.

## What the history shows

- an initial commit, and a second commit that changes `index.html`
- a `feature` branch with its own commit (changes to `about.html`), merged back into `main` with `--no-ff` so the branch stays visible in the graph
- a `.gitignore` that ignores `*.log` files and the `temp/` folder
- an extra commit ("Add contact page") that was undone with `git revert`

To see the branch and the merge from the terminal:

    git log --oneline --graph --all

All the git commands I used are listed with short explanations in [git_commands.txt](git_commands.txt).
