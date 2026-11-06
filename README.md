# BrandWise AI

BrandWise AI checks draft content against brand rules and suggests a revised draft.

## Features

- Save brand rules in a SQLite database.
- Check a draft with Gemini when `GEMINI_API_KEY` is configured.
- Use basic rule checks if Gemini is unavailable.
- Save and reopen previous reviews.
- Copy the suggested revised draft.

## Run on Windows

1. Open PowerShell in this project folder.
2. Run `py server.py`.
3. Open http://localhost:8000 in a browser.

The app creates `brandwise.db` automatically in this folder. Keep the database and API key out of the public repository.
