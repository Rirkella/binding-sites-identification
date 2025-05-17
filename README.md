# Searching for motifs in genomes: DNA binding sites of transcription factors / Recherche de motifs dans les génomes : les sites de fixation à l’ADN des facteurs de transcription  

## Contexte / Context

Ce projet a été réalisé dans le cadre du cours **LO3IN402 - Projet BIO-info** à l'Université de la Sorbonne.  
L’objectif était de **trouver les motifs d’ADN** reconnus par des facteurs de transcription à partir de données **ChIP-seq** chez *Candida glabrata*.

---

This project was carried out as part of the **LO3IN402 - BIO-info Project** at Sorbonne University.  
The goal was to **discover DNA motifs** recognized by transcription factors from **ChIP-seq** data in *Candida glabrata*.

## Description / Description

Le projet est structuré en plusieurs étapes :

1. Analyse exploratoire des séquences ChIP-seq fournies.
2. Application de trois algorithmes :
   - **Hash Table** : recherche des k-mers fréquents.
   - **Median String** : recherche de la séquence la plus proche.
   - **Suffix Tree (approche simplifiée)** : recherche des motifs communs exacts.
3. Analyse des motifs trouvés avec :
   - Visualisation de **logos de séquences**.
   - Validation avec **RSAT PeakMotif**.
   - Recherche de la **fréquence des motifs** dans les promoteurs du génome.

---

The project is structured in several steps:

1. Exploratory analysis of provided ChIP-seq sequences.
2. Application of three algorithms:
   - **Hash Table**: search for frequent k-mers.
   - **Median String**: search for the closest sequence.
   - **Suffix Tree (simplified approach)**: search for exact common motifs.
3. Motif analysis with:
   - **Sequence logo** visualization.
   - Validation with **RSAT PeakMotif**.
   - **Motif frequency** search in genome promoters.

## Fichiers inclus / Included Files

- `project.ipynb` : Notebook Python avec tout le pipeline d’analyse et le rapport.
- `presentation_Pdr1.pdf` : Présentation orale sur le facteur **Pdr1** et ses résultats.
- `donnees.zip` : Archive contenant les fichiers **FASTA** des séquences ChIP-seq et des promoteurs.


