# T2-Star_Analysis-Portfolio
Published Paper: https://www.mdpi.com/2035-8377/17/4/53

This repository presents the analysis and code used for the study titled "Combined MR volumetry and relaxometry reveals the olfactory system as a critical iron-dependent structure affected by radiation". The study investigates the effects of whole-brain irradiation on adult mice, focusing on T2* MRI metrics sensitive to iron accumulation. The repository provides a detailed breakdown of the analysis pipeline, from data preprocessing to statistical analysis and visualization.

Table of Contents
1. Introduction
2. Project Structure
3. Analyis Workflow
4. Results Highlights
5. Acknowledgments

Introduction:
This study explores the neuroanatomical impact of radiation-induced brain injury (RIBI), with an emphasis on the olfactory system as a sensitive iron-dependent structure. Using advanced T2* MRI relaxometry, over 600 brain regions were analyzed for significant changes in volume and iron accumulation a year post-radiation.

Project Structure:
The repository includes the following directories:

Data Loading: Scripts and sample data for importing MRI datasets and neuroanatomical labels.
Data Cleaning: Procedures for pre-processing raw T2* maps and volumetric data.
Feature Extraction: Code for generating regional T2* and volume metrics from MRI data.
Statistical Analysis: Python scripts leveraging libraries like Pandas, SciPy, and Seaborn for identifying statistically significant changes.
Visualization: Notebooks for creating heatmaps, z-score plots, and correlation analyses of affected regions.
Analysis Workflow
Data Loading:

Imported MRI datasets and aligned them with the P56 Mouse Brain atlas.
Applied high-order B0 shimming for field uniformity and registered anatomical images.
Preprocessing:

Generated T2* maps using a 2D multi-echo GRE sequence.
Co-registered maps to anatomical images to isolate neuroanatomical structures.
Statistical Analysis:

Conducted t-tests to identify regions with significant differences in volume and T2* relaxation.
Computed z-scores and performed correlation analysis to cross-reference affected regions.
Visualization:

Generated heatmaps of significant regions.
Highlighted the strong correlation between T2* relaxation and volume loss in the olfactory system.
Results Highlights
Identified 18 neuroanatomical subregions with significant changes in both volume and T2* relaxation.
The olfactory system exhibited the most pronounced changes, potentially linking iron accumulation to cognitive decline post-radiation.


Acknowledgments:
This research was supported by NIH grant R21CA270742, the Radiation Research Foundation, and the University of Iowa's Holden Comprehensive Cancer Center.
