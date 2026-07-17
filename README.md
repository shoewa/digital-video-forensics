# Digital Video Forensics and Metadata Security

## Overview
This project provides a Python-based forensic analysis workflow designed to investigate metadata leakage in high-quality digital creative assets. By analyzing EXIF data and file size metrics, this toolset distinguishes between manipulated and unaltered media, accelerating the identification of device anomalies and unauthorized modifications.

## Motivation
Digital media files inherently carry extensive metadata that can expose sensitive information about the source device, location, and creation environment. This project aims to demonstrate how data analysis techniques can be applied to forensic datasets to secure digital assets and verify their integrity.

## Dataset
This project utilizes a structured subset of the **IEEE Camera Model** dataset. The data involves simulated forensic extraction logs detailing EXIF data density, file metadata, and manipulation markers.

## Technical Stack
* **Language:** Python 3
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Seaborn, Matplotlib
* **Environment:** Jupyter Notebook

## Key Features
* **Automated Data Preprocessing:** Cleans and structures raw forensic extraction logs for analysis.
* **Anomaly Detection Logic:** Classifies files based on metadata stripping and modification signatures.
* **Visual Forensics:** Generates Seaborn-based visualizations to highlight discrepancies between authentic and manipulated files.

## Installation & Usage
1. Clone the repository:
   ```bash
   git clone [https://github.com/yourusername/digital-video-forensics.git](https://github.com/yourusername/digital-video-forensics.git)