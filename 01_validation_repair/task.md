# Scenario 1 — RDF Validation and Repair

## Situation

A catalogue metadata record is being checked before publication. The same draft metadata is available in Turtle and JSON-LD.

This scenario is deliberately focused on non-SHACL validation. The records use local draft classes rather than `dcat:Catalog`, `dcat:Dataset`, `dcat:Distribution`, or `foaf:Agent`, so the SHACL shapes used in Scenario 2 should not target these files.

## Your task

Open:

- `catalog-record.ttl`
- `catalog-record.jsonld`

Review the files as you normally would before publishing or sharing RDF metadata. Use any other tools you normally use, and then use RDFusion where it helps,.

Look for validation or data-quality issues and make any repairs you think are needed. The issues are intentionally spread through the documents rather than concentrated in one statement.

## RDFusion features to try

This scenario is intended to exercise Turtle validation, JSON-LD validation, diagnostics, prefix checks, date/literal checks, IRI or URL scheme checks, remote vocabulary typo detection, duplicate detection, and JSON-LD-specific checks.

SHACL validation and shape selection are evaluated separately in Scenario 2.
