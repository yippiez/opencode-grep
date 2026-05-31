# opencode-grep

A read-only [opencode](https://opencode.ai) agent for code search and explanation.

- Green-colored (`#A7DCA5`) subagent
- **Read-only**: edit/deny, write/deny, webfetch/deny
- Permitted bash: `fzf`, `ast-grep`, `rg`, `grep`, `ls`
- Provides file locations and step-by-step code walkthroughs

## Usage

Place `grep.md` in `~/.config/opencode/agent/` and restart opencode. Then invoke with `@grep`.
