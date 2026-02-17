# AGENTS.md

## Default Instruction For New Posts

For every new blog post under `content/posts/`, use this structure in this exact order:

1. `## What it is`
2. `## Why`
3. `## How does it work`
4. `## More details (and references)`

## Writing Tone

- Use clear, simple language suitable for middle school readers and adults.
- Avoid childlike phrasing, baby talk, or "explained like you're 5" style.
- Keep explanations practical and accurate.

## References Requirement

- Include 2 to 3 high-quality references in the final section.
- Prefer primary or official sources where possible.

## Image Requirement

- For each new post, create a simple “How diagram” or sketch (SVG preferred) that explains the process in `## How does it work`.
- Place the diagram in the post content near the “How does it work” section.
- Use local assets when possible (for example, inside the post bundle or `static/images/diagrams/`).
- Do not create a hero image by default.
- If a diagram is not appropriate, include one relevant image from the web in the content instead.

## Front Matter Guidance

- Keep standard Hugo front matter (`title`, `date`, `description`, `tags`, `categories`, `draft`).
- Use meaningful `description`, `tags`, and `categories` aligned with the topic.
