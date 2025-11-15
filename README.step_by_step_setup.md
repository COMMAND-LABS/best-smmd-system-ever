# TLDR

Here are the setup steps for how to get this SMMD system up and running.

## Overview

1. Prereqs for PART A
2. Setting up the Compilation Agent (PART A)
3. Prereqs for PART B
4. Setting up the Distribution Agent (PART B)
5. Example Prompts

## 1. Prereqs for PART A

- Sign up to Airtable (https://airtable.com/) [FREE]
- Sign up to Dropbox (https://www.dropbox.com/) [FREE]
- Sign up to n8n (https://n8n.io/) [$20/month]
- Connect to your preferred LLM [~$5-$10 in credits per month]
  - OpenAI Platform (https://platform.openai.com/)
  - Anthropic Console (https://console.anthropic.com/)

## 2. Setting up the "Compilation" Agent (PART A)

- Download the `n8n/Compilation_Agent.json` file
- Import the `Compilation_Agent.json` workflow into n8n
- Connect Airtable
  - Go to the Builder Hub in Airtable
  - Create a `Personal Access Token (PAT)` with the following permissions
    - `data.records:read`
    - `data.records:write`
    - `schema.bases:read`
  - Add the Airtable `PAT` to the Airtable node in n8n
- Connect your LLM Provider
  - ie: Create an API key in the OpenAI Platform (https://platform.openai.com/)
    - Add the OpenAI API key to the OpenAI node in n8n
- Set up the 3 Airtable tables (check out the `airtable/setup.md` doc for more info)
  - `Compilation Prompts`
  - `Content`
  - `Distribution Prompts`

## 3. Prereqs for PART B

- Download & Install Node.js (https://nodejs.org/en/download)
- Download & Install uv (https://docs.astral.sh/uv/getting-started/installation/)
- Sign up to Metricool (https://metricool.com/)
  - We will need the `ADVANCED` plan is it gives you access to the Metricool API
- Download Claude for Desktop (https://claude.ai/download)

## 4. Setting up the "Distribution" Agent (PART B)

- Get an API key from Metricool
  - Will be used in the `mcp/claude_desktop_config.json` file
- Get a PAT from Airtable
  - Will be used in the `mcp/claude_desktop_config.json` file
- Set up the `mcp/claude_desktop_config.json` on your computer
  - macOS: ~/Library/Application Support/Claude/claude_desktop_config.json
  - Windows: %APPDATA%\Claude\claude_desktop_config.json
- Here are the MCP servers needed
  - Airtable
    - https://glama.ai/mcp/servers/@domdomegg/airtable-mcp-server
    - https://github.com/domdomegg/airtable-mcp-server
  - Metricool
    - https://glama.ai/mcp/servers/@metricool/mcp-metricool
    - https://github.com/metricool/mcp-metricool

## 5. Example Prompts

The system is prompt based and is highly flexible to you needs. Below are 3 examples showing how to use the system.

### Demo_1 - peep `demo_1`

How to post a vertical video to YouTube, LinkedIn, Instagram, Facebook, TikTok, and X.com.

### Demo_2 - peep `demo_2`

How to post a promo image across multiple days
