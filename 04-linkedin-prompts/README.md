# LinkedIn Prompts

## Module Summary
This folder contains content-generation and repost-generation prompts for LinkedIn. It is organized into post-strategist and repost-strategist workflows, plus n8n automation assets where relevant.

## Directory Structure
```text
├── post-strategist  # prompt file
│   ├── n8n  # resource
│   │   ├── system-prompt.md  # system prompt for automation node
│   │   ├── user-prompt-template.md  # user message template with variables
│   │   └── workflow-skeleton.json  # importable n8n workflow skeleton
│   ├── linkedin-content-strategist-auto-mode.md  # prompt file
│   ├── linkedin-content-strategist.md  # prompt file
│   ├── linkedin-post-custom-gpt-production.md  # short production-ready prompt
│   ├── linkedin-post-editable-base.md  # base prompt used to personalize or regenerate another prompt
│   ├── linkedin-post-image-prompt-maker.md  # prompt file
│   ├── linkedin-post-recruiter-facing.md  # resource
│   └── repo-to-linkedin-post.md  # resource
└── repost-strategist  # prompt file
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
- Use `post-strategist` when writing original content.
- Use `repost-strategist` when reacting to or reposting someone else’s content.

## Workflow Pattern
1. Pick the closest prompt instead of starting from a blank page.
2. Copy the prompt block from the chosen file.
3. Supply the source material, constraints, and target outcome.
4. Save improved variants as new versions when behavior changes materially.

## Maintenance Notes
- Keep names short, searchable, and folder-specific.
- Add new versions only when the output behavior changes clearly.
- Prefer updating this README when new files are added.
