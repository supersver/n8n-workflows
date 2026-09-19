# BoilDocs

> Turn technical documentation into concise, structured, and actionable notes for developers.

BoilDocs is an n8n workflow that takes a documentation URL or pasted documentation text, extracts the useful content, sends it to an LLM through OpenRouter, and returns a structured summary that can be consumed by a frontend or another automation.

## What it does

```text
Documentation URL / Text
          ↓
       Webhook
          ↓
   Detect source type
      ↓          ↓
    URL         Text
      ↓          ↓
 Fetch HTML   Use content
      ↓          │
 Extract text ───┘
          ↓
   Generate Summary
     via OpenRouter
          ↓
   Validate JSON
          ↓
 Respond to Webhook
```
