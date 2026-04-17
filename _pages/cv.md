---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in Computer Science, University of California, Irvine (UCI), 2026 (expected)
* B.S. in Computer Science, University of California, Irvine (UCI), 2025

Research Experience
======
* 2025–Present: Graduate Research Assistant  

  * University of California, Irvine (Institute for Future Health)  
    * Conducting AI safety and alignment research (Tinwhistle), focusing on false rejection and mental health-sensitive prompt evaluation  

  * University of California, Irvine (Donald Bren School of Information and Computer Sciences, Hayes Lab)  
    * Working on anatomically consistent human part segmentation and synthetic-to-real human pose estimation (UnrealPose)  
    * Focus on dataset construction, benchmarking, and evaluation under occlusion and class imbalance  

* 2024–2025: Undergraduate Research Assistant  
  * University of California, Irvine (Molloi Lab)  
  * Worked on medical imaging and data analysis projects related to cardiovascular systems  
  * Gained experience with image processing, quantitative analysis, and research workflows  

Projects
======
* H36M-Seg: Anatomically Consistent Human Part Segmentation  
  * Developed a large-scale dataset derived from Human3.6M with anatomically consistent pixel-level labels  
  * Built automated pipeline using 3D keypoints to generate 2D segmentation masks  

* UnrealPose  
  * Built a synthetic data generation pipeline in Unreal Engine 5 producing COCO-style annotations (keypoints, bounding boxes, occlusion labels, camera parameters)  
  * Designed cross-dataset evaluation pipelines to analyze synthetic-to-real generalization across vision benchmarks  

* Distributed Slow-Motion Video Pipeline  
  * Designed a distributed video frame interpolation pipeline using RIFE for scalable slow-motion generation  
  * Built an AWS-based system using EC2, Batch, Step Functions, and S3 with scene-based workload partitioning  

* Search Engine (Information Retrieval System)  
  * Built an information retrieval system using TF-IDF scoring, inverted indexes, phrase queries, and partial index merging  

Experience
======
* Outreach Coordinator, UCI HyperXite  
  * Organized events and coordinated outreach initiatives for student engagement  

* Member, IEEE Open Project Space (OPS)  
  * Participated in collaborative engineering and development projects  

* General Member, Women in Computer Science (WICS), UCI  

* NASA L’SPACE Program Participant  
  * Completed NASA’s L’SPACE Academy, gaining experience in space mission design and proposal development  

Technical Skills
======
* Languages: Python, C/C++, JavaScript, TypeScript, Java, SQL, Bash  
* ML/AI: PyTorch, TensorFlow, Transformers, HRNet, DEKR, MMPose, nnU-Net, BayeSeg  
* Systems: CUDA, SLURM, Docker, Linux, AWS (EC2, S3, Batch, Step Functions), Unreal Engine 5  
* Areas: Computer Vision, Machine Learning, Deep Learning, AI Safety  

Publications
======
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Service and Leadership
======
* Outreach Coordinator, UCI HyperXite  
* Member, IEEE OPS  
* Participant, NASA L’SPACE Program  
