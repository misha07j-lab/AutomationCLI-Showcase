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

## Portfolio Case Assets

### 1. Data Cleanup Workflow for Messy CSV Exports

**Client problem**  
Business exports often arrive as inconsistent CSV files with duplicate rows, extra spaces, missing required columns, and noisy formatting that makes import, reporting, or follow-up processing unreliable.

**What I built**  
A production-ready CSV cleanup workflow focused on preparing messy datasets for operational use. The solution is built around a CLI utility that standardizes values, removes duplicates, validates structure, and filters rows when needed.

**How it works**  
The workflow takes raw CSV input, applies cleanup rules, validates required columns, and produces a cleaner output file that is more consistent and safer to use in downstream systems or reporting steps.

**Typical input / output**  
- **Input:** raw CSV export from business software, spreadsheet, CRM, ERP, or manually edited source  
- **Output:** cleaned and normalized CSV ready for import, review, or further automation

**Business value**  
- reduces manual cleanup effort  
- improves import readiness  
- lowers risk of bad data entering downstream workflows  
- makes recurring CSV-based operations more repeatable

**Tools / stack**  
- C#  
- .NET CLI utility  
- CSV processing workflow  
- [DataCleaner](https://github.com/misha07j-lab/DataCleaner)

---

### 2. CSV to JSON Transformation for Integration Preparation

**Client problem**  
Teams frequently need to move data between tools that expect different formats. CSV exports are easy to produce, while many integrations, scripts, and APIs work better with JSON. Manual transformation creates friction and inconsistency.

**What I built**  
A lightweight format-transformation utility for converting structured data between CSV and JSON in a predictable, automation-friendly way. The focus is on fast conversion and reliable CLI behavior for repeatable operational use.

**How it works**  
The utility accepts CSV or JSON as input, applies the requested conversion, and produces the target format as output. This makes it easier to prepare datasets for system handoff, automation workflows, or integration-related preprocessing.

**Typical input / output**  
- **Input:** CSV export or JSON dataset from an internal tool, report, or intermediate processing step  
- **Output:** converted JSON or CSV file ready for scripting, integration preparation, or exchange between tools

**Business value**  
- reduces friction between systems and teams  
- standardizes format conversion in repeatable workflows  
- removes manual restructuring work  
- supports integration preparation and file-based automation

**Tools / stack**  
- C#  
- .NET CLI utility  
- CSV / JSON transformation  
- [CsvJsonConverter](https://github.com/misha07j-lab/CsvJsonConverter)

---

### 3. Lightweight ETL Workflow for Business Reporting

**Client problem**  
Many recurring reporting and operational tasks require filtering, transforming, and preparing tabular data, but the workload is too small to justify a full ETL platform. The result is usually repetitive manual processing in spreadsheets or ad hoc scripts.

**What I built**  
A lightweight ETL-style CLI workflow for small and medium operational datasets. The solution is designed to handle filtering and transformation steps in a structured, repeatable way without introducing heavyweight infrastructure.

**How it works**  
The workflow receives tabular input data, applies processing rules such as filtering and transformation, and returns an output dataset suitable for reporting, internal review, or the next automation step in a small pipeline.

**Typical input / output**  
- **Input:** CSV or tabular export from business operations, reporting flows, or internal systems  
- **Output:** filtered and transformed dataset ready for reporting, validation, or downstream processing

**Business value**  
- replaces repetitive manual preparation of reporting data  
- creates repeatable small-scale ETL steps  
- improves consistency of operational reporting flows  
- provides a practical middle layer between raw exports and final reporting use

**Tools / stack**  
- C#  
- .NET CLI utility  
- lightweight ETL processing  
- [MiniETL-CLI](https://github.com/misha07j-lab/MiniETL-CLI)

---

### 4. Log Parsing Utility for Operational Diagnostics

**Client problem**  
Raw log files are difficult to review manually because they contain too much noise. Troubleshooting and operational diagnostics often require isolating only the relevant signal, but manual review is slow and error-prone.

**What I built**  
A log-parsing utility for extracting useful information from raw logs and turning noisy text data into more actionable output. The solution is built for filtering, narrowing the signal, and supporting operational diagnostics or follow-up automation.

**How it works**  
The utility processes raw log files, applies filtering logic, and produces cleaner output that highlights the relevant records. This makes logs more useful for troubleshooting, reporting, or downstream automated handling.

**Typical input / output**  
- **Input:** raw application, service, or operational log files  
- **Output:** filtered log output with more relevant records and reduced noise

**Business value**  
- reduces manual log review time  
- improves signal extraction during diagnostics  
- helps structure raw operational data for follow-up use  
- supports faster troubleshooting and log-based automation steps

**Tools / stack**  
- C#  
- .NET CLI utility  
- log parsing and filtering workflow  
- [LogParser](https://github.com/misha07j-lab/LogParser)

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

