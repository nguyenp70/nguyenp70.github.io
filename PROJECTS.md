# Project Creation Guidelines

When the user triggers the **Create Project** command, follow this workflow to build their new project page:

## 1. Information Gathering
Before writing any code, ask the user the following questions if the information wasn't provided:
- **Project Title**: What is the name of the project?
- **Category/Topic**: What category does it fall under (e.g., Open Source, Security Research)?
- **Tags**: What 2-3 technical tags should be included?
- **Description**: What is the short description for the project card?
- **Detailed Content**: Do you have the main body text for the project page, or should I generate placeholders?

## 2. Design & Styling Conventions
- **Fonts**: Use the existing site font (`'SF Mono', 'Fira Code', monospace`) for body text.
- **Headings**: Use `<h1>` with Light Slate (`#ccd6f6`) for the main title.
- **Dates**: Place a "Published: MM/DD/YYYY" date tag directly under the main heading using the `--accent` or `--text-dim` colors.
- **Card Format**: When adding the card to grids, ensure the date is placed in the top-right corner of the card across from the category.
- **Integration**: Ensure the new project is properly added to the `projects.html` grid and correctly linked.

## 3. Template
Use `project-example.html` as the baseline layout template for all new projects to maintain visual consistency.
