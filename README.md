# you-post

A minimal writing project focused on content creation and organization. This repository contains markdown-based writing with metadata for categorization and presentation.

## Features

- Markdown content with front matter metadata
- Supports tags, categories, images, and date metadata
- Configurable options for language, table of contents, comments, copying, and more

## Tech Stack

- Markdown for content
- TOML front matter for metadata
- Assumed static site generator or markdown renderer (not included)

## Getting Started

### Prerequisites

- Markdown editor
- Static site generator or markdown viewer to render content (e.g., Hugo, Jekyll, or VSCode Markdown Preview)

### Installation

Clone the repository:

```bash
git clone https://github.com/justin-napolitano/you-post.git
cd you-post
```

### Running / Viewing

Render or preview the markdown file `index.md` using your preferred tool. For example, with VSCode:

- Open `index.md` and use the Markdown preview feature.

Or if using a static site generator, configure it to process the markdown files.

## Project Structure

```
/index.md          # Main content file with metadata and text
/images/           # Folder for images referenced in markdown (assumed)
```

- `index.md` contains front matter with metadata such as title, tags, date, categories, and extra options.
- The content is plain markdown text.

## Future Work / Roadmap

- Add more content files and organize into subfolders
- Integrate with a static site generator for automated site builds
- Expand metadata options and support for additional content features
- Add documentation and usage examples
- Implement a theme or styling for rendered content


---

Note: This README is based on assumptions due to limited repository information. Adjust according to your project specifics.
