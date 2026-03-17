# virtual-stores-feasibility-report

This is a documentation site to support adoption of virtual store technologies at NASA.

It is under active development through collaboration of the Virtual Stores Co-Working Group organized by @abarciauskas-bgse and @maxrjones.

## Installation

### Quarto

Install Quarto by downloading the installer for your platform from [quarto.org/docs/get-started](https://quarto.org/docs/get-started/), or via a package manager:

- **macOS (Homebrew):** `brew install --cask quarto`
- **Linux:** Download the `.deb` or `.rpm` package from the Quarto website
- **Windows:** Download the `.msi` installer from the Quarto website

Verify the installation with `quarto check`.

## Development

To preview the site locally:

```bash
make preview
```

This runs `quarto preview`, which serves the site and reloads on changes.

To publish to GitHub Pages:

```bash
make publish
```

This runs `quarto publish gh-pages`, which renders the site and pushes the output to the `gh-pages` branch. On first use, Quarto will prompt you to confirm the target repository. Ensure GitHub Pages is enabled in the repository settings (Settings → Pages → Source: `gh-pages` branch).
