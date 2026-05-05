---
title: "H36M-Seg: Human Part Segmentation of Human3.6M"
collection: publications
category: manuscripts
permalink: /publication/h36m-seg
excerpt: 'An anatomically consistent human part segmentation dataset and benchmarking study under occlusion and class imbalance.'
date: 2026-04-17
venue: 'Preprint (in preparation); planned submission to CVPR 2026 Workshop'
citation: 'M. Sinha, S. Manzur, J. Kawaguchi, E. Wang, W. Hayes. (2026). "'
---
image: /images/H36M_Seg_poster.png
image_caption: "Overview of the H36M-Seg pipeline."

![UnrealPose Pipeline](/images/H36M_Seg_poster.png)

**Status:** Preprint in preparation. Planned submission to CVPR 2026 Workshop.

**Abstract (draft):**
Human part segmentation aims to decompose the human body into semantically meaningful regions at the pixel level. Existing datasets often rely on appearance-based labeling, leading to inconsistencies under occlusion and clothing. We address this gap in two ways. First, we introduce an automated pipeline that generates pixel-level annotations. For each input image, our method assumes a known camera viewpoint and ground-truth 3D keypoints; we use these to generate a 3D solid-body “abstract image” representation of individually-colored limbs, with occlusion, as viewed from the given camera viewpoint. Finally, applying the binary mask (that outlines the human in the image) to the abstract image gives us a final, pixel-by-pixel segmentation of the imaged human into color-coded limbs. Second, we apply this pipeline to every image in Human3.6M, giving a dataset which we call **H36M-Seg**. It provides pixel-level segmentation divided into nine anatomically defined body parts: bilateral thighs, calves, upper arms, forearms, and torso. We benchmark modern segmentation architectures and analyze performance under severe foreground–foreground imbalance and occlusion. Our results highlight challenges in anatomically consistent segmentation and motivate data-centric approaches for fine-grained human understanding.

**Resources:** Links to paper/code will be added upon arXiv release.
