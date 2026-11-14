# Attribution

The subagent definitions in `.claude/agents/` come from
[escapeboy/claude-code-kit](https://github.com/escapeboy/claude-code-kit), release v1.35.1
(`10-subagents/examples/`), and are used under its MIT License.

Local changes:
- `loop-monitor.md`: read-only tools (`Read, Grep, Glob`) instead of `Read, Bash`;
  new `NOW` input; example script fixed (no `--var` flag, Linux/macOS notification);
  dead link removed.
- `self-review.md`: explicit `model` and read-only `tools`; removed the unused `category` key.
- `plan-challenger.md`: dead link removed.
- `code-reviewer.md`, `debugger.md`, `test-generator.md`: extracted from the
  "Agent Definition" block of the upstream example files.

MIT License — Copyright (c) 2026 escapeboy (Nikola Katsarov). Full text:
https://github.com/escapeboy/claude-code-kit/blob/v1.35.1/LICENSE
