# LinkedIn Post Strategist - n8n

## Module Summary
This subfolder contains automation assets for n8n-based LinkedIn post generation, including a system prompt, user prompt template, and workflow skeleton.

## Directory Structure
```text
├── system-prompt.md  # system prompt for automation node
├── user-prompt-template.md  # user message template with variables
└── workflow-skeleton.json  # importable n8n workflow skeleton
```

## How To Use This Folder
- Paste `system-prompt.md` into the system field of your AI node.
- Use `user-prompt-template.md` for mapped runtime variables.
- Import `workflow-skeleton.json` as a starting point, not a final production flow.

## Workflow Pattern
1. Pick the closest prompt instead of starting from a blank page.
2. Copy the prompt block from the chosen file.
3. Supply the source material, constraints, and target outcome.
4. Save improved variants as new versions when behavior changes materially.

## Maintenance Notes
- Keep names short, searchable, and folder-specific.
- Add new versions only when the output behavior changes clearly.
- Prefer updating this README when new files are added.
