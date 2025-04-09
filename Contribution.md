## 🧠 Task E: Reflection & Verification

### 1️⃣ Workflow Summary

This collaboration simulation involved using two GitHub accounts:  
- **Account A**: `manjeetsingh78` (original repository owner)  
- **Account B**: `Manjeet9058` (collaborator via fork and pull request)

#### 🔧 Steps Taken:
1. **Repository Creation**:  
   Created a repository named `collab-demo` under `manjeetsingh78`.

2. **Forking the Repository**:  
   Logged in to `Manjeet9058` and forked the `collab-demo` repo.

3. **Cloning & Branching**:  
   Cloned the forked repo locally and created a new branch `feature-update`.

4. **Making Changes**:  
   Added a new file (`contribution.md`) documenting the workflow and made minor edits to the README.

5. **Committing & Pushing**:  
   Committed the changes and pushed the branch to the forked repo.

6. **Creating Pull Request**:  
   Created a pull request from `Manjeet9058:feature-update` to `manjeetsingh78:main`.

7. **Review & Merge**:  
   Switched to `manjeetsingh78`, reviewed the pull request, approved it, and merged it into `main`.

#### ⚠️ Challenges & Solutions:
- **Challenge**: SSH key conflicts when switching between accounts on the same machine.  
  **Solution**: Used HTTPS for one account and SSH for the other, and configured Git to use account-specific credentials using `.gitconfig`.

- **Challenge**: Pull request not reflecting latest branch updates.  
  **Solution**: Ensured all changes were committed and pushed properly before creating the PR.

---

### 2️⃣ Verification

#### ✅ Original Repository (`manjeetsingh78`)
- Repository link: [https://github.com/manjeetsingh78/collab-demo](https://github.com/manjeetsingh78/collab-demo)
- Main branch contains merged PR with updated files.

#### ✅ Forked Repository (`Manjeet9058`)
- Fork link: [https://github.com/Manjeet9058/collab-demo](https://github.com/Manjeet9058/collab-demo)
- New branch: `feature-update`

#### ✅ Pull Request & Merge
- Pull Request: [View Pull Request](https://github.com/manjeetsingh78/collab-demo/pull/1)  
  *(Replace with actual PR link if different)*

#### 📸 Screenshots (if required):
Include screenshots in the `screenshots/` folder showing:
- The original repo and its commits
- The forked repo
- Branch creation and commit history
- The pull request and approval/merge

---

This concludes the reflection and verification for Task E. ✔️
