# Better Cursor

Cursor does way too many things by default. When you ask it to create something, it'll over engineer a feature, add tests, add a readme, and import a bunch of libraries that aren't likely necessary.

This changes things so that it does _less_ and better matches how explicit you are.

## Rules

- `coding_style.mdc` - Standards for concise code creation with limited design patterns. Do less, don't over engineer, start with MVP and we can iterate.
- `rules_location.mdc` - Let's you say "create a rule about X" and it will automatically create that rule within the rules directory.
- `self_improvement.mdc` - Instructs cursor to continuously seek rules that ought to be created. If it finds new patterns, gets reviews, or more, it will suggest creating a rule.
- `task_drive_development.mdc` - For larger feature adds, rather than get to work and risk losing context, it will instead create a PRD and a list of tasks to complete sequencially and in priority. That way it works one task at a time without getting lost in large contexts.
