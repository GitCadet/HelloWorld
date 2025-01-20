# HelloWorld WebApp - Git Workflow Practice Repo
This repository was created to practice Git workflows and imitate real world development scenarios. My goal was to gain hands-on experience in branch management, resolving conflicts, and git processes.

![image alt](https://github.com/GitCadet/HelloWorld/blob/main/Screenshot%202025-01-20%20at%2017.34.02.png?raw=true)

### 1. **Branching and Feature Development**
- I created the prod branch for isolated development of the HelloWorld webapp. (Other feature branches (e.g. dev,devR) were used similarly but for a index.html webpage.)
- I pulled updates from the remote to local machine to align with the latest changes.
- I updated background from "white" to "red", font color from "black" to "green" and box background from "white" to "yellow".  
- Committed changes frequently with messages for a readable history.

### 2. **Merging with main**
- Merged prod branches into the main branch while addressing divergence.
- Practiced both fastforward and three way merges, depending on branch history.

### 3. **Conflict Resolution**
- The main branch had diverged due to "Dev is cool" paragraph and an updated font from "Arial" to "Poppins". Resolved merge conflicts during both merging and rebasing.
- Gained familiarity with conflict markers and ensured correctness post-resolution.

### 4. **Stash and Rebase**
- Used git stash to temporarily save uncommitted changes and allow for task switching.
- Successfully reapplied stashed changes after resolving conflicts.
- Rebasing prod branches onto the updated main branch to maintain a linear commit history.
- Used git push -f to update remote branches after rebasing, ensuring a clean history.

  ![image alt](https://github.com/GitCadet/HelloWorld/blob/main/Screenshot%202025-01-20%20at%2017.30.56.png?raw=true)

### 7. **Merging into `prod`**
- Validated the main branch and merged it into the prod branch to simulate a deployment.
- Verified the deployment by testing the updated web application to ensure all changes were reflected and functional.

## Outcome
By completing these exercises, and simulating team collaboration by pulling, pushing, and resolving conflicts on shared branches, I developed a deeper understanding of Git best practices for repository management and strategies for addressing complex challenges in version control. I made sure these skills are directly transferable to team-based workflows in real world development projects.
