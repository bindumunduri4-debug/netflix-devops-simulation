# Branching Strategy - Netflix DevOps Simulation

## Main Branch (`main`)
- Contains production-ready code
- Protected from direct changes

## Feature Branches (`feature/<name>`)
- Used for new features or improvements
- Example: `feature/homepage`, `feature/seo-update`

## Workflow Steps
1. Create feature branch from `main`
2. Make changes and commit locally
3. Push to GitHub
4. Create a Pull Request (PR)
5. Review and resolve any conflicts
6. Merge into `main` after approval

## Benefits
- Clean and safe production branch
- Parallel development for teams
- Easier conflict management and code reviews
