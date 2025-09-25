# 🧠 Neural Network Avalanche Forecasting – STA5073Z Assignment 1

## 📍 University of Cape Town  
**Department of Statistical Sciences**  
**STA5073Z – Data Science for Industry 2025**  
**Assignment 1: Neural Networks**  
**Due Date:** 29 September 2025, 12 PM (noon)

---

## 🧩 Project Overview

This group project explores the use of neural networks to model avalanche hazard forecasts using a 15-year dataset from the [Scottish Avalanche Information Service (SAIS)](https://www.sais.gov.uk/). Our group has been assigned **Problem A**:  
> **Construct and evaluate a neural network model that predicts the *forecasted avalanche hazard* (FAH).**

The dataset includes daily avalanche forecasts and observations across six regions in Scotland, along with topographical, meteorological, and snowpack-related predictors.

---

## 📊 Dataset Description

The dataset contains the following variables:

- `Date`: Date of forecast  
- `Area`: One of six forecasting regions  
- `FAH`: Forecast Avalanche Hazard (target variable)  
- `OAH`: Observed Avalanche Hazard  
- **Predictor Set 1**: `longitude`, `Incline` (location/topography)  
- **Predictor Set 2**: `Air.Temp`, `Summit.Wind.Speed` (weather conditions)  
- **Predictor Set 3**: `Max.Temp.Grad`, `Snow.Temp` (snowpack integrity)

---

## 🎯 Objectives

### Analytical Goals
- Clean and preprocess the dataset
- Create training, validation, and test splits
- Fit and evaluate neural network models
- Assess predictor importance and model performance

### Workflow Goals
- Collaborate effectively using GitHub (branches, pull requests)
- Render a reproducible scientific paper using Quarto
- Host the paper and supporting materials on GitHub Pages
- Critically assess the use of LLMs (e.g., ChatGPT) in the workflow

---

## 📁 Deliverables

1. **Scientific Report** (≤ 4500 words) hosted on GitHub Pages  
2. **Group Presentation** (20 minutes) for SAIS management  
3. **Amathuba Submission**:
   - `STUDENTID.txt`: Links to GitHub repo and website  
   - `STUDENTID.html`: Rendered scientific paper  
   - `STUDENTID.qmd`: Quarto source file with embedded resources

---

## 🤖 Use of AI

We actively incorporate a large language model (LLM) to assist with:
- Code generation and debugging
- Report drafting and editing
- Prompt design and critical reflection on LLM performance

A dedicated webpage will document our LLM usage and evaluation.

---

## 👥 Group Members & Contributions

Each member’s role and contributions will be documented in the scientific paper, following authorship guidelines from [PLOS ONE](http://journals.plos.org/plosone/s/authorship#loc-author-contributions).

---

## 📚 Resources

- [Scientific Paper Writing Guide – Nature](https://www.nature.com/scitable/topicpage/scientific-papers-13815490)
- [Jari Saramäki’s Blog Series on Paper Writing](https://jarisaramaki.fi/2017/04/28/why-can-writing-a-paper-be-such-a-pain/)
- [How to Write a Scientific Paper – ConservationBytes](https://conservationbytes.com/2012/10/22/how-to-write-a-scientific-paper/)

---

## ⚠️ Notes

- All code and analysis must be reproducible (`set.seed()` used)
- Submissions must follow the plagiarism policy and include a signed declaration
- Python is accepted, but R is recommended for this assignment

---

