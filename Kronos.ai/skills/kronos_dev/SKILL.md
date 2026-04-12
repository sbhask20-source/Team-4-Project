---
name: kronos-dev
description: Build and maintain Kronos.ai, a multimodal scheduling extraction app that converts screenshots or photos into structured calendar entries.
---

Use this skill when working on the Kronos.ai MAE301 project.

## Product goal
Kronos.ai accepts an uploaded screenshot or photo containing scheduling information.
It extracts:
- title
- date
- time
- location
- notes
- confidence
- missing_fields

## Engineering rules
- Keep the app small and demoable.
- Use the OpenAI Responses API for image understanding.
- Use Structured Outputs with a strict JSON schema.
- Keep extraction logic separate from normalization logic.
- Never trust raw model output without schema validation.
- Prefer deterministic post-processing for date and time cleanup.
- Add tests for every normalization rule.
- Keep README updated when commands or files change.

## Project files
- app.py: demo UI
- src/extract.py: OpenAI API call
- src/schema.py: JSON schema / typed model
- src/prompts.py: system prompt
- src/normalize.py: cleanup and validation
- tests/: unit tests

## Good tasks for this skill
- Scaffold the project
- Implement image-to-JSON extraction
- Add schema validation
- Add normalization for date/time/location
- Create sample tests
- Improve prompt reliability
- Add demo UI

## Done criteria
- App runs locally
- Uploading an image returns structured JSON
- Tests pass
- README explains setup and demo steps  
