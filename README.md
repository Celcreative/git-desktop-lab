# git-desktop-lab

This lab is to gain practical experience using Git and GitHub with GitHub Desktop for version control, collaboration, and conflict resolution. Students will learn to create and manage repositories, commit changes, work with branches, and resolve merge conflicts using a GUI-based workflow.


This is branch A and B.

## Steps Completed

### 1. Repository Setup
- Created a new repository with `README.md`
- Cloned to local using GitHub Desktop

### 2. Basic Git Operations
- Created `info.txt` with name, student ID, and course
- Updated `README.md` with lab purpose
- Committed and pushed changes

### 3. Branching and Merging
- Created `feature/new-content` branch
- Added `content.txt` with a paragraph about a favorite topic
- Committed, pushed, and merged using a pull request
- Pulled merged changes to `main`

### 4. Merge Conflict Resolution
- Created two branches: `branch-a` and `branch-b` from `main`
- Edited the same line in `README.md` in both branches:
  - `branch-a`: "This is branch A."
  - `branch-b`: "This is branch A and B."
- Merged `branch-a` into `main` via pull request
- Switched to `branch-b` and pulled from `main` → caused a **merge conflict**
- Resolved conflict by keeping:

- Marked conflict as resolved in GitHub Desktop
- Committed, pushed, and merged `branch-b` into `main`

---

## Challenges Faced

- **Branches not showing as folders:** Realized Git uses the same folder and only changes content when switching branches.
- **Merge conflict syntax confusion:** Learned what, and mean and how to manually fix them.

## Conclusion

This lab helped me:
- Use GitHub Desktop for commits, branches, and merges
- Understand and resolve merge conflicts
- Work with a real-world version control workflow
