# Scenario 4 — RDF Maintenance and Triple Management

## Goal

Use RDFusion Triple Management features to inspect and maintain two RDF catalogue snapshots.

## Files

Open:

- `catalog-snapshot-a.ttl`
- `catalog-snapshot-b.ttl`

## Suggested steps

Use the VS Code Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`) and search for the exact RDFusion command names below. Try at least two RDFusion actions.

1. Open one snapshot and run **RDFusion: Filter Triples By Subject Only**. For example, filter by a dataset subject such as `https://example.org/rdfusion-eval/dataset/air-quality`.
2. Run **RDFusion: Filter Triples By Predicate Only**. For example, filter by `dcat:downloadURL` or `dcat:keyword`.
3. Run **RDFusion: Turtle Formatter** or **RDFusion: Group By Subject** to improve readability.
4. Run **RDFusion: Merge Files** to merge one with the other. The merged result should open in a new editor tab.
5. Run **RDFusion: Generate VoID** and inspect the generated metadata.
6. Run **RDFusion: Toggle IRI Shortening** to inspect long IRIs more easily. You can also try **RDFusion: Set IRI Shorten Length**.
7. Run **RDFusion: Decode Turtle Unicode Escapes** to inspect escaped text such as `Café`.
8. Optional, if the dataset folder is opened as a Git repository: use **RDFusion: RDF Diff Compare with HEAD** or **RDFusion: RDF Diff Compare with Ref...** on a changed Turtle file, to see the difference between previous commit versions of the file.

## About diff/comparison

RDFusion's RDF Diff commands are Git-based. They compare the current Turtle file with a Git version/reference, not two different Turtle files.

## RDFusion features to try

- filtering triples
- sorting/grouping/formatting Turtle
- merging RDF files
- generating VoID metadata
- visual IRI shortening
- Unicode normalization
- optional Git-based RDF diff

## What to answer in the form

Report which maintenance actions you completed and whether RDFusion reduced manual copying/editing or external-tool use.
