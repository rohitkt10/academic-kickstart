---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Learning nonlinear correlations between multifidelity models using deep neural networks"
event: "SIAM Annual Meeting"
location: "Pittsburgh, PA"
#address: 
#  city: "Pittsburgh"
#  region: PA
subtitle: "Leveraging information for multiple sources to construct accurate surrogate models"
abstract: "A typical scenario in computational science is the availability of a suite of simulators the solve the same physical problem at varying degrees of accuracy (or *fidelity*). Higher fidelity solvers adhere to the underlying physics more faithfully, requiring fewer simplications/approximations of the solution methodology and typically incur higher computational cost. A persistant challenge in computational science has thus been on developing methods for efficiently assimilating information from varying sources in order to construct accurate surrogate models for physical systems. O'Hagan's classical linear autoregressive model for multifidelity data fusion is the seminal work on this topic - improved upon, most notably by Le Gratiet in 2013. Perdikaris et al. (2018) proposed a nonlinear extension to the classical linear autoregressive scheme using Gaussian processes. We propose a simple deep neural network approach to learn nonlinear correlations across models of various fidelity - enabling us to scale to higher dimensional stochastic inputs."
authors: ["Rohit Tripathy", "Ilias Bilionis"]
tags: [deep learning, uncertainty quantification, surrogate models, machine learning, multifidelity]
categories: []
date: 2017-03-01T16:00:00Z
lastmod: 2017-03-01T16:00:00Z
featured: false
all_day: true
draft: false

url_slides: https://speakerdeck.com/rohitkt10/dnn-for-hd-uq

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
#image:
#  caption: "Active Subspace GPR"
#  focal_point: "Center"

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: ["High-dimensional Uncertainty Quantification"]


---
