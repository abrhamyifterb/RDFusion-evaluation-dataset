# Scenario 1 — RDF Validation and Repair

## Goal

Check two draft catalogue records before publication and repair validation/data-quality issues. This scenario is about RDF/Turtle/JSON-LD validation and repair, **not SHACL**.

## Files

Open:

- `catalog-record.ttl`
- `catalog-record.jsonld`

## Suggested steps

1. Open `catalog-record.ttl`.
2. Review RDFusion diagnostics in the editor.
3. Repair as many issues as you can. The intended issue types include:
   - misspelled vocabulary terms;
   - an undeclared prefix;
   - invalid XSD date;
   - suspicious IRI/URL schemes;
   - duplicate triples or repeated values.
4. For an undeclared prefix, try RDFusion's prefix quick fix. RDFusion can suggest a prefix declaration when the prefix is available from prefix.cc.
5. For remote vocabulary typos, try RDFusion's vocabulary typo quick fix where available.
6. Open `catalog-record.jsonld` and repeat the validation/repair process.

## Important note about VS Code Fix and AI suggestions

VS Code may show generic **Fix**, **Generate Code**, or AI-assisted actions. Those are not RDFusion features.

For this scenario, RDFusion contributions include RDFusion diagnostics and RDFusion quick fixes namely:

- remote vocabulary typo fixes;
- missing-prefix fixes when the prefix can be resolved from prefix.cc.

Other repairs need to be made manually.

## RDFusion features to try

- Turtle validation
- JSON-LD validation
- diagnostics in the editor
- prefix diagnostics and prefix quick fix from prefix.cc
- XSD/date validation
- IRI scheme validation
- remote vocabulary typo diagnostics/quick fixes where available
- duplicate detection

## What to answer in the form

Report whether RDFusion helped you find and understand the issues, and note any cases where you were confused or not clear with RDFusion functionality.
