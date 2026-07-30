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
## Knowledge Base information architecture

- Keep knowledge/vi/index.mdx as the main Knowledge Base landing page.
- Organize product tutorials under knowledge/vi/huong-dan/category-name/.
- Organize troubleshooting under knowledge/vi/khac-phuc-loi/.
- Organize comparison and review content under knowledge/vi/blog/so-sanh/ and knowledge/vi/blog/review/.
- Organize announcements and promotions under knowledge/vi/tin-tuc/.
- Create category hub pages first. Add individual articles to navigation only after their instructions, screenshots, links, and product facts are verified.
- Troubleshooting articles must link to warranty and support. Comparison/review articles may include a relevant storefront CTA after the analysis.
- Do not publish placeholder articles or demo product claims.
- Organize legal navigation by policy topic first, then list Tiếng Việt, English, and 한국어 as leaf pages.
