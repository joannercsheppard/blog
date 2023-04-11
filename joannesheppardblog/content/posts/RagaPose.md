---
title: "Pose Estimation"
date: 2022-12-01T15:32:21+01:00
---

[Raga Pose Estimation](https://github.com/DurhamARC/raga-pose-estimation) comprises a set of tools to facilitate the use of pose estimation software for the analysis of human movement in music performance. It was developed with the study of Indian classical music in mind – hence the name – but can be applied to any other type of small musical ensemble. Raga Pose Estimation was developed by staff in the Music Department and Advanced Research Computing at Durham University, as part of the EU Horizon 2020 FET project EnTimeMent – Entrainment & synchronization at multiple TIME scales in the MENTal foundations of expressive gesture.

The project, which is available as a library and [Colab script](https://colab.research.google.com/github/DurhamARC/raga-pose-estimation/blob/master/RagaPoseEstimationColab.ipynb), utilizes the OpenPose tool to facilitate the analysis of musical performance. The Colab script does this by enabling the user to carry out pose estimation online, avoiding the need for a suitable local GPU. Post-processing functions turn the large numbers of JSON files (one per video frame) output by OpenPose into single CSV files per performer. Cropping and trimming of videos, applying confidence levels and smoothing functions to the output, are amongst the other functions that are built into a single process.
