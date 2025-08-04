Sure! Here's your list corrected and improved with some **additional important Git commands** including creating, switching, and deleting branches:

---

### ✅ **Important Git Commands**

---

**01.** `git clone <repository-link>`
🔹 *Clone the remote project to your local machine.*
📝 *Example:* `git clone https://github.com/user/repo.git`

---

**02.** `git status`
🔹 *Shows the current branch, staged and unstaged changes, and untracked files.*

---

**03.** `git add <filename>`
🔹 *Stages a specific changed file for commit.*

**OR** `git add .`
🔹 *Stages **all** changed files.*

---

**04.** `git commit -m "<message>"`
🔹 *Saves the staged changes to the local repository with a descriptive message.*
📝 *Example:* `git commit -m "Fixed login bug"`

---

**05.** `git push origin main`
🔹 *Pushes your local commits on the `main` branch to the remote repository (like GitHub).*

---

### 🧪 **Branch Commands**

**06.** `git branch`
🔹 *Lists all branches in your local repository.*
🔹 *The current branch is marked with `*`.*

---

**07.** `git branch <branch-name>`
🔹 *Creates a new branch.*
📝 *Example:* `git branch feature-login`

---

**08.** `git checkout <branch-name>`
🔹 *Switches to an existing branch.*
📝 *Example:* `git checkout feature-login`

---

**09.** `git checkout -b <new-branch>`
🔹 *Creates and switches to a new branch.*
📝 *Example:* `git checkout -b fix-header`

---

**10.** `git branch -d <branch-name>`
🔹 *Deletes a **local** branch (only if merged).*
📝 *Use `-D` to force delete if not merged.*
📝 *Example:* `git branch -d feature-login`

---

**11.** `git push origin --delete <branch-name>`
🔹 *Deletes a branch from the **remote** repository.*
📝 *Example:* `git push origin --delete old-feature`

---

### 🔄 Other Useful Commands

**12.** `git pull`
🔹 *Fetches and merges changes from the remote repository to your current branch.*

---

**13.** `git log`
🔹 *Shows the history of commits in the current branch.*
    : press 'q' to exit.

---

**14.** `git remote -v`
🔹 *Lists the remote URLs connected to your local repo.*

---

Let me know if you'd like a downloadable cheat sheet or a visual version too!
