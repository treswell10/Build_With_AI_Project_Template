# Build With AI: Basics — Project Template

This repository is a reusable starting point for projects built with the
Build With AI: Basics workflow. It includes six agent skills for onboarding,
scoping, requirements, technical planning, building, and shipping.

## Create a project from this template

On GitHub, choose **Use this template** and create a new repository for your
project. Clone that new repository and open its folder in your coding agent
(for example, VS Code with Copilot or Claude Code).

The skills are included in `.agents/skills/`, `agent/skills/`, and
`.claude/skills/` so different agent clients can discover them. Keep the skills
in place.

### First step after cloning

In your coding agent's chat, invoke the **`1-start`** skill. It checks that the
folder is ready for a new project, learns what you want to build and your
experience, and creates your project workspace documents. Then follow the
numbered workflow: `2-scope` → `3-prd` → `4-spec` → `5-build` → `6-ship`.
Start with `1-start` even if you're not sure what to build yet.

## Make this repository a GitHub template

Publish this repository to GitHub:

```powershell
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/treswell10/Build_With_AI_Project_Template.git
git push -u origin main
```

Then open the repository's **Settings**:

1. Under **General**, enable **Template repository**.
2. Save the setting.

## Privacy

The root `.gitignore` excludes `.env` files and
`devpost/learner-profile.md` by default. The learner profile may contain
personal learning context; review files and git history for private data or
credentials before publishing a project repository.
