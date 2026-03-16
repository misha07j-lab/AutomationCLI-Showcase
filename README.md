# Automation CLI Toolkit

Production-ready C# command-line utilities for data cleanup, file transformation, lightweight ETL, log parsing, and small automation workflows.

## What This Toolkit Solves

This toolkit is built for practical automation tasks where lightweight, reliable command-line utilities are more useful than heavyweight platforms.

It helps with:
- cleaning inconsistent CSV datasets
- transforming files between business-friendly formats
- running lightweight ETL steps
- parsing logs and extracting useful signal
- automating repeatable file-based data tasks

## Who It Is For

This toolkit is relevant for:
- small businesses
- operations workflows
- analysts working with exported data
- developers building internal tools
- freelancers delivering small automation solutions
- clients who need practical data and process utilities without unnecessary system complexity

## Toolkit Overview

### DataCleaner
Clean and normalize CSV datasets before import, review, or downstream processing.

Typical outcomes:
- trimmed values
- duplicate removal
- required column validation
- row filtering
- cleaner, more consistent data

Repository: [DataCleaner](https://github.com/misha07j-lab/DataCleaner)

### CsvJsonConverter
Convert structured data between CSV and JSON quickly and predictably.

Typical outcomes:
- easier format conversion
- smoother handoff between systems
- automation-friendly file transformation
- reliable CLI behavior for repeatable workflows

Repository: [CsvJsonConverter](https://github.com/misha07j-lab/CsvJsonConverter)

### MiniETL-CLI
Run lightweight ETL-style workflows on tabular data without building a full data platform.

Typical outcomes:
- filtering records
- transforming values
- processing small recurring datasets
- creating simple repeatable data pipelines

Repository: [MiniETL-CLI](https://github.com/misha07j-lab/MiniETL-CLI)

### LogParser
Parse raw log files, isolate useful information, and turn noisy text into actionable output.

Typical outcomes:
- filtering records
- extracting signal from logs
- reducing manual review effort
- creating automation-friendly outputs for follow-up processing

Repository: [LogParser](https://github.com/misha07j-lab/LogParser)

## Typical Use Cases

Examples of problems this toolkit can help solve:
- clean CSV exports before importing them into another system
- convert files between formats used by different tools or teams
- run small recurring ETL steps on operational data
- parse log files for troubleshooting or reporting
- automate repetitive file-processing tasks with predictable command-line tools

## Portfolio Cases

### 1. CSV Data Cleanup Before Import
**Problem:** exported CSV files often contain inconsistent values, duplicates, missing structure, or formatting noise.

**What this solves:**
- trim and normalize raw values
- remove duplicate rows
- validate required columns
- prepare cleaner datasets before import into another system

**Relevant tool:** [DataCleaner](https://github.com/misha07j-lab/DataCleaner)

---

### 2. File Format Transformation Between Systems
**Problem:** teams and tools often exchange data in different formats, creating friction in handoff and automation.

**What this solves:**
- convert CSV to JSON
- convert JSON to CSV
- simplify data handoff between tools
- create repeatable format-conversion steps for operational workflows

**Relevant tool:** [CsvJsonConverter](https://github.com/misha07j-lab/CsvJsonConverter)

---

### 3. Lightweight ETL for Small Operational Workflows
**Problem:** many recurring data tasks need filtering and transformation, but do not justify building a full ETL platform.

**What this solves:**
- filter tabular records
- transform small datasets
- process recurring operational exports
- create lightweight repeatable ETL-style steps

**Relevant tool:** [MiniETL-CLI](https://github.com/misha07j-lab/MiniETL-CLI)

---

### 4. Log Parsing and Signal Extraction
**Problem:** raw log files are noisy and time-consuming to review manually.

**What this solves:**
- filter relevant records
- reduce manual log review effort
- isolate actionable signal
- prepare outputs for troubleshooting, reporting, or follow-up automation

**Relevant tool:** [LogParser](https://github.com/misha07j-lab/LogParser)

---

### 5. Small Custom Automation Utilities
**Problem:** many internal workflows need narrow, reliable utilities instead of large complex systems.

**What this solves:**
- create focused CLI-first internal tools
- automate repetitive file and data tasks
- combine utility logic into repeatable workflows
- support practical small-scale automation delivery

**Relevant foundation:** Automation CLI Toolkit

## Why This Toolkit

The toolkit is positioned around practical delivery, not experimental demos.

Key characteristics:
- production-ready repositories
- consistent CLI-oriented approach
- predictable exit-code behavior
- self-contained release assets
- utility-first architecture
- suitable for repeatable automation work and small custom tooling engagements

## Repository Map

- **AutomationCLI-Showcase** — canonical public entry point for the toolkit
- **DataCleaner** — CSV cleanup and normalization
- **CsvJsonConverter** — CSV ↔ JSON conversion
- **MiniETL-CLI** — lightweight ETL processing
- **LogParser** — log parsing and filtering

## Quick Navigation

- [AutomationCLI-Showcase](https://github.com/misha07j-lab/AutomationCLI-Showcase)
- [DataCleaner](https://github.com/misha07j-lab/DataCleaner)
- [CsvJsonConverter](https://github.com/misha07j-lab/CsvJsonConverter)
- [MiniETL-CLI](https://github.com/misha07j-lab/MiniETL-CLI)
- [LogParser](https://github.com/misha07j-lab/LogParser)

## Delivery Direction

This toolkit is suitable as a foundation for:
- custom CLI utilities
- small internal automation tools
- lightweight data-processing workflows
- repeatable operational automation tasks
- practical client-facing automation work

## Roadmap Direction

Automation CLI Toolkit is the utility layer.

The longer-term direction is to build on top of this foundation:
- reusable automation workflows
- higher-level orchestration
- AI-assisted execution over tools and data
- future vertical automation offers for specific business scenarios

## Status

Current public lineup:
- DataCleaner
- CsvJsonConverter
- MiniETL-CLI
- LogParser

`AutomationCLI-Showcase` is the canonical public entry point for the toolkit.

