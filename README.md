# Final Project of the Statistics Course – MBA in AI, Data Science and Big Data for Business (IBMEC): ENADE 2017 Data Analysis

![Status: Completed – Score 10/10] 

# Complete Report and Interactive Visualization:
This project aims to analyze the ENADE 2017 dataset as part of the final evaluation for the Statistics for Data Science course in the MBA in AI, Data Science and Big Data for Business at IBMEC.
The final report (HTML) contains all R code, charts, and statistical analyses required for the assignment.

**ACCESS THE INTERACTIVE REPORT HERE:**
[Projeto Final - Relatório ENADE (HTML)] (https://heitorfb10.github.io/enade_projeto_final_estatistica_mba_ibmec/projeto_final_estatistica_ibmec_v4.html)

## Objective and Analytical Context

The main objective of this work is to apply **Descriptive and Inferential Statistics** techniques to analyze the ENADE 2017 microdata, focusing on the **Control and Automation Engineering program.**
The analysis aims **to identify performance disparities** and answer the following hypothesis:
**Is there evidence that socioeconomic (Race/Color) and geographic (Region) variables cause statistically significant differences in students’ scores?**

## Methodology and Tools
Tool / Technique	Purpose
Programming Language / Environment	R (RStudio)
Variable Transformation	case_when() to label 17 columns (e.g., code 1 for North).
Data Cleaning	na.omit() to ensure statistical quality of the sample.
Descriptive Statistics	summarise() with Mode, skewness, kurtosis (distribution shape).
Main Visualization	Faceted Box Plots (facet_wrap) to compare Scores by Race within each Region.
Frequency Analysis	Stacked Bar Charts (geom_bar(position="fill")) to visualize satisfaction proportions.
Final Report	RMarkdown (output using rmdformats::readthedown).
---
