<div align="center">
  
# UMD (Universal Media Toolkit)

UMD is a Python CLI tooling project focused on reliable, compliance-aware media workflow automation.

![Python](https://img.shields.io/badge/python-3.9+-blue)
![License](https://img.shields.io/badge/license-Apache%202.0-green)
[![Repo](https://img.shields.io/badge/source-Codeberg-blue?logo=git)](https://codeberg.org/nk2552003/umd)

</div>
## Project Snapshot

- 60+ stars
- 20+ forks
- Original repository encountered automated moderation flags due to category classification.
- Project now maintained at https://codeberg.org/nk2552003/umd

> "The repo got stars, forks, and then an account suspension. So we kept the engineering, removed risky phrasing, and turned chaos into clean documentation."

## Suspension Context

This repository gained traction quickly, then hit automated moderation.

1. Community growth crossed 60+ stars and 20+ forks.
2. Automated policy systems flagged the repository category.
3. The account was suspended pending review.
4. No security or integrity issues were identified in the project.
5. The project was migrated, legal scope was clarified, and docs were rewritten with compliance-first language.

## What UMD Is

UMD is an engineering-focused command-line toolkit for:

- Input validation and normalization
- Batch job orchestration
- Metadata handling
- Format conversion workflows
- Error handling, retries, and logging
- Cross-platform automation scripts

## What UMD Is Not

UMD is not positioned as:

- A rights-bypass utility
- A DRM circumvention tool
- A policy-evasion script
- A "grab everything from anywhere" product

## Legal-Safe Positioning

Use UMD only with assets you are authorized to process:

- Personal or owned files
- Public domain material
- Open-licensed content
- Explicitly permitted internal or client assets

Users are responsible for following local law, content rights, and service terms.

## Recruiter Quick Scan

If you are reviewing this project as portfolio work, evaluate it for:

- CLI product design and developer experience
- Modularity and separation of concerns
- Reliability patterns in automation workflows
- Practical scripting for macOS, Linux, and Windows
- Readability and maintainability in a production-style Python codebase

## Architecture Overview

```text
umd/
├── cli/              # Argument parsing and command routing
├── core/             # Workflow orchestration and domain logic
├── utils/            # Shared helpers, validation, and utilities
├── scripts/          # Setup, install, and update scripts
├── documentations/   # Technical and operational docs
└── README.md
```

## Setup

### Quick Install

```bash
git clone https://codeberg.org/nk2552003/umd.git
cd umd
./scripts/install.sh
```

### Windows

```bat
git clone https://codeberg.org/nk2552003/umd.git
cd umd
scripts\install.bat
```

### Prerequisites

- Python 3.9+
- Git
- FFmpeg (recommended)

Check Python version:

```bash
python3 --version
```

## Quick Evaluation Commands

```bash
umd --version
umd --help
```

## Development

```bash
git clone https://codeberg.org/nk2552003/umd.git
cd umd
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## Documentation

- Installation: documentations/INSTALLATION.md
- Usage: documentations/USAGE.md
- Architecture: documentations/ARCHITECTURE.md
- Changelog: documentations/CHANGELOG.md

## Contributing

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Open a pull request.

## License

Apache License 2.0. See LICENSE for details.

## Support

- Issues: https://codeberg.org/nk2552003/umd/issues
- Repository: https://codeberg.org/nk2552003/umd
