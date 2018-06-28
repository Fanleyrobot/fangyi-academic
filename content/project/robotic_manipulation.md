+++
# Date this page was created.
date = 2016-12-31T00:00:00

# Project title.
title = "Robotic Manipulation for Warehouse and Household Applications"

# Project summary to display on homepage.
summary = ""
#summary = "Sensor-based robot tasks such as visual reaching are traditionally implemented by hand-crafted controllers. Typically a perception system will identify the target in some local or global coordinate system and the robot motion planner and joint control system will ensure that the required collision-free motion is executed. Understanding complex visual scenes has traditionally been a hard problem but in recent years deep learning techniques have led to significant improvements in robustness and performance. Recently deep learning approaches have also been used in robotic applications to learn visuo-motor policies where motors are directly controlled by observations from raw-pixel images. However, a consistent issue faced by most approaches is the reliance on large amounts of data for training. In practice, labelling of real robotic data is very expensive, or even impractical. In contrast, simulated data is much cheaper. Therefore, this thesis focuses on investigating how simulation can be used to reduce the cost of data collection for visuo-motor policy learning. Firstly, we evaluate the feasibility of learning vision-based planar reaching using a Deep Q Network (DQN), showing that DQN is able to learn reaching in simulation, however the learned policies do not transfer directly to real robots with real cameras observing real scenes. Therefore, modular deep Q networks are proposed to transfer policies from simulation to the real world in a low-cost manner with a small number of labelled real images. To further weaken the reliance on real data, an adversarial discriminative loss based semi-supervised approach is proposed to transfer visuo-motor policies with fewer labelled real data. A comparable performance can be achieved with 50% fewer labelled real images in a benchmark task of 7 DoF robotic reaching in clutter."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "projects/apc2016.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["reinforcement-learning", "deep-learning"]`
tags = ["robots for housework", "robotic manipulation", "robotic picking and placing", "robotic vision", "deep learning", "motion planning"]

# Optional external URL for project (replaces project detail page).
external_link = ""
# external_link = "https://research.qut.edu.au/ras/research/amazon-picking-challenge-2016/"

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++

- ### **Amazon Picking Challenge (2016)**
As part of the [Team ACRV](https://research.qut.edu.au/ras/research/amazon-picking-challenge-2016/) for the [Amazon Picking Challenge 2016](http://pwurman.org/amazonpickingchallenge/results.shtml), I worked on hand-eye calibration with [Dr. Leo Wu](https://sites.google.com/site/wuliaothu/home).
{{< youtube kiPumsk9TBk >}}

- ### **Household Applications**
This is a project I worked on during my visit to the [Perception and Robotics Group](http://prg.cs.umd.edu/) at the [University of Maryland](https://umd.edu/), College Park, Sep-Dec 2016. A mobile manipulation robot was developed for housework in a kitchen scenario, where I mainly took in charge of the sub-task of table cleaning. Thanks to [Prof. Yiannis Aloimonos](http://legacydirs.umiacs.umd.edu/~yiannis/), [Dr. Cornelia Fermüller](http://legacydirs.umiacs.umd.edu/~fer/), [Dr. Yi Li](https://users.cecs.anu.edu.au/~yili/), [Dr. Yezhou Yang](https://yezhouyang.engineering.asu.edu/) and my colleagues: [Dr. Fang Wang](http://users.cecs.anu.edu.au/~fwang/), Dr. Ren Mao, [Dr. Aleksandrs Ecins](https://scholar.google.com/citations?user=eDDJ48UAAAAJ&hl=en), [Dr. Wentao Ruan](https://scholar.google.com/citations?user=PJQ8XgwAAAAJ&hl=en), [Mr. Konstantinos Zampogiannis](https://www.cs.umd.edu/~kzampog/), Mr. Yi Zhang, [Mr. Kanishka Ganguly](http://legacydirs.umiacs.umd.edu/~kganguly/), [Chethan M Parameshwara](https://analogicalnexus.github.io/).
#### **Table Cleaning**
{{< youtube QyQWNof-8v4 >}}
#### **Refrigerator Operating**
{{< youtube 1rK_O8T_ck4 >}}
#### **Microwave Operating**
{{< youtube WUcqNiUzKvI >}}
