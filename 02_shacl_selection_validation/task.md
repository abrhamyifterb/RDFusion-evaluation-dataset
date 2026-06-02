# Scenario 2 — SHACL Selection, Validation, and Coverage

## Situation

A catalogue maintainer is checking a DCAT-AP-style catalogue record. A broader SHACL shape set is available, but the current review is mainly about the Dataset and Distribution metadata.

## Your task

Open:

- `catalog-data.ttl`
- `shapes-full.ttl`

Review the data against the broader shape set first. Then use RDFusion's SHACL selection support to focus on the Dataset and Distribution shapes.

## RDFusion features to try

This scenario is intended to exercise SHACL validation, SHACL shape selection, validation-noise reduction, and SHACL coverage. The broader shape set includes some extra checks so that selected validation can be compared with a noisier result.
