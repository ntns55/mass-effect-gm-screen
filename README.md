# Mass Effect Inspired GM Screen (LaTeX)

A modular sci-fi GM screen project built in LaTeX.

## Structure

- `main.tex` - main document
- `preamble.tex` - packages, colors, reusable commands
- `content/` - panel content files
- `assets/` - panel backgrounds and visual assets

## Build

```bash
latexmk -pdf main.tex
cat > README.md <<'EOF'
# Mass Effect Inspired GM Screen (LaTeX)

A modular sci-fi GM screen project built in LaTeX.

## Structure

- main.tex - main document
- preamble.tex - packages, colors, reusable commands
- content/ - panel content files
- assets/ - panel backgrounds and visual assets

## Build

Run:

latexmk -pdf main.tex

## Notes

Place your background images in assets/ as:

- panel1.png
- panel2.png
- panel3.png
- panel4.png
