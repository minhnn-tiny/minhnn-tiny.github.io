---
title: 'MANDO-GURU: vulnerability detection for smart contract source code by heterogeneous graph embeddings'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Hoang H. Nguyen
  - me
  - Hong-Phuc Doan
  - Zahra Ahmadi
  - Thanh-Nam Doan
  - Lingxiao Jiang

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-11-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-11-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['conference-paper']

# Publication name and optional abbreviated publication name.
publication: the 30th ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering

publication_short: ESEC/FSE

abstract: Smart contracts are increasingly used with blockchain systems for high-value applications. It is highly desired to ensure the quality of smart contract source code before they are deployed. This paper proposes a new deep learning-based tool, MANDO-GURU, that aims to accurately detect vulnerabilities in smart contracts at both coarse-grained contract-level and fine-grained line-level. Using a combination of control-flow graphs and call graphs of Solidity code, we design new heterogeneous graph attention neural networks to encode more structural and potentially semantic relations among different types of nodes and edges of such graphs and use the encoded embeddings of the graphs and nodes to detect vulnerabilities. Our validation of real-world smart contract datasets shows that MANDO-GURU can significantly improve many other vulnerability detection techniques by up to 24\% in terms of the F1-score at the contract level, depending on vulnerability types. It is the first learning-based tool for Ethereum smart contracts that identify vulnerabilities at the line level and significantly improves the traditional code analysis-based techniques by up to 63.4\%. Our tool is publicly available at https://github.com/MANDO-Project/ge-sc-machine. A test version is currently deployed at http://mandoguru.com, and a demo video of our tool is available at http://mandoguru.com/demo-video.


# Summary. An optional shortened abstract.
summary: The paper introduces MANDO-GURU, a deep learning tool that utilizes heterogeneous graph attention neural networks on control-flow and call graphs to accurately detect smart contract vulnerabilities at both the contract and line levels. Validations on real-world datasets demonstrate that MANDO-GURU significantly outperforms existing techniques, offering F1-score improvements of up to 24% for contract-level detection and up to 63.4% for line-level detection.

tags:
  - heterogeneous graphs
  - graph neural networks
  - vulnerability detection
  - smart contracts
  - Ethereum blockchain

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1145/3540250.3558927

# Custom links
links:
  - type: pdf
    url: "/publications/mando-guru/final.pdf"
  - type: code
    url: https://github.com/MANDO-Project/ge-sc-machine
  - type: demo
    url: https://mandoguru.com
  - type: video
    url: https://www.youtube.com/watch?v=x2-KqndqDc8

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
 