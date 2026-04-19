# notes-ai

MkDocs-based notes site for AI topics.

## Local development

Create a virtual environment and install dependencies:

```bash
python3 -m venv .venv
. .venv/bin/activate
pip install -r requirements.txt
```

Run the local preview server:

```bash
mkdocs serve
```

Build the static site:

```bash
mkdocs build
```

The generated output is written to `site/`.
