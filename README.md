# DSGF

Repository for the [Digital Scholarship Graduate Fellows Program](https://digitalscholarship.blogs.brynmawr.edu/dsgf/) at Bryn Mawr College, AY 2025-2026.

Led by Alice McGrath (Senior Digital Scholarship Specialist) and Jeff Hopkins (Educational Technology Specialist)

## Editing the site

This site uses [Quarto](https://quarto.org/) to render markdown into web content. Review the [Quarto docs on Websites](https://quarto.org/docs/websites/) for configuration. Content is 

When adding new documents, use this folder structure:

- `logs` for personal smart goals and logs
- `meetings` for session and meeting notes
- `resources` for instructional materials

## Deploying the site

- Committing to the main branch will not cause the rendered site to update. This site is deployed using the `quarto publish` command, which renders html and pushes it directly to the `gh-pages` branch.
- This can only be done from VS Code using a local clone.
- To configure Quarto, use [these instructions](https://quarto.org/docs/get-started/hello/vscode.html)