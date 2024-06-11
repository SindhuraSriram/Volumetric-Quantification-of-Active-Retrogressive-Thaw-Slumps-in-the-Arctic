# Volumetric-Quantification-of-Active-Retrogressive-Thaw-Slumps-in-the-Arctic
This project utilizes high-resolution ArcticDEM data and advanced machine learning, specifically Mask R-CNN, to comprehensively map and volumetrically quantify retrogressive thaw slumps across the Arctic, demonstrating a significant correlation with increasing summer temperatures.
# README: Volumetric Quantification of Active Retrogressive Thaw Slumps in the Arctic

## Project Overview

This project aims to provide the first volumetric quantification of retrogressive thaw slumps (RTS) across the Arctic region. We utilize ArcticDEM data, machine learning techniques, and climate data to detect and map active RTS, offering insights into the impacts of climate change on permafrost terrains.

## Key Features

- **Comprehensive Dataset**: Analysis using high-resolution ArcticDEM (2m) time-dependent digital elevation models.
- **Machine Learning Integration**: Implementation of deep learning techniques (Mask R-CNN) for automated detection and mapping of RTS.
- **Pan-Arctic Scale**: Mapping and volumetric quantification covering the entire Arctic region.

## Main Findings

- **Detection**: 2,850 active RTS detected and mapped across the Arctic.
- **Volume Loss**: The total volume loss from these RTS is approximately \(327.6 \times 10^6\) m³ from 2012 to 2022.
- **Carbon Release**: Annual volume loss translates to a carbon release of \(3.85 \times 10^{-4}\) Pg C/year.
- **Temperature Correlation**: 30% of RTS show significant correlation (>=0.5) between volume loss and summer air temperature.

## Methodology

1. **Data Acquisition**:
   - Utilized ArcticDEM versions 3 and 4.1 for 2m resolution DEM data.
   - Climate data sourced from ERA5 and CRU datasets.

2. **Data Processing**:
   - Coregistration and adjustment of DEMs using bundle adjustment techniques.
   - Change detection algorithms to identify and quantify surface elevation changes over time.

3. **Machine Learning**:
   - Mask R-CNN model fine-tuned for RTS segmentation.
   - Multi-band input images including elevation change, total curvature, and time of change maps.

4. **Validation**:
   - Ground truth validation using field data and cross-referencing with previously published inventories.

## Usage

- **Data Access**: ArcticDEM data is available at [ArcticDEM](https://www.pgc.umn.edu/data/arcticdem/).
- **Scripts and Models**: Model training scripts and RTS classification models are provided for reproducibility and further research.

## Acknowledgements

This project is supported by NASA's Earth Surface and Interior Program and various other institutional grants and programs.

For detailed documentation and further information, please refer to the full research paper and supplementary materials.
