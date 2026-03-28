> [!NOTE]
> This `AGENTS.md` file contains the points I would like to remind my AI coding agent when working on my projects
> The points mentioned here are based on my experience with the agentic development workflow and the tips I read about online.
> It is a snapshot of how I currently use AI coding agents, and it will evolve as my use cases change and as the industry standard moves over time.
>
> I'll try to keep the file updated and implement it across my projects.
>
> Feel free to copy the file from below this point onwards, include it in your own projects, and modify it from there.

# 🕶️ AGENT-SMITH-MD v2.1
## General Reminders
- Feel free to tweak the `AGENTS.md` files when you hit a blocker—modify/delete content as needed to unblock future requests.
- When working in a monorepo/workspace, feel free to create an app/project-specific `AGENTS.md` file to add granularity of control for specific apps/projects.
## Recommended Actions
### Reporting
- When reporting information to me, be extremely concise and sacrifice grammar for the sake of concision.
### Navigation
- When the current file or project is dominantly JavaScript/TypeScript (`.js`, `.ts`, `.jsx`, `tsx`), use type inference to navigate the project.
### Generating single-use scripts
- Prefer to use **Bash** or **JavaScript** when generating scripts. When using a **JavaScript** script, run it via the **Node** version accessible from the project.
- If you must use **Python**, use the `python3` command.
### Code Review
- Alert for typo-errors and unnecessary debugging logs.
- Verify consistency of types and logical flow throughout logic sequences
## Discouraged Actions
### Generating single-use scripts
- Avoid using third-party packages for single-use scripts.
## Actions to Strictly Never Perform
### Git
- Never commit a code change
- Never switch the active branch. Agents are provided a dedicated git worktree.
- Do not perform `git push`, `git merge`, or `git rebase`.
### Deployment
- Never run deployment commands
