# RDFusion-evaluation-dataset

This repository contains the prepared dataset/fixtures for the RDFusion user evaluation.

RDFusion is a Visual Studio Code extension for RDF editing. The evaluation uses small DCAT/DCAT-AP-style files so that participants can try RDF validation, SHACL selection, vocabulary/context-aware editing, Triple Management, and JSON-LD processing in a controlled way.

## Estimated time

The full evaluation should take about **35–45 minutes**.

## Prerequisite knowledge

You do not need to be an RDF expert, but you should be at least slightly comfortable with:

- Visual Studio Code;
- basic RDF concepts such as subjects, predicates, objects, IRIs, literals, and prefixes;
- Turtle syntax;
- JSON-LD syntax;
- the idea of SHACL validation.


## Before you start

1. Install RDFusion in Visual Studio Code through extensions (Ctrl + Shift + X) in VS Code.
2. Download this dataset as a ZIP file or clone it with Git.
3. Open the **top-level dataset folder** in VS Code. Do not open only one scenario file by itself.
4. Open the `task.md` file inside each scenario folder before starting that scenario.
5. Use the VS Code **Command Palette** (`Ctrl+Shift+P` / `Cmd+Shift+P`) and search for commands beginning with `RDFusion:`.

## Scenario overview

Each scenario folder contains a `task.md` file. Start there.

Complete the scenarios in order:

1. `01_validation_repair` — Turtle and JSON-LD validation/repair. This is not a SHACL task.
2. `02_shacl_selection_validation` — SHACL validation, shape selection, mode visibility, and coverage.
3. `03_vocabulary_context_editing` — vocabulary suggestions, hover, and JSON-LD context-aware authoring.
4. `04_triple_management` — RDF maintenance commands such as filtering, formatting, merging, VoID generation, IRI shortening, Unicode normalization, and optional Git-based RDF diff.
5. `05_jsonld_processing` — JSON-LD expansion, compaction, flattening, or framing.

# Source Notes

## Primary public source family

This repository contains the dataset fixtures for the RDFusion user evaluation.

The dataset is based on the DCAT/DCAT-AP data-catalogue metadata domain. It is designed for a controlled evaluation of RDFusion, not for DCAT-AP conformance testing.

Main public references:

- SEMICeu/DCAT-AP GitHub repository: https://github.com/SEMICeu/DCAT-AP
- DCAT-AP 3.0.1 specification: https://semiceu.github.io/DCAT-AP/releases/3.0.1/
- W3C DCAT Version 3: https://www.w3.org/TR/vocab-dcat-3/
- W3C SHACL Recommendation: https://www.w3.org/TR/shacl/
- W3C JSON-LD 1.1 Processing Algorithms and API: https://www.w3.org/TR/json-ld11-api/


## How participants should use this dataset

Participants should open the folder in Visual Studio Code and complete the scenarios in order.

## Notes

VS Code may show generic **Fix**, **Generate Code**, or AI-assisted actions depending on your editor setup. Those actions are VS Code or AI features, not RDFusion features. RDFusion has two quick fix, namely a remote vocabulary typo fix or a prefix fix resolved from prefix.cc or generate a placeholder prefix if not available in prefix.cc;