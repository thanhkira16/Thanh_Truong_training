# Thanh Truong Gihub

## Git Basics: Adding and Committing

- **git repo, git init, git status, git add, git log**
- Committing workflow: `git add` (staging area) -> `git commit` (repository)

### Commits in Detail

- Atomic Commits: Each commit should represent a single feature, change, or fix.
- Writing Commit Messages: Use the imperative mood for clear communication and good collaboration habits.
- `git log --oneline`: View commit history in a concise format.
- Fixing Mistakes with Amend: Use when a file was missed in the previous commit.
  - `git add <missing file>` -> `git commit --amend`

### Ignore Files

- Use `.gitignore` file to specify files or patterns to be ignored.
  - `.filename`: Ignore files named 'filename'.
  - `folderName/`: Ignore an entire directory.
  - `*.log`: Ignore any file with the .log extension.

## Working with Branches

- **git branches**: Enables trying new things or working on multiple ideas in parallel.
- Default Branch: Typically named "master" or "main."
- `HEAD`: A pointer referring to the current location.
- View All Branches: `git branch`
- Create a New Branch: `git branch <name>`
- Switch to Existing Branch: `git switch <name>`
