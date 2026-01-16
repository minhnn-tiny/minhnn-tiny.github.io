---
title: 'MANDO-HGT: Heterogeneous Graph Transformers for Smart Contract Vulnerability Detection'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Hoang H. Nguyen
  - me
  - Chunyao Xie
  - Zahra Ahmadi
  - Daniel Kudenko
  - Thanh-Nam Doan
  - Lingxiao Jiang

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2023-05-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-05-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['conference-paper']

# Publication name and optional abbreviated publication name.
publication: IEEE/ACM 20th International Conference on Mining Software Repositories

publication_short: MSR

abstract: Smart contracts in blockchains have been increasingly used for high-value business applications. It is essential to check smart contracts' reliability before and after deployment. Although various program analysis and deep learning techniques have been proposed to detect vulnerabilities in either Ethereum smart contract source code or bytecode, their detection accuracy and scalability are still limited. This paper presents a novel framework named MANDO-HGT for detecting smart contract vulnerabilities. Given Ethereum smart contracts, either in source code or bytecode form, and vulnerable or clean, MANDO-HGT custom-builds heterogeneous contract graphs (HCGs) to represent control-flow and/or function-call information of the code. It then adapts heterogeneous graph transformers (HGTs) with customized meta relations for graph nodes and edges to learn their embeddings and train classifiers for detecting various vulnerability types in the nodes and graphs of the contracts more accurately. We have collected more than 55K Ethereum smart contracts from various data sources and verified the labels for 423 buggy and 2,742 clean contracts to evaluate MANDO-HGT. Our empirical results show that MANDO-HGT can significantly improve the detection accuracy of other state-of-the-art vulnerability detection techniques that are based on either machine learning or conventional analysis techniques. The accuracy improvements in terms of F1-score range from 0.7% to more than 76% at either the coarse-grained contract level or the fine-grained line level for various vulnerability types in either source code or bytecode. Our method is general and can be retrained easily for different vulnerability types without the need for manually defined vulnerability patterns.


# Summary. An optional shortened abstract.
summary: The paper introduces MANDO-HGT, a framework designed to improve the accuracy and scalability of vulnerability detection in Ethereum smart contracts. By converting source code or bytecode into heterogeneous contract graphs (HCGs) and utilizing customized heterogeneous graph transformers (HGTs), the method effectively learns embeddings to classify vulnerabilities at both the coarse-grained contract level and the fine-grained line level.

tags:
  - vulnerability detection
  - smart contracts
  - source code
  - bytecode
  - heterogeneous graph learning
  - graph transformer

# Display this page in the Featured widget?
featured: false

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1109/MSR59073.2023.00052

# Custom links
links:
  - type: pdf
    url: "/publications/mando-hgt/final.pdf"
  - type: code
    url: https://github.com/MANDO-Project/ge-sc-transformer
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
 