# AgenticMindX RPA Exception Analyzer

A practical utility for RPA developers. It reads a sanitized CSV export of automation run events, groups failures by exception type, and creates a summary to support troubleshooting.

## Quick start
Requires Python 3.10 or newer.

```bash
python src/main.py
```

Input: `data/sample_run_events.csv`  
Output: `output/exception_summary.csv`

## Features
- Groups failed events by exception type.
- Counts occurrences and lists example workflow names.
- Keeps source logs unchanged.
- Uses fictional sample data.

## Privacy and operational notes
Remove credentials, personal data, hostnames, and business-sensitive details before analyzing or publishing logs. This tool is an aid for investigation, not an automated root-cause determination.

## Next steps
Add UiPath Orchestrator API ingestion with secure secret storage, environment-specific filters, and links to run details.
