# Getting Started With the Pipeline

This repository contains the pipeline codes for the neuronal mechanism analysis of burst generation and propagation under anesthesia detected by cortex-wide neural optoelectronic interface. This pipeline includes data processing and analysis, organized by **Python**.

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

  * '**/012_data_processing_and_classification.ipynb**': Screen different types of neurons according to burst and suppression periods.
  <br/>

### 2. Burst generation analysis

The '**/02_burst_generation_analysis**' folder consists of codes for analyzing the burst generation mechanisms at neuronal level. 

  * '**/021_active_neurons_in_fixed_duration.ipynb**': Calculate the neuron numbers during the fixed durations of burst and suppression periods.

  * '**/022_duration_vs_active_neurons.ipynb**': Fit the relationship between burst (or suppression) duration and the number of active neurons.

  * '**/023_neuron_map_plot.ipynb**': Map the distribution of active neurons in physical space.

  * '**/024_sorting_neurons_and_statistics.ipynb**': Categorize neurons and display the category features.

  * '**/025_neurons_transition.ipynb**': Quantifying the transition process between different types of neurons.
  <br/>

### 3. Burst propagation analysis

The '**/03_burst_propagation_analysis**' folder consists of codes for analyzing the burst propagation mechanisms at neuronal level. 

  * '**/031_plot_ecog_and_calc_trace.ipynb**': Demonstrate the dynamics of calcium activity and electrophysiological signals.

  * '**/032_multi_channels_analysis.ipynb**': Display the multichannel electrophysiological traces over time with statistical propagation characteristics.
  <br/>

### 4. Other results

The '**/04_supplementary_figures**' folder consists of code examples for generating the analysis results of other mice. 

  * '**/mxx_multi_channels_analysis.ipynb**': The multichannel analysis for other mice.

  * '**/mxx_sorting_neurons_and_statistics.ipynb**': The neuron categorization for other mice.
  <br/>
