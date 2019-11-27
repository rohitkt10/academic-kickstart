---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Gradient-free active subspace recovery using deep neural networks"
subtitle: "Applications to high-dimensional uncertainty quantification"
event: "ASME IDETC-CIE"
location: "Anaheim, CA"
#address: 
#  city: "Pittsburgh"
#  region: PA
subtitle: "Leveraging information for multiple sources to construct accurate surrogate models"
abstract: "A problem of considerable importance within the field of uncertainty quantification (UQ) is the development of efficient methods for the construction of accurate surrogate models. Such efforts are particularly important to applications constrained by high-dimensional uncertain parameter spaces. The diffi- culty of accurate surrogate modeling in such systems, is fur- ther compounded by data scarcity brought about by the large cost of forward model evaluations. Traditional response sur- face techniques, such as Gaussian process regression (or Krig- ing) and polynomial chaos are difficult to scale to high dimen- sions. To make surrogate modeling tractable in expensive high- dimensional systems, one must resort to dimensionality reduc- tion of the stochastic parameter space. A recent dimension- ality reduction technique that has shown great promise is the method of ‘active subspaces’. The classical formulation of ac- tive subspaces, unfortunately, requires gradient information from the forward model - often impossible to obtain. In this work, we present a simple, scalable method for recovering active sub- spaces in high-dimensional stochastic systems, without gradient- information that relies on a reparameterization of the orthogonal active subspace projection matrix, and couple this formulation with deep neural networks. We demonstrate our approach on synthetic and real world datasets and show favorable predictive comparison to classical active subspaces."
authors: ["Rohit Tripathy", "Ilias Bilionis"]
tags: [deep learning, uncertainty quantification, surrogate models, machine learning, active subspace]
categories: []
date: 2019-08-21T16:00:00Z
lastmod: 2019-08-21T16:00:00Z
featured: false
all_day: true
draft: false

url_slides: https://speakerdeck.com/rohitkt10/gradient-free-active-subspace-recovery-using-deep-neural-networks-application-to-high-dimensional-uncertainty-quantification

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
