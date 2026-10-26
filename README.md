# CEST MRI Tools

**Browser-Based Tools for Chemical Exchange Saturation Transfer (CEST) MRI Data Analysis**

https://doi.org/10.5281/zenodo.23670168

**Developed by Zinia Mohanta, PhD**  
Department of Radiology, Kennedy Krieger Institute
## Overview

Chemical Exchange Saturation Transfer (CEST) MRI enables noninvasive investigation of tissue chemistry, molecular contrast, and physiological processes. However, CEST data processing often requires specialized software, programming expertise, and computational resources.

**CEST MRI Tools** is an open-source initiative aimed at simplifying CEST MRI data visualization and preliminary analysis through lightweight, browser-based applications.

These tools are designed for researchers working with preclinical MRI data, particularly Bruker MRI acquisitions, and aim to enable rapid evaluation of imaging data directly on scanner workstations or personal computers.

The long-term objective is to develop accessible, reproducible, and user-friendly computational tools that support both preclinical research and the broader translation of CEST MRI.

## Available Tools

### 1. CEST Quick Analyzer

**File:** `CEST_Quick_Analyzer_Designed_By_Zinia_Moha...html`

A browser-based utility for rapid visualization and exploratory analysis of CEST MRI data.

**Key capabilities:**
- Loading and visualization of supported Bruker MRI datasets
- CEST image and frequency-offset exploration
- Region-of-interest (ROI) selection and analysis
- Z-spectrum visualization for suitable acquisitions
- Preliminary evaluation of dynamic and interleaved CEST acquisitions
- Rapid assessment of imaging data during experiments

**Intended application:** Preliminary data quality assessment, visualization of CEST contrast, and exploratory analysis during scanner sessions.

### 2. WASSR B0 Viewer

**File:** `WASSR_B0_Viewer_by_ZM.html`

A specialized utility for evaluating B0 field inhomogeneity using Water Saturation Shift Referencing (WASSR) acquisitions.

**Key capabilities:**
- Loading supported Bruker WASSR acquisitions
- Visualization of reference MRI images
- Estimation and visualization of spatial B0 frequency shifts
- ROI-based WASSR spectrum inspection
- Evaluation of magnetic field homogeneity
- Preliminary assessment of frequency-offset corrections

**Intended application:** B0 field assessment and quality control before quantitative CEST analysis.

## Getting Started

### Requirements

- A modern web browser, such as Google Chrome or Microsoft Edge
- Supported Bruker MRI acquisition files
- A computer with sufficient memory for the selected imaging dataset

### Instructions

1. Download the desired `.html` file from this repository.
2. Open the file using a compatible web browser.
3. Use the application's file or folder selection interface to load the relevant Bruker MRI data.
4. Select the appropriate experiment and imaging dataset.
5. Use the available visualization and analysis controls to inspect your data.

The applications are intended to operate through a browser without requiring MATLAB or Python installation.

**Note:** Browser file permissions, supported acquisition structures, and available functions may vary. Not all Bruker datasets have been validated.

## Applications

These tools are being developed to support:

- Preclinical CEST MRI experiments
- B0 field mapping and quality assurance
- CEST phantom characterization
- Molecular contrast agent development
- Dynamic CEST imaging
- Rapid scanner-side assessment of experimental data
- Accessible training and education in CEST MRI analysis

## Development Status

**Status: Early-stage research software / ongoing development**

The current applications are exploratory tools and continue to undergo testing and refinement.

Planned improvements include:

- Broader Bruker acquisition compatibility
- Improved handling of continuous and interleaved CEST acquisitions
- Enhanced ROI-based quantitative analysis
- Improved dynamic CEST visualization
- More robust data export and quality-control features
- Extended support for quantitative CEST metrics and analysis workflows

## Limitations

- The tools are intended for research and educational purposes only.
- They are not validated for clinical diagnostic use.
- Compatibility with all Bruker acquisition formats is not guaranteed.
- Quantitative results should be independently verified before scientific reporting.
- The tools are under active development, and some functions may be experimental.

## Contributions and Feedback

Feedback, suggestions, bug reports, and contributions from researchers working in CEST MRI, magnetic resonance imaging, and computational imaging are welcome.

Please use GitHub Issues to report problems or suggest improvements.

When reporting an issue, please include the browser version, acquisition type, a description of the problem, and reproducible steps where possible. Do not upload identifiable or confidential imaging data.

## Citation

If you use these tools in your research, please acknowledge:

Mohanta, Z. *CEST MRI Tools: Browser-Based Utilities for CEST MRI Data Visualization and Analysis.* GitHub software repository.

A formal software citation with a version number and persistent identifier will be provided in a future release.

## License

MIT License.

Copyright © 2026 Zinia Mohanta.

See the `LICENSE` file for the complete license terms.

## Contact

**Zinia Mohanta, PhD**  
Staff Research Scientist  
Kennedy Krieger Institute 
For questions, feature requests, or collaborations, please open an issue in this repository.
