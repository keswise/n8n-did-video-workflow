# n8n D-ID Expressive Video Workflow

An n8n workflow for generating **expressive AI videos** using the **D-ID `/expressives` API**.

- Async video generation
- Polls until ready
- Returns final video URL
- No credentials included (safe to share)

---

## Files

workflow.json # n8n workflow (sanitized)
avatars.json # Public avatar & sentiment IDs

---

## Requirements

- n8n (cloud or self-hosted)
- D-ID API access

---

## Setup

1. Import `workflow.json` into n8n
2. Create a D-ID credential in n8n
3. Attach the credential to HTTP Request nodes
4. Choose `avatar_id` and `sentiment_id` from `avatars.json`
5. Provide input text


