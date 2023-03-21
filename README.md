# STA207_final_project

## Background

In this project, we analyze a subset of data collected by Steinmetz et al. (2019). While this document provides the basic understanding of the experiments, it is highly recommended that one consults the original publication for a more comprehensive understanding in order to improve the quality of the analysis report.

In the study conducted by Steinmetz et al. (2019), experiments were performed on a total of 10 mice over 39 sessions. Each session comprised several hundred trials, during which visual stimuli were randomly presented to the mouse on two screens positioned on both sides of it. The stimuli varied in terms of contrast levels, which took values in {0, 0.25, 0.5, 1}, with 0 indicating the absence of a stimulus. The mice were required to make decisions based on the visual stimuli, using a wheel controlled by their forepaws. A reward or penalty was subsequently administered based on the outcome of their decisions. The activity of the neurons in the mice's visual cortex was recorded during the trials and made available in the form of spike trains, which are collections of timestamps corresponding to neuron firing. 

In this project, we focus specifically on the spike trains of neurons in the visual cortex, from the onset of the stimuli to 0.4 seconds post-onset. In addition, we only use five sessions (Sessions 1 to 5) from two mice (Cori and Frossman).

