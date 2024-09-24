# Getting Started With the Pipeline

This repository contains the pipeline codes for the neuronal mechanism analysis of burst generation and propagation under anesthesia detected by cortex-wide neural optoelectronic interface. This pipeline includes data pre-processing and analysis, organized by **Python**.

## Installation

Please install the dependencies using: 

​`pip install -r environment.txt`

## Datasets

* The entire dataset, which includes the extracted neuronal traces and electrophysiological signals of 5 mice, will be open-sourced after publication. The transgenic mice consisted of two types: Cx3Cr1-GFP mice (for microglia labeling) and Rasgrf2-2A-dCre/Ai148D mice (for neuronal labeling with GCaMP6f in layers 2/3).

## Usage

These codes are tested under Python 3.8.15. The pipeline consists of the following sections:

### 1. Data pre-processing

The '**/01_data_pre-processing**' folder consists of codes for processing the raw traces. 

  * '**/011_find_burst_timestamps.ipynb**': Select the timestamps of burst or suppression periods.

  * '**/012_data_processing_and_classification.ipynb**': Screening different types of neurons according to burst and suppression periods.
  <br/>

### 2. Burst generation analysis

The '**/02_burst_generation_analysis**' folder consists of codes for processing the raw traces. 

  * '**/011_find_burst_timestamps.ipynb**': 

  * '**/012_data_processing_and_classification.ipynb**':
  <br/>

### 3. Burst propagation analysis

The '**/03_burst_propagation_analysis**' folder consists of codes for processing the raw traces. 

  * '**/011_find_burst_timestamps.ipynb**': Select the timestamps of burst or suppression periods.

  * '**/012_data_processing_and_classification.ipynb**': Screening different types of neurons according to burst and suppression periods.
  <br/>

### 4. Other results

The '**/04_supplementary_figures**' folder consists of codes for processing the raw traces. 

  * '**/011_find_burst_timestamps.ipynb**': Select the timestamps of burst or suppression periods.

  * '**/012_data_processing_and_classification.ipynb**': Screening different types of neurons according to burst and suppression periods.
  <br/>
