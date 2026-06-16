# Project Instructions: nguyenp70.github.io

This file provides foundational mandates and conventions for Gemini CLI when working on this repository.

## Project Overview
A personal website hosted on GitHub Pages. It currently uses a custom "Corporate Cyber" HTML/CSS layout instead of a standard Jekyll theme.

## Foundational Mandates
- **Static Site Logic**: Maintain the integrity of the custom HTML/CSS structure in `index.html`.
- **Security**: Never commit or log secrets, including any tokens stored in `.env`.
- **Command Substitution**: Do NOT attempt to run shell commands containing command substitution (e.g., $(...), backticks). Instead, provide the final command to the user and ask them to execute it manually to avoid security blocks.
- **Deployment Trigger**: Only push changes to the production repository (GitHub) when the user explicitly says "**push to prod**". Otherwise, only update files locally and commit them without pushing.
- **Changelog Maintenance**: Every time the user says "**changelog update**", update the `CHANGELOG.md` file with a concise summary of the recent changes made to the codebase.
- **Environment**: All local operations should be performed within the WSL environment.

## Conventions & Style
- **Formatting**: Use clean, semantic HTML and CSS within `index.html`.
- **Assets**: Organize any future images or assets in an `assets/` directory.
- **Theme**: Adhere to the "Corporate Cyber" high-contrast aesthetic (Deep Navy, Slate, Cyan accents).

## Workflow
- **Validation**: Ensure any changes to `index.html` preserve the standard HTML5 structure.
- **Pushing to Prod**: When pushing changes (triggered by "push to prod"), provide the user with the git push command that includes the token retrieval logic from `.env`.
