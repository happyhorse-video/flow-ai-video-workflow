# Flow AI Video Prompt & Workflow Assistant

A reusable skill for turning creative briefs, product images, and rough ideas into AI video prompt packages.

## What it does

- Plans coherent shots for product demos, short social videos, and landing-page loops.
- Writes paste-ready text-to-video and image-to-video prompts.
- Preserves reference-image details and identifies relevant motion constraints.
- Provides review criteria and targeted prompt revisions.

This is a planning skill. It does not connect a video-generation API or render videos by itself.

## Use in Runable

1. Download [flow-ai-video-workflow.zip](flow-ai-video-workflow.zip).
2. Open [Runable Skills](https://runable.com/skills) while signed in.
3. Choose Create → Upload skill and select the ZIP file.
4. Enable `flow-ai-video-workflow` and use it in your next conversation.

For other compatible agents, use [SKILL.md](SKILL.md) as the skill entrypoint.

## Example request

> Use flow-ai-video-workflow to plan a six-second product hero loop for a landing page. Keep the product centered with room for a heading on the left. Give me one image-to-video prompt, preservation constraints, and a short review checklist. Treat duration as a target until supported settings are confirmed.

The assistant responds in your language and provides English generation prompts by default. It distinguishes creative targets from verified tool capabilities.
