# Meeting Action Board

## Overview
This project extracts action items from meeting transcripts using LangChain tool calling, stores results in SQLite, and creates GitHub issues for confirmed actions.

## Objective

Extract action items from meeting transcripts using LangChain Tool Calling.

## Features

- LangChain Tool Calling
- GitHub Issue Creation
- SQLite Storage
- Duplicate Detection
- OpenRouter GPT-4o Mini

## Setup

1. Clone repository
2. Install dependencies

pip install -r requirements.txt

3. Configure secrets

- OPEN_ROUTER_API_KEY
- GITHUB_TOKEN
- GITHUB_OWNER
- GITHUB_REPO

4. Run notebook

## Note

The implementation is complete. During testing, OpenRouter returned:

403 PermissionDeniedError
Key limit exceeded (total limit)

This is an API account/quota limitation.

