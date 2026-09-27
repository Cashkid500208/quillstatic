# quillstatic

Static blog generator: markdown in, tidy HTML out

Small but I use it weekly.

## Examples

```bash
mkdir posts && echo '# hello' > posts/first.md
python build.py
# site lands in dist/
```

## Install

```bash
pip install -r requirements.txt
```

## Highlights

- Markdown posts with fenced code and tables
- Index page with post list by date
- RSS feed generation
- Single template, plain str.format, no Jinja

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   └── usage.md
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── LICENSE
├── build.py
└── requirements.txt
```

## Development

```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
```

## License

MIT - see [LICENSE](LICENSE).
