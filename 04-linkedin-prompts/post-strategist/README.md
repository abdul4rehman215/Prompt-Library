# LinkedIn Post Strategist

## Module Summary
Use these prompts when you are creating original LinkedIn posts from scratch, from notes, or from projects. The folder includes manual prompts, editable personalization prompts, and automation assets.

## Directory Structure
```text
├── n8n  # resource
│   ├── system-prompt.md  # system prompt for automation node
│   ├── user-prompt-template.md  # user message template with variables
│   └── workflow-skeleton.json  # importable n8n workflow skeleton
├── linkedin-content-strategist-auto-mode.md  # prompt file
├── linkedin-content-strategist.md  # prompt file
├── linkedin-post-custom-gpt-production.md  # short production-ready prompt
├── linkedin-post-editable-base.md  # base prompt used to personalize or regenerate another prompt
├── linkedin-post-image-prompt-maker.md  # prompt file
├── linkedin-post-recruiter-facing.md  # resource
└── repo-to-linkedin-post.md  # resource
```

## How To Use This Folder
- Start with `linkedin-content-strategist-auto-mode.md` if you want one flexible default.
- Use the recruiter-facing version when interview visibility matters.
- Use the production or n8n assets when building automation.

## Workflow Pattern
1. Pick the closest prompt instead of starting from a blank page.
2. Copy the prompt block from the chosen file.
3. Supply the source material, constraints, and target outcome.
4. Save improved variants as new versions when behavior changes materially.

## Maintenance Notes
- Keep names short, searchable, and folder-specific.
- Add new versions only when the output behavior changes clearly.
- Prefer updating this README when new files are added.
