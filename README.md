# Build With AI: Basics — Project Template

This repository is a reusable starting point for projects built with the
Build With AI: Basics workflow. It includes six agent skills for onboarding,
scoping, requirements, technical planning, building, and shipping.

## Create a project from this template

On GitHub, choose **Use this template** and create a new repository for your
project. Clone that repository and open its folder in your coding agent.

The skills are included in `.agents/skills/`, `agent/skills/`, and
`.claude/skills/` so different agent clients can discover them. Keep the skills
in place; start a new project by running `1-start`, then continue through the
numbered skills as appropriate.

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
