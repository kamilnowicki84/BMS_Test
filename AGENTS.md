# Project Rules

This repository contains a BMS engineering project.

## Source documentation

The directory `00_Source_Docs/` contains original project documentation.

Rules:
- Do not modify, rename or delete files in `00_Source_Docs/`.
- Read only files required for the current task.
- Do not reproduce passwords, private keys, credentials or other secrets.
- Do not commit source documentation to Git.
- If sensitive information is found, report that it exists without copying it.

## Working directories

- `01_Analysis/` — documentation analysis
- `02_System_Architecture/` — proposed BMS architecture
- `03_IO/` — point lists, I/O, Modbus/BACnet mappings
- `04_Implementation/` — implementation plan
- `05_Commissioning/` — commissioning procedures and checklists
- `06_Scripts/` — scripts and automation tools

## General rules

- Do not delete files without explicit approval.
- Before major changes, explain the proposed change.
- Prefer Markdown and CSV for generated documentation.
- Keep changes small and logically grouped.
- Do not store credentials in the repository.