# Claude Code Instructions

## Auto-push after every edit
After making any file changes, always run:
```bash
git add .
git commit -m "claude: <brief description of what changed>"
git push
```

## Project context
This is a static HTML project deployed on Vercel.
Any push to main auto-deploys to Vercel.
