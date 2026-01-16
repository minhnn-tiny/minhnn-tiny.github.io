---
title: 'MANDO-LLM: Heterogeneous Graph Transformers with Large Language Models for Smart Contract Vulnerability Detection'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - me
  - Hoang H. Nguyen
  - Long Le Thanh
  - Zahra Ahmadi
  - Thanh-Nam Doan
  - Daoyuan Wu
  - Lingxiao Jiang

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-12-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-12-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['journal-article']

# Publication name and optional abbreviated publication name.
publication: ACM Transactions on Software Engineering and Methodology
publication_short: TOSEM

abstract: Detecting vulnerabilities in smart contracts is vital for the security and reliability of decentralized apps. To facilitate vulnerability detection, contract codes, including bug patterns, are represented as heterogeneous graphs with various nodes and edges, like control-flow and function-call graphs. However, existing graph learning techniques struggle with large, complex graphs. This paper presents MANDO-LLM, a novel framework that combines heterogeneous graph transformers (HGTs) with large language models (LLMs) for detecting vulnerabilities in smart contracts represented as heterogeneous contract graphs built upon control-flow and call graphs. MANDO-LLM uses LLMs to capture code features from control-flow and call data, customizes HGTs to learn embeddings with specific node-edge meta relations, and employs classifiers for vulnerability detection in Solidity code at both contract and line levels. Our evaluation shows that MANDO-LLM significantly outperforms existing methods on real-world large-scale imbalanced datasets, with F1-score improvements from 0.59\% to 80.72\% at the contract level. It is also one of the first effective methods for identifying line-level vulnerabilities, with performance boosts ranging from 3.09\% to over 95\% across different vulnerability types. MANDO-LLM’s versatility allows easy retraining for various vulnerabilities without needing manually defined patterns.

# Summary. An optional shortened abstract.
summary: MANDO-LLM is a new framework for smart contract security that combines the semantic understanding of Large Language Models (LLMs) with the structural analysis of Heterogeneous Graph Transformers (HGTs).

tags:
  - vulnerability detection
  - smart contracts
  - source code
  - heterogeneous graph learning
  - graph
  - transformer
  - graph embedding
  - large language model
  - code embedding

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1145/3765751

# Custom links
links:
  - type: pdf
    url: "/publications/mando-llm/final.pdf"
  - type: code
    url: https://github.com/MANDO-Project/ge-sc-llm
  # - type: dataset
  #   url: https://github.com/HugoBlox/hugo-blox-builder
  # - type: slides
  #   url: https://www.slideshare.net/
  # - type: source
  #   url: https://github.com/MANDO-Project/ge-sc-llm
  - type: demo
    url: https://mandoguru.com

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.

slides: ""
---
 