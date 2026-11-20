# GEOG0125: Migration from R Markdown/Bookdown to Quarto

## 1. Project Objective

GEOG0125 (Advanced Topics in Social & Geographic Data Science) is a postgraduate module at UCL. Its computer practicals were originally developed using R Markdown (`.Rmd`) and published using Bookdown.

The objective is to migrate the existing teaching materials to Quarto (`.qmd`), using Positron as the primary development environment.

The migrated materials should preserve the original teaching content, R code, datasets, figures, exercises and overall document structure, while taking advantage of Quarto's publishing capabilities.

## 2. Preferred Tools

- **IDE:** Positron on macOS.
- **Publishing framework:** Quarto.
- **Programming language:** R.
- **Version control:** Git.
- **GitHub organisation/account:** `UCLPG-MSC-SGDS`.
- **New GitHub repository:** `GEOG0125_2627`.

Use existing R packages and project dependencies wherever possible. Do not introduce unnecessary packages or change statistical methods.

## 3. Project Directories and Codex Workspace

### Original Project — Read Only

Folder: `GEOG0125`

Path:
`/Users/anwarmusah/Documents/Websites/GEOG0125`

This directory contains the original `.Rmd` files, datasets, HTML outputs and Bookdown configuration.

**Important:** Treat this directory as strictly read-only. Do not modify, rename, move, overwrite or delete any original files.

### New Quarto Project — Codex Working Directory

Folder: `GEOG0125_2627`

Path:
`/Users/anwarmusah/Documents/Websites/GEOG0125_2627`

This directory is the designated Codex workspace and the destination for the migrated Quarto project.

All new `.qmd` files, Quarto configuration files, required datasets, supporting assets and rendered HTML outputs must be placed here.

### Codex Workspace Requirements

1. Open `GEOG0125_2627` as the active project in the Codex macOS application.
2. Store this `AGENTS.md` file in the root of `GEOG0125_2627`.
3. Ensure Codex has read access to the original `GEOG0125` directory.
4. Perform all new file creation, editing and rendering within `GEOG0125_2627`.
5. Do not change the working directory to the original project for any operation that could modify its contents.
6. If Codex cannot access the original directory, report the issue and request guidance rather than attempting an alternative without permission.

## 4. Migration Workflow

**Follow the stages below sequentially. Do not execute the entire migration in a single operation.**

### Stage 1: Inspect and Prepare a Migration Plan

1. Read this `AGENTS.md` file in full.
2. Inspect the original `GEOG0125` Bookdown project without modifying any files.
3. Identify all `.Rmd` files and their chapter or practical ordering.
4. Examine Bookdown configuration files, including `_bookdown.yml` and `_output.yml`, where present.
5. Identify all datasets, figures, R scripts, bibliographies and other dependencies.
6. Identify internal links, cross-references, citations and navigation elements.
7. Identify potential compatibility issues between Bookdown and Quarto.
8. Produce a concise migration plan describing the proposed file structure, conversion steps and potential challenges.

**STOP: Do not begin Stage 2 until I have reviewed and explicitly approved the migration plan.**

### Stage 2: Migrate to Quarto

After receiving my approval:

1. Copy the required source materials into the new project directory.
2. Convert existing `.Rmd` files to `.qmd`.
3. Create an appropriate Quarto project configuration (`_quarto.yml`).
4. Preserve the original chapter or practical ordering and navigation structure.
5. Convert Bookdown-specific syntax and configuration to appropriate Quarto equivalents.
6. Preserve existing R code, exercises, explanations and analytical methods.
7. Update file paths and internal references where necessary.
8. Do not rewrite teaching content unless required for compatibility. Explain any substantive changes.

Where the original materials form a Bookdown book, prefer an equivalent Quarto book structure rather than a collection of unrelated HTML pages.

### Stage 3: Execute and Validate

1. Check that Quarto is installed and accessible through Positron.
2. Check that required R packages are available.
3. Identify and resolve migration-related errors.
4. Render the Quarto project to HTML.
5. Verify that figures, tables, code outputs, citations, links and navigation work correctly.
6. Check that datasets are loaded using valid paths.
7. Compare the new HTML outputs with the original Bookdown outputs for major content or formatting differences.
8. Report any unresolved warnings, errors or differences.

Do not silently remove code chunks or teaching content to make rendering succeed.

### Stage 4: Preview and Review in Positron

1. Open the new Quarto project in Positron, where supported.
2. Make the rendered HTML available for preview using Positron's Viewer or the appropriate Quarto preview mechanism.
3. Explain how to inspect the outputs in Positron if direct graphical interaction is unavailable.
4. Allow me to review the migrated materials before proceeding to GitHub publication.

**STOP: Do not proceed to Stage 5 without my explicit approval.**

### Stage 5: GitHub Repository and Publication

Once I have reviewed and approved the HTML outputs:

1. Check whether `GEOG0125_2627` already exists under `UCLPG-MSC-SGDS`.
2. If it does not exist, request my approval to create the repository.
3. Initialise Git in the new project directory if necessary.
4. Create an appropriate `.gitignore` file.
5. Ensure that temporary files, credentials, unnecessary build artefacts and restricted datasets are excluded.
6. Prepare a Git commit describing the migration.
7. Request my approval before pushing to GitHub.
8. Push the approved changes to the repository.

Do not enable GitHub Pages or other public publishing services without separate approval.

## 5. General Rules

- Preserve all original files in `GEOG0125`.
- Perform all modifications within `GEOG0125_2627`.
- Prefer R for existing analytical workflows.
- Use Quarto rather than Bookdown for the new project.
- Maintain the academic content and teaching objectives.
- Do not invent missing datasets, results or analytical outputs.
- Do not upload restricted or confidential teaching datasets without approval.
- Explain significant modifications and document unresolved issues.
- Do not commit, push or publish without my approval.
- Keep `AGENTS.md` in the root of the new project and include it in version control so that its instructions remain available for future Codex sessions.

## 6. Expected Deliverables

The completed migration should provide:

1. A functioning Quarto project in `GEOG0125_2627`.
2. Converted `.qmd` files corresponding to the original practicals.
3. A working `_quarto.yml` configuration.
4. Required datasets, figures and supporting assets.
5. Successfully rendered HTML outputs.
6. A short migration report documenting changes and outstanding issues.
7. A GitHub repository containing the approved migrated project, once publication is authorised.

**The migration is not considered complete until the HTML outputs have been reviewed and approved.**

