# Prompt Library

## What This Repository Is
This is a cleaned, reusable prompt library organized by workflow instead of long file names and ad hoc storage. Each prompt file now includes a quick guide, a copy-ready prompt block, usage steps, and—when needed—a personalization guide for adapting person-specific prompts.

## Recommended Starting Points
- **Prompt improvement:** `01-prompt-engineering/ai-prompt-engineer-chat.md`
- **Quality review:** `02-critique-and-evaluation/critique-prime-evaluator.md`
- **Main repo README generation:** `03-github-readme-prompts/repo-main-readme/github-main-readme-maker.md`
- **Subfolder README generation:** `03-github-readme-prompts/folder-readme/github-folder-readme-maker.md`
- **Original LinkedIn post creation:** `04-linkedin-prompts/post-strategist/linkedin-content-strategist-auto-mode.md`
- **Best default LinkedIn repost prompt:** `04-linkedin-prompts/repost-strategist/linkedin-repost-v6-hybrid-master.md`
- **n8n automation assets:** `04-linkedin-prompts/*/n8n/`

## Repository Structure
```text
prompt-library/
├── README.md  # repository guide
├── PERSONALIZATION-GUIDE.md  # how to adapt person-specific prompts
├── MIGRATION_MAP.md  # old names to new names
├── 01-prompt-engineering/  # prompt-building and refinement
├── 02-critique-and-evaluation/  # QA and critique prompts
├── 03-github-readme-prompts/  # repo and folder README prompts
└── 04-linkedin-prompts/  # post and repost workflows plus n8n assets
```

## How To Use This Repository
1. Start with the folder that matches your task.
2. Open the prompt file and read the short guide at the top.
3. Copy the prompt from the **Copy-Ready Prompt** block.
4. Paste it into your AI tool and add the requested source material.
5. Save strong variants as new versions instead of destroying the original master.

## Naming System
- Folder names are short and workflow-based.
- File names are short, searchable, and version-aware.
- Production and automation assets are grouped under `n8n/` where relevant.

## Sharing With Friends
If a prompt is tailored to a specific person, open the file and use the **How To Personalize This Prompt For Another Person** section at the end. That section explains exactly what to replace before reuse.

## Maintenance Tips
- Add a folder `README.md` whenever you create a new prompt group.
- Keep prompt files focused: one prompt per file.
- Use version numbers only when the behavior meaningfully changes.
