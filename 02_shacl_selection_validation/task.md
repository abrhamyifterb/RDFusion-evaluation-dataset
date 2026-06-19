# Scenario 2 — SHACL Selection, Validation, and Coverage

## Goal

Evaluate how RDFusion helps with SHACL validation, shape selection, validation noise reduction, SHACL mode visibility, and coverage inspection.

## Files

Open:

- `catalog-data.ttl`
- `shacl-shapes.ttl`

## Suggested steps

1. Open `catalog-data.ttl` and `shacl-shapes.ttl`.
2. First, inspect the validation result using the automatic/auto SHACL mode.
3. Check the SHACL mode indicator in the status bar. It should show whether validation is in automatic mode or custom/selected-shapes mode.
4. Open the VS Code Command Palette and run **RDFusion: Configure SHACL Selection**.
5. Wait for RDFusion to scan the workspace and list the available shapes.
6. Choose custom-mode and select the shapes focused on `dcat:Dataset` and `dcat:Distribution`, then apply the selection.
7. Confirm that the SHACL mode now indicates the custom/selected-shapes mode.
8. Return to `catalog-data.ttl` and compare the focused validation result with the auto-mode result.
9. Run **RDFusion: Show SHACL Coverage** and inspect which fields are covered by the selected shapes.

## RDFusion features to try

- SHACL validation diagnostics
- Status-bar SHACL mode indicator: automatic vs custom/selected shapes
- **RDFusion: Configure SHACL Selection**
- selected Dataset/Distribution-focused validation
- **RDFusion: Show SHACL Coverage**

## What to answer in the form

Report whether shape selection made the validation output easier to understand, whether the active SHACL mode was visible enough, and whether the difference between validation errors and coverage gaps was clear.
