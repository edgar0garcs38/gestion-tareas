# Task Manager: Git Feature-Branch Workflow (Angular 20)

An Angular 20 project used to practice a **feature-branch Git workflow**. Each feature of a task-management app is developed on its own branch from a common base.

## Branches
| Branch | Purpose |
|---|---|
| `main` | Base Angular 20 project |
| `feature/auth` | `Login` component |
| `feature/tareas` | `Tareas` (tasks) component |
| `feature/dashboard` | `Dashboard` component |

The components are scaffolded with the Angular CLI. The focus of this repository is the branching structure and commit history, not the UI.

## Tech stack
Angular 20 · TypeScript · Git

## Run it
```bash
npm install
ng serve
```
Then open `http://localhost:4200/`. Switch branches with `git checkout feature/<name>` to see each component.
