---
title: "Overcoming Difficulty in Obtaining Dark-skinned Subjects for Remote-PPG by Synthetic Augmentation"
collection: publications
permalink: /publication/2021-06-10-overcoming-difficulty-in-obtaining
excerpt: 'Here we show a first attempt to overcome the lack of dark-skinned subjects in r-PPG datasets by synthetic augmentation.'
date: 2021-06-10
venue: 'arXiv preprint'
paperurl: 'https://arxiv.org/abs/2106.06007'
---

Camera-based remote photoplethysmography (rPPG) provides a non-contact way to measure physiological signals (e.g., heart rate) using facial videos. Recent deep learning architectures have improved the accuracy of such physiological measurement significantly, yet they are restricted by the diversity of the annotated videos. The existing datasets MMSE-HR, AFRL, and UBFC-RPPG contain roughly 10%, 0%, and 5% of dark-skinned subjects respectively. The unbalanced training sets result in a poor generalization capability to unseen subjects and lead to unwanted bias toward different demographic groups. In Western academia, it is regrettably difficult in a university setting to collect data on these dark-skinned subjects. Here we show a first attempt to overcome the lack of dark-skinned subjects by synthetic augmentation. A joint optimization framework is utilized to translate real videos from light-skinned subjects to dark skin tones while retaining their pulsatile signals. In the experiment, our method exhibits around 31% reduction in mean absolute error for the dark-skinned group and 46% improvement on bias mitigation for all the groups, as compared with the previous work trained with just real samples.

[Download paper here](https://arxiv.org/pdf/2106.06007)

### Citation

Y. Ba, Z. Wang, D. Karinca, O. D. Bozkurt, A. Kadambi, "Overcoming Difficulty in Obtaining Dark-skinned Subjects for Remote-PPG by Synthetic Augmentation," arXiv:2106.06007 (June 10, 2021)