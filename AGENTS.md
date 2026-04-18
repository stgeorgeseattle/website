## Browser Validation

- All future changes must be visually tested in a browser to verify the changes were intentional and did not break existing behavior.
- Prefer Codex's in-app browser for this visual validation. If it is unavailable, use the `agent-browser` skill instead.
- If the global `agent-browser` skill is unavailable, use the repo-local fallback at `.skills/agent-browser/SKILL.md`.
- For every change with any visible surface area, explicitly compare exact screenshots from `master` against the working branch for the affected pages and states.
- Attach screenshots of every visible change to the pull request.
