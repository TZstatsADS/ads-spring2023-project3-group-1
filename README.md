# Project: Weakly supervised learning-- label noise and correction


### [Full Project Description](doc/project3_desc.md)

Term: Spring 2023

+ Team ## Group 1
+ Team members
	+ Wen Chen
	+ Chenyi Jiang
	+ Ashwathi Nair
	+ Hongju Ouyang
	+ Han Wang
	+ Zixun Zhang

+ Project summary: In this project, we created a novel solution for image classification with noisy image labels. The team worked on building 2 models. In Model 1, we trained a CNN classification model with nosiy data. In Model II, we first built a label-cleaning model based on CNN that extracts visual features from images and used them to predict labels, which are then passed through Model-I for image classification. In the evaluation section, we test all 3 models (baseline, model I and model II) and model 2 shows a great improvement in performance.
	

**Contribution statement**: ([default](doc/a_note_on_contributions.md)) All team members contributed equally in all stages of this project. All team members approve our work presented in this GitHub repository including this contributions statement. 

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
