# Git Workflow Simulation

This project demonstrates a professional Git workflow setup, including branching strategy, merge conflict resolution, and branch protection rules.

## Project Structure

-   **main**: Production-ready code (protected).
-   **develop**: Integration branch for features (protected).
-   **feature/**: Feature branches for new developments.

## Workflow

1.  **Branching Strategy**: A `develop` branch was created and protected, along with `main`.
2.  **Merge Conflict**: Two feature branches (`feature/add-greeting` and `feature/change-greeting`) were created, intentionally causing a merge conflict in `hello.py`.
3.  **Conflict Resolution**: The conflict was resolved manually by editing the file and committing the changes.
4.  **Branch Protection**: Protection rules were applied to `main` and `develop` to enforce pull request reviews and prevent direct pushes.

## Learning Outcomes

-   **Git Branching**: Mastered creating and managing feature, develop, and main branches.
-   **Merge Conflicts**: Gained practical experience in identifying and resolving Git merge conflicts.
-   **Pull Requests**: Understood the importance of PRs for code review and collaboration.
-   **Branch Protection**: Learned to secure critical branches using GitHub's branch protection rules.

This simulation is essential for understanding team collaboration and ensuring a stable and professional codebase.
