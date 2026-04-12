# LinkedIn Repost Strategist

## Module Summary
Use these prompts when you want to repost someone else’s LinkedIn content with your own angle, value-add, and positioning. The versions increase in complexity from basic to hybrid master mode.

## Directory Structure
```text
├── n8n  # resource
│   ├── system-prompt.md  # system prompt for automation node
│   ├── user-prompt-template.md  # user message template with variables
│   └── workflow-skeleton.json  # importable n8n workflow skeleton
├── linkedin-repost-custom-gpt-production.md  # short production-ready prompt
├── linkedin-repost-editable-base.md  # base prompt used to personalize or regenerate another prompt
├── linkedin-repost-v1.md  # versioned repost prompt
├── linkedin-repost-v2.md  # versioned repost prompt
├── linkedin-repost-v3-authority.md  # versioned repost prompt
├── linkedin-repost-v4-conversion.md  # versioned repost prompt
├── linkedin-repost-v5-elite-client.md  # versioned repost prompt
└── linkedin-repost-v6-hybrid-master.md  # versioned repost prompt
```

## How To Use This Folder
- Use `linkedin-repost-v6-hybrid-master.md` as the default all-around repost prompt.
- Use v3, v4, or v5 when you want a stronger bias toward authority, conversion, or premium positioning.
- Use the editable base when adapting the system to a new person.

## Workflow Pattern
1. Pick the closest prompt instead of starting from a blank page.
2. Copy the prompt block from the chosen file.
3. Supply the source material, constraints, and target outcome.
4. Save improved variants as new versions when behavior changes materially.

## Maintenance Notes
- Keep names short, searchable, and folder-specific.
- Add new versions only when the output behavior changes clearly.
- Prefer updating this README when new files are added.
