# TLDR

Welcome to the "Best SMM Distribution System Ever"!

SMM = Social Media Marketing

## Gist of how this system works after setup

1. Compile Social Media Content
2. Review (Human-in-the-Loop)
3. Schedule
4. Review (Human-in-the-Loop)
5. Publish

## How to setup the system

Check out `README.step_by_step_setup.md`

## System Diagram

Peep `diagrams/SMMD_agents.png`

## Compilation Agent components (PART A)

- `Airtable` (https://airtable.com/)
- `Dropbox` (https://www.dropbox.com/)
- `n8n` (https://n8n.io/)
- Whichever LLM provider you prefer (pick your poison)
  - `OpenAI` (https://platform.openai.com/)
  - `Anthropic API` (https://console.anthropic.com/)
  - `Ollama` (https://ollama.com/)
  - etc.

## Distribution Agent components (PART B)

- `Airtable` (https://airtable.com/)
- `Dropbox` (https://www.dropbox.com/)
- `Metricool` (https://metricool.com/)
- Local MCP Client
  - `Claude for Desktop` (https://claude.ai/download)
  - `Cursor` (http://cursor.com/)
  - etc.

## General MCP docs

- https://docs.anthropic.com/en/docs/mcp
- On Mac, configure MCP setup in the `~/Library/Application Support/Claude/claude_desktop_config.json` file
- On Windows, configure MCP setup in the `%APPDATA%\Claude\claude_desktop_config.json` file

# Shoutouts

Shoutout to Chris Larco 🇭🇹
