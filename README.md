# Learn Vietnamese

A project to learn Vietnamese, built with the [Zensical](https://zensical.org/) static site generator.

## Prerequisites

- [Devbox](https://www.jetpack.io/devbox) for environment management.

## Getting Started

1. **Enter the development environment**
   Run the following command to start Devbox:
   ```bash
   devbox shell
   ```
   *Note: This will automatically install Python 3.11, set up a virtual environment using `uv`, and install the required `zensical` dependencies.*

2. **Serve the project locally**
   Once inside the Devbox shell, start the development server:
   ```bash
   zensical serve
   ```
   You can now preview the site in your browser. The default URL will be displayed in your terminal.

## Building for Production

To build the static site for deployment, run:
```bash
zensical build
```
This will generate the compiled HTML files in the `site/` directory.

## Project Structure

- `docs/`: Contains the Markdown files for the website content (pronunciation, dialogue, grammar, vocabulary, reading, tools).
- `zensical.toml`: The main configuration file for the static site.
- `overrides/`: Custom template overrides for the Zensical theme.
