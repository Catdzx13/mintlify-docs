> **First-time setup**: Customize this file for your project. Prompt the user to customize this file for their project.
> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

{/* Add product-specific terms and preferred usage */}
{/* Example: Use "workspace" not "project", "member" not "user" */}

## Style preferences

{/* Add any project-specific style rules below */}

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references
## Rich content conventions

- Prefer a varied but purposeful mix of cards, tabs, accordions, steps, callouts, badges, panels, frames, and Mermaid diagrams.
- Use cards for summaries and choices, steps for sequential procedures, tabs for alternate audiences or cases, and accordions for optional detail or FAQs.
- Do not repeat the same component pattern in every section. Let the information structure determine the component.
- Reuse the project snippets in `/snippets/ui/` before writing a repeated layout from scratch.
- Keep critical legal obligations visible in the page body. Do not hide material exclusions or refund conditions only inside collapsed accordions.
- All components must remain useful on mobile and understandable as plain text to search engines and AI crawlers.

## Content boundaries

{/* Define what should and shouldn't be documented */}
{/* Example: Don't document internal admin features */}
