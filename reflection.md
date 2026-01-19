# Team Reflection - Assignment 02: Agile Collaboration

## 1. Conflict Report: Many-to-One Simulation
Our team successfully simulated a "Many-to-One" merge conflict in the `README.md` file to practice professional Git collaboration and conflict resolution.

* **The Scenario:** All three members (Linh, Long, and Quan) edited the exact same line in the `README.md` file on separate feature branches. Specifically, each member added their own introduction line ("My name is...") right under the "Hello everyone!" header.
* **Merge Order:**
    1. **Linh Merged First:** Her Pull Request was merged into `main` automatically as the branch was clean.
    2. **Long Merged Second:** After Linh’s merge, Long’s PR flagged a "Can't automatically merge" error. Long had to pull the updated `main` and resolve the conflict locally before merging.
    3. **Quan Merged Last:** By this time, the `main` branch contained both Linh's and Long's updates. Quan pulled the latest `main`, resolved the remaining differences on his local machine, and completed the team's integration.
* **Resolution Method:** We utilized **Method 1: Local Merge Resolution**.
    * Members facing conflicts used `git pull origin main` to fetch the latest changes.
    * We used VS Code's merge editor to compare changes and select the appropriate content (Accept Incoming/Current) to preserve everyone's contributions.
    * Finalizing with `git add`, `git commit`, and `git push` ensured the conflict was resolved on GitHub.

**This simulation helped the team understand the importance of pulling the latest `main` branch before merging and reinforced real-world Git collaboration practices.**

## 2. The Value of Code Review
Requiring at least 2 comments per Pull Request provided significant benefits:
* **Maintaining Consistency:** It ensured all members were aware of how the `README.md` and `index.html` structures were evolving.
* **Peer Support:** Instead of struggling with conflicts alone, members received guidance and suggestions through PR comments.
* **Agile Quality Control:** It established a habit of cross-checking work to ensure high standards before merging into the production branch (`main`).

## 3. Agile Events & Team Tracking
* **Mini-Daily Standups:** We held quick sync-ups to communicate merge status. This allowed the next person to know exactly when to pull the latest `main` to resolve their conflicts.
* **GitHub Projects (Agile Board):** The Scrum Master monitored task statuses closely. When a PR showed a conflict (red status), the team coordinated immediately to assist.
* **Definition of Done (DoD):** A task was only moved to "Done" once it passed 2 peer reviews, resolved all conflicts, and was successfully merged into the `main` branch.

---
**Team Members:**
* Long (Scrum Master / Developer)
* Linh (Product Owner / Developer)
* Quan (Developer)