# Semantic Vault

[![ko](https://img.shields.io/badge/lang-한국어-red.svg)](README.ko.md)

A public Korean-language Obsidian vault dataset for testing the [Obsidian 3D Semantic Graph](https://github.com/hyungrae0907/obsidian-3d-semantic-graph) plugin. This repository contains only Markdown notes designed for embedding-based semantic clustering and 3D layout evaluation.

## Overview

| Item | Value |
|------|-------|
| Topics | 25 |
| Notes per topic | 30 |
| Total notes | 750 |
| Format | Obsidian Markdown (`.md`) |
| Language | Korean |

## Topics

- Health
- Science
- Travel
- Cooking
- Music & Art
- Artificial Intelligence
- Philosophy
- Crossover
- Programming
- Economics
- Psychology
- History
- Mathematics
- Literature
- Environment & Ecology
- Space & Astronomy
- Sports
- Film & Media
- Education
- Law & Politics
- Architecture & Design
- Linguistics
- Agriculture & Food
- Energy & Climate
- Games & Interaction

## Note Structure

Each note follows a consistent format:

- YAML frontmatter with category and tags
- Body text of approximately 300–500 characters
- Wikilinks to related notes in the "Related Notes" section

This structure is suitable for testing the following characteristics in embedding-based semantic similarity analysis:

- Dense cluster formation among notes within the same topic
- Intermediate placement of notes at topic boundaries
- Correlation between wikilinks and semantic similarity
- Separation and cohesion of UMAP-based 3D layouts

## Repository Policy

This repository is organized for public distribution.

- **Included:** `README.md`, `README.ko.md`, Markdown notes in topic folders
- **Excluded:** `.obsidian`, plugin files, cache, local settings, generation scripts

## Getting Started

1. Clone this repository.
2. Open it as a vault in Obsidian.
3. Set your OpenAI API key in the 3D Semantic Graph plugin settings.
4. Generate embeddings and explore the 3D graph.

## Expected Results

- 25 topics should appear as semantically distinct clusters.
- Similar notes should be placed closer together in 3D space.
- Crossover notes may appear at connection points between multiple clusters.
- You can compare the differences between link structure and embedding-based distances.

## License

This dataset is provided for testing and research purposes.
