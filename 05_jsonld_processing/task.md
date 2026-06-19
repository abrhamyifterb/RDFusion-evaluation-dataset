# Scenario 5 — JSON-LD Processing and Inspection

## Goal

Run a JSON-LD processing operation from inside VS Code and inspect the result.

This scenario is about JSON-LD processing commands.

## Files

Open:

- `dcat-dataset.jsonld`
- `dcat-frame.json`

## Suggested steps

1. Open `dcat-dataset.jsonld`.
2. Use the VS Code Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`) and run one of:
   - **RDFusion: Expand JSON-LD**
   - **RDFusion: Compact JSON-LD**
   - **RDFusion: Flatten JSON-LD**
   - **RDFusion: Frame JSON-LD From Template**
3. If you choose framing, use `dcat-frame.json` as the frame/template when prompted.
4. Inspect the generated JSON-LD output in the new editor tab.
5. Note whether the output was easier to inspect inside VS Code compared with your usual JSON-LD workflow.

## RDFusion features to try

- JSON-LD expansion
- JSON-LD compaction
- JSON-LD flattening
- JSON-LD framing
- output inspection inside VS Code

## What to answer in the form

Report which JSON-LD operation you completed and whether RDFusion made the operation easier to run or inspect.
