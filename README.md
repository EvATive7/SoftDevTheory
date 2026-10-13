# SoftDevTheory

Course repository: https://github.com/higolab/SoftDevTheory

My fork: https://github.com/EvATive7/SoftDevTheory

## Top Ten Open-Source Tools for a Reproducible Python Workflow

This list covers different stages of a Python project: tracking code changes, managing dependencies, checking correctness, automating analyses, sharing an environment, and preserving research inputs. Each tool addresses a distinct part of the workflow. The links point to the projects or their official documentation.

1. **[Git](https://github.com/git/git)** - Records changes as commits and supports branches and merges, making it possible to trace how a project evolved and return to an earlier version.
2. **[Snakemake](https://snakemake.readthedocs.io/en/stable/)** - Defines analysis steps and their dependencies in a Python-based workflow, helping collaborators rerun a documented process with consistent inputs and software requirements.
3. **[uv](https://github.com/astral-sh/uv)** - Manages Python packages, project environments, and dependency lockfiles, helping collaborators recreate the same dependency versions.
4. **[Ruff](https://github.com/astral-sh/ruff)** - Checks Python code for common problems and formats it consistently, making changes easier to read and review.
5. **[pytest](https://docs.pytest.org/en/stable/)** - Runs automated tests and reports failing assertions, helping developers check behavior after a change and detect regressions.
6. **[mypy](https://github.com/python/mypy)** - Uses Python type annotations to check for incompatible types before running a program, improving the clarity of interfaces between components.
7. **[pre-commit](https://pre-commit.com/)** - Manages Git hooks that run checks before a commit, helping collaborators apply the same formatting and validation rules.
8. **[JupyterLab](https://github.com/jupyterlab/jupyterlab)** - Combines notebooks, code, explanations, and visual outputs in an interactive environment, making exploratory analysis easier to document and share.
9. **[Podman](https://podman.io/)** - Runs applications in containers, allowing a project to describe and share its runtime environment more consistently across machines.
10. **[DVC](https://dvc.org/)** - Adds data version control to Git-based projects, helping connect a code revision with the datasets used in an experiment.

## Revision and Review

An AI-assisted self-review recommended adding Snakemake to cover workflow automation. This recommendation was incorporated by replacing Code - OSS, keeping the list at ten entries. Snakemake describes the analysis steps, uv manages Python dependencies, and DVC tracks research data, so these entries address complementary parts of reproducibility.

The Snakemake description was checked against its official documentation. The list was reviewed for distinct purposes, clear explanations, and source links. The contribution source for this revision is AI-assisted self-review.
