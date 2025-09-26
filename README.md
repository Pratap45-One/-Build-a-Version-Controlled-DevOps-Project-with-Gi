# DevOps Git Project

## Overview
This project demonstrates Git best practices as part of a DevOps internship task.

## Branching Strategy
- **main**: Stable production-ready code
- **dev**: Development branch where features are merged before going to main
- **feature/**: Each new feature gets its own branch (e.g., `feature/login`, `feature/api`)

## Git Workflow
1. Create a feature branch from `dev`
2. Commit changes frequently with clear messages
3. Push branch to GitHub
4. Open a Pull Request to merge into `dev`
5. After testing, merge `dev` into `main`

## Tags
- v1.0 : Initial release with README and .gitignore

## Files Included
- `README.md` : Documentation of project workflow
- `.gitignore` : Ignored files and directories
- `script.py` : Example script for version control demonstration

---

### Example Command to Run Script
```bash
python script.py
```
