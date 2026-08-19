---
# Leave the homepage title empty to use the site title
title: ''
date: 2026-08-19
type: landing

sections:

  - block: markdown
    content:
      title: ''
      subtitle: ''
      text: |
        # Understanding tumours across space and scale.

        We combine spatial biology, computational pathology and single-cell genomics to understand how tumours are organised, evolve and interact with their microenvironment.

    design:
      columns: '1'

  - block: markdown
    content:
      title: Research
      subtitle: ''
      text: |
        ## 01 — Spatial tumour ecosystems

        Mapping cellular states and interactions across space.

        ## 02 — Computational pathology & AI

        Connecting tissue morphology with molecular phenotype.

        ## 03 — Tumour evolution

        Reconstructing how cancers change across time, treatment and space.

    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: Recent Work
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
---
