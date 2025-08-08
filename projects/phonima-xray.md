# Phonima Medical Image Classifier for X-ray

**Year:** 2025  
**Domain:** Healthcare AI — Medical Imaging  
**Stack:** Python, PyTorch, OpenCV, Grad-CAM, AWS S3

## Overview
AI-powered classifier to detect chest X-ray abnormalities using transfer learning with explainability via Grad-CAM heatmaps.

## Key Features
- Preprocessing pipeline (DICOM/PNG)
- Transfer learning with fine-tuning
- Grad-CAM visualizations for clinician trust
- Batch inference and export to PACS-compatible formats

## Architecture
Data ingestion → preprocessing → training (PyTorch) → evaluation → explainability (Grad-CAM) → REST inference API.

## Results
High diagnostic accuracy on validation set; interpretable outputs for review; packaged as a containerized inference service.

## Links
- Code: #
- Live Demo: #
- Deck/Docs: #
