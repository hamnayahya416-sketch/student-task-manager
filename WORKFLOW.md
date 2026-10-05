# Team Workflow

## Team
- Team name: Code Crew
- Member 1: [Hamna Yahya] (Workflow owner and observer)
- Member 2: [Esha Saleem] (Developer)
- Project: Student Task Management System
- Communication: WhatsApp, short daily update

## Branch Strategy
- `main`: stable code, no direct commits
- `feature/<name>`: new features (e.g. `feature/add-task`)
- `bugfix/<name>`: bug fixes
- All changes go into main through a Pull Request

## Coding Standards
- Variables/functions: camelCase (e.g. `addTask`)
- Classes: PascalCase (e.g. `TaskManager`)
- Indentation: 4 spaces
- Use meaningful names and comment complex logic
- Do not commit debug code or unused code
- Commit messages short and clear: `Add task creation form`

## Pull Request Rules
- Every PR needs a title and a short description
- Link the issue: `Closes #1`
- At least 1 approval from the other member is required
- All review comments must be resolved before merging
- Never merge your own PR

## Definition of Done
A task is "done" when:
- [ ] The feature works as described in the issue
- [ ] Coding standards are followed
- [ ] It has been tested manually
- [ ] The PR is reviewed and approved
- [ ] All comments are resolved
- [ ] The code is merged into main
- [ ] The issue is closed
- [ ] The README is updated if needed
