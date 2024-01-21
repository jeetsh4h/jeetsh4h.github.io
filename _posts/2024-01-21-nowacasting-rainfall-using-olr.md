---
layout: post
title: Nowcasting Rainfall using OLR
gh-repo: jeetsh4h/Nowcasting-OLR-Optical-Flow
gh-badge: [star, fork, follow]
tags: [nowcasting, deep-learning, research, project]
comments: true
author: Jeet Shah
---

The project was discussed and ideated in the latter half of the 2022-2023 academic year. The research work started under Prof. V. K. Jayaraman's class - "Statistics and Optimisation in Computing". I was mentored by Prof. Kaushik Gopalan.  
The main aim of the project was to build a Convolutional LSTM model to nowcast cloud cover over the Indian subcontinent using Outgoing Longwave Radiation data obtained INSAT-3D satellite and distributed by MOSDAC.

Due to time constraints, and my inexperience then; the project pivoted to nocasting the cloud cover changes using optical flow techniques. The project was submitted as a part of the course and you can find the write-up of the same in the GitHub respostiory that is linked above.

The project continued on, even after the course ended under the tutelage of Prof. Kaushik Gopalan. He was kind enough to introduce me to scientists working at Space Applications Centre, ISRO. I received a chance to work under Dr. Bipasha Shukla on-site at SAC, Ahmedabad. We continued working on developing the Convolutional LSTM model for nowcasting cloud cover. As soon as my on-site internship ended, I had a chance to present my work up until now at the 2023 National Conference on
Computer Vision, Pattern Recognition, Image Processing and Graphics (NCVPRIPG) held at IIT Jaipur.

The work is still being continued on as my Honor's Thesis at FLAME University with Prof. Kaushik Gopalan and Dr. Bipasha Shukla as my mentors. The model has undergone many revisions, while also introducing the HEM (Hydro-Estimator Model) product derived from images from the INSAT-3D satellite to give a probablistic value for rain within a 10km x 10km area across the Indian subcontinent with a lead-time of 2 hours.

All work that will be done will be updated on the GitHub repository linked above; or a new link will be added to the current post.