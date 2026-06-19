# Scenario 3 — Vocabulary and Context-Aware Authoring

## Goal

Add missing metadata using RDFusion vocabulary suggestions, hover information, prefix support, and JSON-LD context-aware editing.

This scenario is **not** a validation-repair task and is **not** about SHACL.

## Files

Open:

- `dataset-to-complete.ttl`
- `dataset-context-to-complete.jsonld`

## Suggested steps for the Turtle file

1. Open `dataset-to-complete.ttl`.
2. Read the comments in the file. They describe what to add and where to add it.
3. Do not simply copy terms from documentation first. Try typing a real prefix such as `dct:`, `dcat:`, or `skos:` and use RDFusion completion suggestions.
4. Use RDFusion hover information to understand suggested terms before choosing them.
5. Add the missing dataset metadata suggested in the comments, including:
   - a title from DCMI Terms;
   - a description from DCMI Terms;
   - keyword/theme metadata using DCAT/SKOS-style modelling;
   - a landing page;
   - a link to the distribution;
   - distribution metadata such as title, media type, download URL, access URL, byte size, and license.
6. The values to reuse are listed near the bottom of the Turtle file.

## Suggested steps for the JSON-LD file

1. Open `dataset-context-to-complete.jsonld`.
2. Add missing context mappings and properties for the same kind of dataset metadata.
3. Use RDFusion completion when typing compact IRIs such as `dct:` or `dcat:` inside the `@context`.
4. Add readable aliases where they make the JSON-LD easier to use, for example aliases for title, description, landing page, distribution, download URL, access URL, media type, byte size, and license.

## RDFusion features to try

- Term completion while typing predicates/classes
- hover information for vocabulary terms
- prefix-aware remote vocabulary suggestions
- workspace/local vocabulary suggestions

## What to answer in the form

Report whether RDFusion suggestions and hover details helped you understand which vocabulary terms to add, and whether they reduced the need to search documentation manually.
