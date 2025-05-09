# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Build Commands
- Local development: `hugo server`
- Production build: `hugo --gc --minify`

## Test Commands
- Verify site builds: `hugo --gc --minify`
- Check links: Run local server and validate with browser tools

## Code Style Guidelines
- Content: Write clear, concise Markdown with proper headings (h2, h3, etc.)
- Frontmatter: Use YAML format with consistent property naming
- Shortcodes: Prefer existing shortcodes (rn-button, people, fellows-resources)
- HTML: Minimize direct HTML in content files unless necessary
- Images: Store in /static/images/ with descriptive filenames
- File organization: Follow existing content directory structure
- Links: Use relative URLs for internal links
- Code blocks: Use proper language identifiers (```bash, ```python, etc.)

## Data Files
- YAML files in /data/ follow snake_case naming
- Structure new data files similar to existing ones