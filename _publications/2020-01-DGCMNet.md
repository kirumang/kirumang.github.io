---
title: "DGCM-Net: Dense Geometrical Correspondence Matching Network for Incremental Experience-based Robotic Grasping"
collection: publications
permalink: /publication/2020-01-DGCMNet.md
excerpt: 'Matching global and local correspodences densly for tranferring grasp poses from a previous success to a new object'
date: 2020-01-15
venue: 'arXiv preprint'
paperurl: 'https://arxiv.org/abs/2001.05279'
---
This article presents a method for grasping novel objects by learning from experience. Successful attempts are remembered and then used to guide future grasps such that more reliable grasping is achieved over time. To generalise the learned experience to unseen objects, we introduce the dense geometric correspondence matching network (DGCM-Net). This applies metric learning to encode objects with similar geometry nearby in feature space. Retrieving relevant experience for an unseen object is thus a nearest neighbour search with the encoded feature maps. DGCM-Net also reconstructs 3D-3D correspondences using the view-dependent normalised object coordinate space to transform grasp configurations from retrieved samples to unseen objects. In comparison to baseline methods, our approach achieves an equivalent grasp success rate. However, the baselines are significantly improved when fusing the knowledge from experience with their grasp proposal strategy. Offline experiments with a grasping dataset highlight the capability to generalise within and between object classes as well as to improve success rate over time from increasing experience. Lastly, by learning task-relevant grasps, our approach can prioritise grasps that enable the functional use of objects.

[Download paper](https://arxiv.org/abs/2001.05279)

[Code (RosNode)](https://rgit.acin.tuwien.ac.at/v4r/dgcm-net)

[![DGCM-Net](https://img.youtube.com/vi/iI_P1UVXfjo/0.jpg)](https://www.youtube.com/watch?v=iI_P1UVXfjo)
