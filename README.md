# Talking Business with My LLM (Book Project)

This repository houses all source files, manuscripts, graphic assets, automation scripts, and promotional copy for the book ***Talking Business with My LLM: A Small Business Guide to Automating Data, Dashboards, and Decisions***.

## Repository Structure

```
.
├── assets/         # Cover designs, diagram graphics, and social media media
├── docs/           # Manuscript chapters, outlines, back-cover blurb, and copy
├── prompts/        # Sample prompt templates and workflow recipes referenced in text
├── scripts/        # Build tools, Markdown-to-PDF scripts, and compilation hooks
├── LICENSE
└── README.md

```

## Directory Breakdown

* **`assets/`**: Vector files (`.svg`), high-resolution book cover renders (`.png`), and data architecture diagrams.
* **`docs/`**: Manuscript files formatted in Markdown (`.md`), organized by chapter, alongside networking pitch copy and marketing material.
* **`prompts/`**: Production-ready prompt templates and LLM configurations featured in the book for readers to copy and adapt.
* **`scripts/`**: Local automation tools (such as Pandoc or Python compilation scripts) used to render Markdown text into print-ready PDF or ePub formats.

## Quick Start

1. **Clone the project:**
```bash
git clone https://github.com/your-username/talking-business-llm.git

```


2. **Review active drafts:** Navigate to `docs/` to view or edit chapter files.
3. **Generate distribution files:** Execute the build script in `scripts/` to aggregate individual chapters into a single target format.

---

**Repository Documentation Notes**

* **Directory Naming Conventions:** Unix and Git best practices favor lowercase directory names (`docs/`, `assets/`) and hyphenated or snake_case file names (`back-cover-blurb.md`) to maintain cross-platform compatibility.
* **Style Consistency:** Formal book titles within your documentation should retain standard American English title case (*Talking Business with My LLM*), whereas repository folder names and Git commands should remain entirely lowercase (`talking-business-llm`).
