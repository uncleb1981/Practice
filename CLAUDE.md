# Claude Code Instructions

## Default Push Workflow

When the user provides a GitHub repository name, follow this process:

1. Set the remote origin to `https://github.com/uncleb1981/<repo-name>`
2. Create or update the necessary files (README.md, index.html, etc.)
3. Commit with a clear, descriptive message
4. Push to the designated working branch (e.g., `claude/<session-branch>`)

## GitHub Pages Setup Reminder

After pushing, remind the user to:
- Go to **Settings → Pages** in the GitHub repo
- Set the source branch to the branch files were pushed to
- Or merge the branch into `main` and set Pages source to `main`

## Notes

- Only push to branches prefixed with `claude/` (permission restriction)
- The user's GitHub username is: `uncleb1981`
