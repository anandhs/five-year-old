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

- Every post must include a top cover image using front matter:
  - `image: "/images/heroes/<post-slug>-hero.svg"` (or another valid path)
- If a specific image is not available, use the default:
  - `image: "/images/heroes/default-hero.svg"`
- If a concept benefits from visual explanation, create a simple local diagram (SVG preferred) and reference it in the post.
- If a diagram is not appropriate, include a relevant image from the web and set `image` to that URL.

## Front Matter Guidance

- Keep standard Hugo front matter (`title`, `date`, `description`, `tags`, `categories`, `draft`).
- Use meaningful `description`, `tags`, and `categories` aligned with the topic.
