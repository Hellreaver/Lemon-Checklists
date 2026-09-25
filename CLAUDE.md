# Lemon-Checklists

Procedure guides built from the Lemon manuals MCP server, one HTML file per job under `guides/`.

- Follow `style-guide.json` for colors, type and components; `guides/volvo-940-b230fd-head-gasket.html` is the reference page.
- Put the manual's own figures in the guide wherever a step, sequence or spec table has one. Get them with the MCP `get_image` tool, store them in `guides/img/<guide-name>/`, and link them with relative paths. Rules are under `guidePage.images` in the style guide.
- Confirm the exact year, model and engine code before writing; pull every spec from that vehicle's book.
- Push straight to `main` (GitHub Pages serves from it). No attribution lines in commits.
- Keep local paths, host names, ports and personal details out of committed files; the repo is public.
