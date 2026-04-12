# GitHub Folder README Maker

**Original source:** `03-github-master-prompts/github-subfolder-mainreadme/GitHub Repo Folder Readme Maker Master Prompt.md`

## Purpose
A subfolder-level README generator for documenting a specific module, feature folder, or internal package.

## Best Use Cases
- Documenting a focused part of a repository
- Explaining folder purpose, interfaces, and dependencies
- Improving maintainability for complex repos

## What You Need Before Using It
- Folder path and folder type
- A file tree or key file snippets
- Context on how the folder fits into the broader application

## How To Use
1. Copy the prompt into your AI tool.
2. Paste the folder tree and any important code snippets.
3. Specify whether the folder is API, UI, docs, utilities, or another module type.
4. Review the README and simplify or expand as needed.

## Expected Output
A technical folder README with a summary, tree, interfaces, dependencies, and a quick usage example.

## Recommended Platforms
ChatGPT, Claude, Gemini

## Copy-Ready Prompt
Copy the block below exactly as needed:

````text
Act as a Lead Systems Architect.
Your task is to write a highly focused, technical README.md for a specific sub-folder within my larger repository. Analyze the following folder contents and context:
[INSERT CONTEXT HERE]
Folder Name: [e.g., /security projects/app/api/video-generation or /scripts/automation or can be anything depending on type of folder/repo]
Folder Type: [Choose one: Documentation / portfolio / UI Components / API Routes / Database Models / Utility Scripts]
Files to Analyze: [Paste the folder's file tree or key code snippets here]
Please structure the README as follows:
1. Module Summary:
A brief 2-3 sentence explanation of what this specific folder does and how it fits into the broader application architecture.
2. Directory Structure:
Generate an ASCII text tree of the folder's contents, with a brief inline comment explaining the purpose of each major file.
3. Core Interfaces & Logic:
Detail the inputs and outputs. If it's an API folder, provide a table of endpoints, methods, expected payloads, and response formats.
If it's a Component folder, list the required/optional props in a table.
4. Dependencies & Constraints:
List any specific libraries or internal modules this folder relies on. Mention any strict constraints (e.g., "This route must be called server-side only").
5. Quick Example:
Provide a single, clear code snippet showing how another part of the application imports and uses the code from this folder.
Tone & Style: Keep it highly technical, concise, and modular. Eliminate marketing fluff; focus purely on developer experience (DX) and integration.
Pro-Tips for Using These Prompts
The "Project Type" Variable is crucial: If you tell the prompt it's a Developer Portfolio Piece, it will emphasize your skills and design choices. If you say it's an Open-Source Tool, it will emphasize contribution guidelines and clear APIs.
Iterative Prompting: If the generated Mermaid diagram is too complex, you can follow up with: "Simplify the Mermaid diagram to only show the macro-level steps."
````

## Practical Notes
- Keep the prompt unchanged if it already performs well for you.
- Add source material below the prompt when the workflow expects context.
- Save your best outputs as new versions instead of overwriting the master immediately.

## Maintenance
- Keep file names short and descriptive.
- If you improve the prompt, note the goal of the new version in the file title or folder README.
- Prefer creating a new version when the behavior changes significantly.
