# Revisiting Supervised and Unsupervised Methods for Effort-Aware Cross-Project Defect Prediction

This repository is an online appendix for "Revisiting Supervised and Unsupervised Methods for Effort-Aware Cross-Project Defect Prediction"


## Abstract

Cross-project defect prediction (CPDP), aiming to apply defect prediction models built on source projects to a target project,
has been an active research topic. A variety of supervised CPDP methods and some simple unsupervised CPDP methods have been
proposed. In a recent study, Zhou et al. found that simple unsupervised CPDP methods (i.e., ManualDown and ManualUp) have a
prediction performance comparable or even superior to complex supervised CPDP methods. Therefore, they suggested that the
ManualDown should be treated as the baseline when considering non-effort-aware performance measures (NPMs) and the ManualUp
should be treated as the baseline when considering effort-aware performance measures (EPMs) in future CPDP studies. However, in
that work, these unsupervised methods are only compared with existing supervised CPDP methods using a small subset of NPMs, and
the prediction results of baselines are directly collected from the primary literatures. Besides, the comparison has not considered other
recently proposed EPMs, which consider context switches and developer fatigue due to initial false alarms. These limitations may not
give a holistic comparison between the supervised methods and unsupervised methods. In this paper, we aim to revisit Zhou et al.’s
study. To the best of our knowledge, we are the first to make a comparison between the existing supervised CPDP methods and the
unsupervised methods proposed by Zhou et al. in the same experimental setting when considering both NPMs and EPMs. We also
propose an improved supervised CPDP method EASC and make a further comparison with the unsupervised methods. According to
the results on 82 projects in terms of 11 performance measures, we find that when considering NPMs, EASC can achieve prediction
performance comparable or even superior to unsupervised method ManualDown in most cases. Besides, when considering EPMs,
EASC can statistically significantly outperform the unsupervised method ManualUp with a large improvement in terms of Cliff’s delta in
most cases. Therefore, the supervised CPDP methods are more promising than the unsupervised method in practical application
scenarios, since the limitation of testing resource and the impact on developers cannot be ignored in these scenarios.
