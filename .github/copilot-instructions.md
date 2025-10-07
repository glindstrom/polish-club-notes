# Polish Club Notes - AI Coding Instructions

## Project Overview

This is a bridge bidding system documentation project focused on the Polish Club convention. The codebase maintains MkDocs comprehensive bidding notes for tournament players.

## Architecture & Key Components

### Documentation Structure

- **Primary content**: `docs/` directory contains all Markdown source files
- **Navigation hierarchy**: Organized by bidding categories (openings, competitive-bidding, conventions, slam-bidding)
- **Web publishing**: MkDocs Material theme with GitHub Pages deployment
- 

### Content Organization Patterns

```
docs/
├── index.md                    # Main landing page
├── [category]/
│   ├── overview.md            # Category introduction
│   └── specific-topics.md     # Individual bidding sequences
```

**Critical pattern**: Each bidding sequence follows a consistent structure:

- Opening description with HCP ranges and distribution
- Response tables using specific format
- Detailed sequence explanations with nested collapsible sections

### Build & Deployment Workflows

#### Web Documentation

- **Command**: `mkdocs build` → generates static site in `site/`
- **Auto-deployment**: GitHub Actions pushes to `gh-pages` branch
- **Config**: `mkdocs.yml` defines navigation structure and theme settings
- **Styling**: Custom CSS in `docs/css/` for enhanced presentation


## Development Conventions

### File Naming & Structure

- **Consistent naming**: Use descriptive hyphenated names (e.g., `one-club-interference.md`)
- **Bridge notation**: Use Unicode card symbols (♣♦♥♠) consistently throughout
- **Response tables**: Standard format with specific columns (Response | Meaning)

### Content Patterns

- **Collapsible sections**: Use `??? note "Title"` for detailed explanations
- **HCP ranges**: Always specify vulnerability differences in opening tables
- **Sequence notation**: Use consistent format like `1♣--1♦--1♥` for bidding sequences

### CSS & Styling

- **Web styling**: `docs/css/custom.css` for MkDocs Material customizations
- **Typography**: DejaVu Sans font family for consistent rendering

## Key Files for AI Understanding

### Navigation & Structure

- `mkdocs.yml`: Complete site navigation and configuration
- `docs/index.md`: Project overview and section links
- `docs/openings/overview.md`: Example of category overview pattern

### Build System

- `.github/workflows/deploy.yml`: Automated deployment pipeline

### Example Content

- `docs/openings/one-club.md`: Demonstrates full bidding sequence documentation pattern
- `docs/competitive-bidding/overview.md`: Shows category organization approach

## Development Workflow

1. **Content changes**: Edit Markdown files in `docs/` structure
2. **Navigation updates**: Modify `mkdocs.yml` nav section to reflect new files
3. **Testing**: Run `mkdocs serve` locally before pushing
4. **Deployment**: Push to main branch triggers automatic GitHub Pages deployment

## Special Considerations

- **Bridge terminology**: Maintain consistent use of standard bridge notation
- **Vulnerability context**: Many opening ranges differ by vulnerability - always specify
- **Cross-references**: Use relative links between related bidding sequences
- **Table formatting**: Preserve exact table structure for clear bid/meaning pairs
