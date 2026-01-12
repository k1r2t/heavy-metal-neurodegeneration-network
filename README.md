# Computational Network-Based Identification of Heavy Metal–Associated Hub Genes and Pathways in Neurodegenerative Disorders

## Overview
This repository contains data, network files, and results supporting a computational toxicogenomics study investigating how heavy metal exposure contributes to neurodegenerative and neurodevelopmental disorders through shared molecular networks.

The analysis integrates curated chemical–gene–disease associations with protein–protein interaction networks to identify central hub genes and conserved biological pathways associated with heavy metal neurotoxicity.

## Diseases Studied
- Alzheimer’s disease (AD)
- Parkinson’s disease (PD)
- Amyotrophic Lateral Sclerosis (ALS)
- Multiple Sclerosis (MS)
- Autism Spectrum Disorder / ADHD

## Heavy Metals Analyzed
- Lead (Pb)
- Mercury (Hg)
- Cadmium (Cd)
- Chromium (Cr)
- Arsenic (As)
- Zinc (Zn)

## Workflow Summary
1. Gene–disease–chemical associations were retrieved from the Comparative Toxicogenomics Database (CTD).
2. Shared genes between heavy metals and neurological disorders were identified.
3. Protein–protein interaction networks were constructed using STRING (confidence ≥ 0.8).
4. Network visualization and hub gene prioritization were performed in Cytoscape.
5. Hub genes were ranked using Maximal Clique Centrality (MCC).
6. Functional enrichment analysis (GO and KEGG) was conducted using STRING.
7. Findings were validated using peer-reviewed literature.

## Key Findings
- Identification of 101 shared genes linking heavy metal exposure and neurological disorders.
- Prioritization of 10 hub genes: TP53, TNF, IL1B, IL10, INS, BCL2, IFNG, PTGS2, PPARG, HMOX1.
- Enrichment of immune-inflammatory signaling, oxidative stress response, apoptosis, mitochondrial dysfunction, and synaptic regulation pathways.

## Repository Contents
- `data/`: Curated gene lists and CTD-derived datasets.
- `network_analysis/`: STRING and Cytoscape network files.
- `enrichment_analysis/`: KEGG and GO pathway results.
- `figures/`: High-resolution network and enrichment figures.
- `poster/`: Conference poster PDF.
- `supplementary_tables/`: Hub gene and pathway tables.

## Status
Manuscript under review / in preparation.  
This repository supports poster presentation and scientific discussion.

## Contact
**Author:** Kritika Sharma 
**Email:** kritika7475@gmail.com
