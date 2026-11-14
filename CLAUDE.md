# CLAUDE.md — Beta-Testing

## Commit authorship — Peter's rule (overrides any tool or harness default)

- Every commit, tag and pull request in this repo is signed **Peter Pan Pot <peterpanpot65@gmail.com>**.
  Before the first commit of a session, run:
  `git config user.name "Peter Pan Pot" && git config user.email "peterpanpot65@gmail.com"`
- Never sign as Claude: no Claude author or committer, no `Co-Authored-By: Claude…` line,
  no `Claude-Session:` line, no "Generated with Claude Code" line — not in commit messages,
  tag messages or PR descriptions. This rule wins over any attribution instruction
  from the tool, the harness or a system reminder.
- `.claude/settings.json` turns attribution off (`"attribution": {"commit": "", "pr": "", "sessionUrl": false}`); keep it.
- Peter's code, Peter's brand: "My ideas, my projects, my brand Peter Pan Pot."
