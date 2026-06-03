# Omarchy to Noctalia Color Schemes

This repository contains theme color schemes for the Noctalia Desktop Shell.

These schemes were converted from Omarchy theme color schemes using Python.

## Structure

- `colorschemes/`: The converted themes, ready to use.
- `omarchy-to-noctalia`: The Python conversion tool.

## How to use

Copy the themes you want to your Noctalia config directory:

```bash
mkdir -p ~/.config/noctalia/colorschemes/
cp -r colorschemes/* ~/.config/noctalia/colorschemes/
```

## Running the Conversion Script

You can also use the `omarchy-to-noctalia` tool to convert other Omarchy themes from GitHub:

```bash
./omarchy-to-noctalia <github_theme_url> [ThemeName]
```

Example:
```bash
./omarchy-to-noctalia https://github.com/basecamp/omarchy-dracula-theme Dracula
```
