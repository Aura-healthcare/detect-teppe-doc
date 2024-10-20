# detect-teppe-doc
Centralized documentation for onboarding on detect-teppe project

# Contribute to the documentation

## Install dependencies

```bash
git clone https://github.com/aura-association/detect-teppe-doc.git
cd detect-teppe-doc
uv sync
```

## Update the documentation

Update the documentation, to see the changes locally, run:

```bash
uv run mkdocs serve
```

## Commit your changes in a PR

```bash
git checkout -b feat/update-docs
git add .
git commit -m "Update the documentation"
git push origin feat/update-docs
```

And open a PR on GitHub.


At the merge of your PR, the documentation will be automatically deployed.