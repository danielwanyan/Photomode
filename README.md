# Photomode

Runtime rule assets for the Aicolate Photomode low-quality workflow.

## Active rule file

`rules/photo_low_quality_rules_v1.json`

The workflow fetches this JSON at runtime, sends it through a deterministic Rules Brain Code Node, and injects only the compact dynamic context into the single multimodal reviewer.

Do not wire the complete raw JSON directly into the reviewer prompt.
