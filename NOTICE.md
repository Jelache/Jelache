# Attribution

The subagent definitions in `.claude/agents/` come from
[escapeboy/claude-code-kit](https://github.com/escapeboy/claude-code-kit), release v1.35.1
(`10-subagents/examples/`), and are used under its MIT License. Files: `code-reviewer.md`,
`debugger.md`, `test-generator.md`, `plan-challenger.md`, `output-evaluator.md` (unchanged),
`self-review.md`, `loop-monitor.md`.

Local changes:
- `loop-monitor.md`: read-only tools (`Read, Grep, Glob`) instead of `Read, Bash`;
  new `NOW` input; example script fixed (no `--var` flag, Linux/macOS notification);
  dead link removed.
- `self-review.md`: explicit `model` and read-only `tools`; removed the unused `category` key.
- `plan-challenger.md`: dead link removed.
- `code-reviewer.md`, `debugger.md`, `test-generator.md`: extracted from the
  "Agent Definition" block of the upstream example files.

## License of the upstream files

```
MIT License

Copyright (c) 2026 escapeboy (Nikola Katsarov)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
