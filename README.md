# STA207_final_project

## Background

In this project, we analyze a subset of data collected by Steinmetz et al. (2019). While this document provides the basic understanding of the experiments, it is highly recommended that one consults the original publication for a more comprehensive understanding in order to improve the quality of the analysis report.

In the study conducted by Steinmetz et al. (2019), experiments were performed on a total of 10 mice over 39 sessions. Each session comprised several hundred trials, during which visual stimuli were randomly presented to the mouse on two screens positioned on both sides of it. The stimuli varied in terms of contrast levels, which took values in {0, 0.25, 0.5, 1}, with 0 indicating the absence of a stimulus. The mice were required to make decisions based on the visual stimuli, using a wheel controlled by their forepaws. A reward or penalty was subsequently administered based on the outcome of their decisions. The activity of the neurons in the mice's visual cortex was recorded during the trials and made available in the form of spike trains, which are collections of timestamps corresponding to neuron firing. 

In this project, we focus specifically on the spike trains of neurons in the visual cortex, from the onset of the stimuli to 0.4 seconds post-onset. In addition, we only use five sessions (Sessions 1 to 5) from two mice (Cori and Frossman).

## Questions of Interest

The primary objectives of this project is to understand how the neural activity in the visual cortex is modulated by the two stimuli and how this information can be utilized to predict the outcome of the trial. To be specific, two questions of interest are as follows. 
1. How do neurons in the visual cortex respond to the stimuli presented on the left and right? (35 pts)
2. How to predict the outcome of each trial using the neural activities and stimuli? (5 pts)

For Question 1, various methodologies can be employed to formulate statistically sound hypotheses that align with the research objective. In particular, we would like to know if the left and right stimuli have additive effects on the neural responses (i.e., whether the interaction effect exists). A suggested model and hypothesis can be found in the provided outline below. However, **alternative models or hypotheses may also be proposed**, but it is necessary to consult with the teaching assistants and obtain written approval from the instructor no later than March 6th.

For Question 2, a variety of models may be employed for building the predictive model and the only criteria is to have the best prediction performance. Here the prediction performance is evaluated by the sensitivity and specificity evaluated on the first 100 trials in Session 1. Additionally, it may be possible to enhance the prediction performance by thoroughly analyzing the rewarding mechanism described in Steinmetz et al. (2019).
