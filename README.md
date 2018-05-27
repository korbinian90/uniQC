# uniQC - Unified NeuroImaging Quality Control (uniQC) toolbox

## Overview
The challenge of unified and comprehensive quality control (QC) in (functional) MRI results from the vast amount of artefact sources combined with the complex processing pipelines applied to the data. Beyond standard image quality measures, MRI sequence development is often in need of flexible diagnostic tools to test diverse hypotheses on artefact origin, such as hardware fluctuations, k-space spikes, or subject movement. These tests are usually performed in a sequential order, where one outcome informs the next evaluation. This necessitates fast switching between mathematical image operations and interactive display of multi-dimensional data to assess image properties from a range of different perspectives. Additionally, for complex image analysis pipelines, as employed, e.g., in fMRI, direct access to the standard analysis packages is required to ultimately evaluate functional sensitivity of new sequence prototypes. Here, we present the uniQC toolbox that provides seamless combination of algebraic matrix operations, image processing, visualisation options and data provenance in an intuitive, object-oriented framework using MATLAB, and interfacing SPM for all fMRI-related pre-processsing and statistical analysis steps. Therein, processing of 4D image time series data is generalised to an arbitrary number of dimensions to handle data from multiple receiver coils, multi-echo or phase fMRI data in a unified framework along with classical statistical analysis and powerful visualisation options.
## Installation

Download the current version of SPM from http://www.fil.ion.ucl.ac.uk/spm/software/ and add the code directory to you MATLAB path. Then clone or download the uniQC repository and recursively add this to your MATLAB path. Type `I = MrImage` to test your setup.
