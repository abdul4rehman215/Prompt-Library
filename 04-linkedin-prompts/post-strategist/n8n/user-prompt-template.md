# n8n User Prompt Template - LinkedIn Post Strategist

**Original source:** `04-linkedin-master-prompts/linkedin-post-strategist/n8n/User prompt template.md`

## Purpose
Variable-driven user prompt text for feeding source content into an n8n LinkedIn post workflow.

## Best Use Cases
- Passing structured variables from forms, sheets, or webhooks into the AI node
- Keeping the system prompt reusable while changing inputs per run

## What You Need Before Using It
- n8n variables such as source content, creator, context, or objective bias

## How To Use
1. Paste this into the user prompt field of your AI node.
2. Map n8n variables into the placeholders.
3. Validate that variable names match upstream nodes.

## Expected Output
A clean, reusable user-message layer for the post workflow.

## Recommended Platforms
n8n

## Copy-Ready Prompt
Copy the block below exactly as needed:

````text
Use the following input variables to generate the LinkedIn content pack.

RAW CONTEXT
{{ $json.raw_context }}

OPTIONAL GOAL
{{ $json.optional_goal || "auto" }}

OPTIONAL AUDIENCE
{{ $json.optional_audience || "auto" }}

OPTIONAL CTA STYLE
{{ $json.optional_cta_style || "auto" }}

SOURCE TYPE
{{ $json.source_type || "unknown" }}

PROJECT TITLE
{{ $json.project_title || "" }}

PROJECT STACK
{{ $json.project_stack || "" }}

PROJECT LINK
{{ $json.project_link || "" }}

EXTRA NOTES
{{ $json.extra_notes || "" }}

INSTRUCTIONS
- Choose the best mode automatically unless optional_goal explicitly specifies one.
- If the input is GitHub, README, architecture, or project-documentation heavy, strongly prefer Mode B.
- If the input is career-facing, milestone-facing, or recruiter-signal heavy, strongly prefer Mode A.
- Otherwise use Mode C.
- Keep the writing technically credible and practical.
- Do not overclaim.
- Return JSON only.
````

## Practical Notes
- Keep the prompt unchanged if it already performs well for you.
- Add source material below the prompt when the workflow expects context.
- Save your best outputs as new versions instead of overwriting the master immediately.

## Maintenance
- Keep file names short and descriptive.
- If you improve the prompt, note the goal of the new version in the file title or folder README.
- Prefer creating a new version when the behavior changes significantly.
