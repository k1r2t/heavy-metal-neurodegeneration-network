# Computational Network-Based Identification of Heavy Metal–Associated Hub Genes and Pathways in Neurodegenerative Disorders

---

## 🔍 Overview

This repository provides **data, network files, and visual results** from a computational toxicogenomics study investigating how **heavy metal exposure** contributes to **neurodegenerative and neurodevelopmental disorders** through **shared molecular interaction networks**.

The analysis integrates **chemical–gene–disease associations** with **protein–protein interaction (PPI) networks** to identify **central hub genes** and **conserved biological pathways** implicated in heavy metal–induced neurotoxicity.

---

## 🧠 Neurological Conditions Analyzed

- Alzheimer’s disease (AD)  
- Parkinson’s disease (PD)  
- Amyotrophic Lateral Sclerosis (ALS)  
- Multiple Sclerosis (MS)  
- Autism Spectrum Disorder / ADHD  

---

## ⚙️ Heavy Metals Included

- Lead (Pb)  
- Mercury (Hg)  
- Cadmium (Cd)  
- Chromium (Cr)  
- Arsenic (As)  
- Zinc (Zn)  

---

## 🧬 Analysis Workflow (Conceptual Overview)

CTD → Shared gene identification → STRING PPI construction →  
Cytoscape network analysis → Hub gene ranking (MCC) →  
GO & KEGG functional enrichment → Literature validation

---

## 🌐 Global Protein–Protein Interaction Network

The global PPI network reveals dense molecular connectivity among genes shared between heavy metal exposure and neurological disorders, indicating coordinated regulatory interactions.

![Global PPI Network](Git_Hub/Results_img/global_network_commongenes.svg)

---

## ⭐ Hub Gene Identification

Hub genes were prioritized using **Maximal Clique Centrality (MCC)**, revealing a tightly connected regulatory core within the network.

**Top 10 hub genes identified:**

TP53, TNF, IL1B, IL10, INS,  
BCL2, IFNG, PTGS2, PPARG, HMOX1

### STRING-Based Hub Gene Network

![Hub Gene Network](Git_Hub/Results_img/hub_gene_STRING.svg)

### MCC Top 10 Hub Gene Ranking

![MCC Top 10 Hub Genes](Git_Hub/Results_img/Sheet1_MCC_top10.png)

---

## 🧩 Disease–Gene Interaction Network

The disease–gene interaction network highlights shared hub gene associations across multiple neurological disorders, supporting a common molecular framework underlying heavy metal–induced neurotoxicity.

![Disease–Gene Interaction Network](Git_Hub/Results_img/gene_disease.png)

---

## 📊 Functional Enrichment Analysis

GO and KEGG enrichment analyses demonstrate significant overrepresentation of biological pathways related to neuronal damage and disease progression.

### KEGG Pathway Enrichment (Common Genes)

![KEGG Enrichment – Common Genes](Git_Hub/Results_img/enrichment_KEGG_common_gene.svg)

### KEGG Pathway Enrichment (Hub Genes)

![KEGG Enrichment – Hub Genes](Git_Hub/Results_img/enrichment_KEGG_hubgene.svg)

**Major enriched biological processes include:**
- Immune and inflammatory signaling  
- Oxidative stress response  
- Apoptosis and mitochondrial dysfunction  
- Protein homeostasis and synaptic regulation  

These findings indicate conserved molecular mechanisms linking heavy metal exposure to diverse neurological disorders.

---

## 📚 Literature Validation

To assess the **biological relevance** of the computationally identified hub genes, a structured **literature validation** was performed using peer-reviewed studies.

The validation evaluates:
- Reported associations between **hub genes** and neurological disorders  
- Evidence linking **heavy metals** to neurotoxic mechanisms  
- Consistency between **network-derived results** and known biological functions  

### 🔎 Validation Highlights
- Hub genes such as **TP53, TNF, IL1B, IL10, BCL2, PTGS2, and PPARG** are extensively reported in the literature to regulate:
  - Neuroinflammation  
  - Oxidative stress  
  - Mitochondrial dysfunction  
  - Neuronal apoptosis and survival signaling  

### 📄 Literature Validation Table

A comprehensive **literature validation table** summarizing:
- Hub gene  
- Associated neurological disorder  
- Heavy metal relevance  
- Biological role  
- Supporting references  

is provided here:

➡️ **[Literature Validation Table (PDF)](Git_Hub/Literature%20Validation.pdf)**

> *The table consolidates experimental, clinical, and mechanistic evidence supporting the identified hub genes.*

---

## 📑 References

All literature sources used for validation and background research are compiled here:

➡️ **[References (PDF)](Git_Hub/References.pdf)**

---

## 📁 Repository Structure


---

## 👁️ How to Use This Repository

- Browse **`Git_Hub/Results_img`** for final network and enrichment visuals  
- Open **`Git_Hub/Cytoscape_visual`** files in Cytoscape for interactive exploration  
- Use **`Git_Hub/String_data`** for downstream analysis or independent validation  
- Refer to **Literature Validation** for biological interpretation support  

---

## 📌 Scope & Status

- Repository contains **data, figures, network files, and literature validation**
- No executable code is included
- Intended for **scientific reference and interpretative support**

---

## 📫 Contact

**Author:** Kritika Sharma  
**Email:** kritika7475@gmail.com
