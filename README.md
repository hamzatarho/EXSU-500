# EXSU 500 Team Project

**Course:** EXSU 500 — Fundamentals of Artificial Intelligence in Medicine  
**Program:** Surgical and Interventional Sciences (SIS)  
**Institution:** McGill University  
**Term:** Fall 2026  
**Repository created:** September 25, 2026

## Dataset
Dataset name: The Dresden Surgical Anatomy Dataset (DSAD) 

## Dataset source
Source: Kaggle  

[The Dresden Surgical Anatomy Dataset](https://www.kaggle.com/datasets/anindyamajumder/the-dresden-surgical-anatomy-dataset/data)

## Dataset licence
Licence: The original Dresden Surgical Anatomy Dataset is licensed under Creative Commons Attribution 4.0 International (CC BY 4.0) (https://creativecommons.org/licenses/by/4.0/) on its [Figshare release] (https://doi.org/10.6084/m9.figshare.21702600).

The [Kaggle mirror used in this project](https://www.kaggle.com/datasets/anindyamajumder/the-dresden-surgical-anatomy-dataset/data) displaysApache License 2.0. This mirror label differs from the original dataset license and is recorded here for transparency.

We acknowledge the original DSAD creators. This dataset is used for a non-commercial university research project and is not included in this repository. Any shared dataset imagges or masks will include attribution and a description of modifications.

*Dataset publication:*  
Carstens, M., et al. The Dresden Surgical Anatomy Dataset for Abdominal Organ Segmentation in Surgical Data Science. Scientific Data *10*, 3 (2023).  
*DOI:* [10.1038/s41597-022-01719-2](https://doi.org/10.1038/s41597-022-01719-2)

## Problem statement
This project investigates automated colon segmentation in laparoscopic surgical images using the Dresden Surgical Anatomy Dataset (DSAD) as the primary data source, a publicly available collection of surgical images with organ-level annotations. The objective is to train and compare several machine-learning models for delineating the colon at the pixel level.

The task is framed as binary semantic segmentation. Each input image is paired with a ground-truth mask that classifies every pixel as either colon or background. Each model is trained to predict this mask directly from the image, and performance is assessed by quantifying the agreement between its predictions and the ground-truth annotations.

Automated anatomical segmentation has potential clinical relevance for computer-assisted surgery. Because minimally invasive procedures depend on a camera view of the operative field, systems that can reliably identify and highlight relevant anatomy may improve intraoperative visual guidance and support surgical decision-making.

## Task type
Classification / segmentation / regression / etc.
