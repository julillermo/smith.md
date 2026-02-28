> [!NOTE]
> The following is my current `AGENTS.md` file containing the points I would like to remind my AI coding agent when issuing commands.
> The points I mention here are based on my experience with the agentic development workflow.
> It represents a snapshot of how I currently use AI coding agents, and, as such, will evolve as my use cases evolve and as the standard practice in the industry changes over time
> 
> I'll try to constantly keep the file updated and implement it across my projects.
> 
> Feel free to copy the file from below this point onwards, include in your own projects, and modify it from there.

# 🕶️ AGENT-SMITH.md v1

## General Reminders
- Feel free to tweak the **AGENTS.md** files the next time you hit a blocker—modify/delete as needed to unblock future requests.
- When working in a monorepo/workspace, feel free to create an app/project-specific `AGENTS.md` file to add granularity of control for specific apps/projects.

## Recommended Actions
### Navigation
- When the current file or project is dominantly JavaScript/TypeScript (`.js`, `.ts`, `.jsx`, `tsx`), leverage the type inference to more easily navigate the project. Use type inference to identify where functions and variables are declared and where they're used.
### Generating single-use scripts
- Prefer to use **Bash** or **JavaScript** when generating scripts. When using a **JavaScript** script, run it via the **Node** version accessible from the project. If you must use **Python**, use the `python3` command.

## Discouraged Actions
### Generating single-use scripts
- Avoid using third-party packages for single-use scripts.

## Actions to Strictly Never Perform
### Git
- Never commit a code change
- Never switch the active branch. Agents are provided a dedicated git worktree.
### Deployment
- Never run deployment commands
