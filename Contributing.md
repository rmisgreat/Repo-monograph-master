# Contributor Guide

Welcome! To ensure audit compliance and research integrity, please read and follow these guidelines.

## File Naming Convention

`[Part]-[Section]_[Version]_[Model]_[Date].md`  
Example: `I-A.3_v1.1_GPT5_2025-10-23.md`

- Use ISO date format (YYYY-MM-DD).
- Update version and model for each phase output.

## Six-Phase Workflow

1. **Architect**: Expand outline into blueprint
2. **Author**: Write technical draft
3. **Pedagogue**: Refine tone/readability
4. **Technician**: Audit equations/derivations
5. **Researcher**: Empirical fact-check/citations
6. **Integrator/Synthesizer**: Integrate logs, final polish

**See `charter/OPERATIONAL_CHARTER_v2.2.md` for details.**

## Revision Logging

- Log all changes in `revision-ledger/REVISION_LEDGER.md`
- Generate SHA-256 checksums for outputs/logs

## Data Integrity

- All empirical claims must have DOI or official URL
- Update `empirical-database/EMPIRICAL_DATABASE_LEDGER.md` per protocol

## Backups

- Weekly repo backup via GitHub Actions (`.github/workflows/backup.yml`)
- Offsite replication every 30 days (manual or automated)

## Templates

- Use templates in `templates/` for outputs and logs.
- Never overwrite original files; always create a new version.

Thank you for supporting precision research!
