# Scenario 3 — Vocabulary and Context-Aware Authoring

## Situation

A catalogue maintainer has a valid draft record, but the metadata is still under-described. Your job is to add the missing RDF terms in a way that fits common DCAT/DCMI/FOAF/SKOS modelling.

This scenario is **not** a validation-repair and is **not** about SHACL. The goal is to see whether RDFusion's completion, hover, prefix handling, and JSON-LD context awareness help you decide which terms to add while authoring.

## Your task

Open:

- `dataset-to-complete.ttl`
- `dataset-context-to-complete.jsonld`

Use RDFusion completion and hover while adding the missing fields.

As you work, pay attention to whether RDFusion helps you distinguish similar terms, for example `dct:title` versus other DCMI terms, `dcat:downloadURL` versus `dcat:accessURL`, or `dcat:theme` versus `dcat:keyword`.

## What this scenario should demonstrate

- Term completion while authoring Turtle predicates and RDF classes.
- Hover metadata for vocabulary terms before choosing them.
- Prefix-aware remote vocabulary assistance for declared namespaces.
