# Getting Started With the Pipeline

This repository contains the pipeline codes for the neuronal mechanism analysis of burst generation and propagation under anesthesia detected by cortex-wide neural optoelectronic interface. This pipeline includes data pre-processing and analysis, organized by **Python**.

## Installation

Please install the dependencies using: 

​`pip install -r environment.txt`

## Datasets

* The demo data is currently available on [OneDrive](xxxx). When using the demo data to test the codes, please change the name of the file folders in the codes according to the storage location of the data.
* The entire dataset with a total size of xx TB, which includes the extracted neuronal traces and electrophysiological signals of 5 mice, will be open-sourced after publication. The transgenic mice consisted of two types: Cx3Cr1-GFP mice (for microglia labeling) and Rasgrf2-2A-dCre/Ai148D mice (for neuronal labeling with GCaMP6f in layers 2/3).

## Usage

These codes are tested under Python 3.8.15. The pipeline consists of the following sections:

### 1. Data pre-processing

The '**/p1_dff0_extract**' folder consists of codes for calculating Δ*F/F* from the raw traces. 

* Extract Δ*F/F* of each stimulus for each indicator (for the analysis of odor responses):

  `python p1_dff0_extract/c1_dff0_stim.py `
