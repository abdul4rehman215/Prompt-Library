# n8n User Prompt Template - LinkedIn Repost Strategist

**Original source:** `04-linkedin-master-prompts/linkedin-repost/n8n/User prompt template.md`

## Purpose
Variable-driven user prompt text for passing repost source content into an n8n workflow.

## Best Use Cases
- Webhook, form, sheet, or database driven repost workflows
- Separating stable system instructions from run-specific input

## What You Need Before Using It
- Creator name, source content, post type, context, and objective variables

## How To Use
1. Paste this into the user prompt field in n8n.
2. Map the correct upstream variables into each placeholder.
3. Validate the final rendered prompt during testing.

## Expected Output
A reusable user-message layer for repost automation.

## Recommended Platforms
n8n

## Copy-Ready Prompt
Copy the block below exactly as needed:

````text
Create a LinkedIn repost package from the source content below.

Creator name:
{{ $json.creator_name || "Original Creator" }}

Post type:
{{ $json.post_type || "unknown" }}

Source content:
{{ $json.source_content || "" }}

Extra context:
{{ $json.extra_context || "" }}

Optional objective bias:
{{ $json.objective_bias || "balanced reach + recruiter conversion + premium inbound trust" }}

Return output using the exact JSON schema requested by the workflow.
````

## Practical Notes
- Keep the prompt unchanged if it already performs well for you.
- Add source material below the prompt when the workflow expects context.
- Save your best outputs as new versions instead of overwriting the master immediately.

## Maintenance
- Keep file names short and descriptive.
- If you improve the prompt, note the goal of the new version in the file title or folder README.
- Prefer creating a new version when the behavior changes significantly.
