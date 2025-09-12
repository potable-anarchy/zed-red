# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Zed editor theme extension repository containing a single custom theme:
- **Zed Red - Demonic**: A dark, edgy theme with pure black backgrounds and blood red accents, designed for night-time coding sessions

## Architecture

### Extension Structure
- `extension.toml`: Extension configuration file defining theme metadata and references
- `themes/`: Contains theme JSON files following Zed's theme schema
  - `themes/zed-red.json`: Complete theme definition with demonic red and black color palette

### Theme Schema
The theme follows Zed's official theme schema v0.2.0 and includes:
- Complete UI styling with pure black backgrounds and red accents
- Comprehensive syntax highlighting emphasizing reds and crimsons
- Terminal color definitions matching the demonic aesthetic
- Multiple player cursor colors for pair programming
- Status indicators using red color variants

## Key Information

### Theme Installation
Theme is installed by copying the `themes/` directory to `~/.config/zed/` and selecting "Zed Red - Demonic" in Zed's settings.

### Color Palette
**Zed Red - Demonic Theme:**
- Background: `#000000` (Pure black for minimal eye strain)
- Primary text: `#dc143c` (Crimson red)
- Accent: `#ff0000` (Bright red for focus elements)
- Keywords: `#ff0000` (Blood red for important syntax)
- Functions: `#ff3333` (Bright red for definitions)
- Comments: `#5a0000` (Dark red, subtle but visible)

### Development Notes
- No build system, package.json, or dependencies - this is a pure theme extension
- Theme file is a static JSON configuration
- Extension uses Zed's extension system as defined in `extension.toml`
- Designed specifically for developers who prefer dark, atmospheric themes with minimal eye strain