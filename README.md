# inkpress

My tiny static site generator, ~100 lines of Python

Built for my own use; public in case it helps someone.

## Install

```bash
pip install -r requirements.txt
```

## Highlights

- Single template, plain str.format, no Jinja
- RSS feed generation
- Markdown posts with fenced code and tables
- Index page with post list by date

## Examples

```bash
mkdir posts && echo '# hello' > posts/first.md
python build.py
# site lands in dist/
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── development.md
│   ├── roadmap.md
│   └── usage.md
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
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
