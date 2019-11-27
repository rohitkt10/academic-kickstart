---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Solving multiscale stochastic partial differential equations using deep neural networks"
event: "SIAM Conference on Computational Science and Engineering"
location: "Atlanta, GA"
#address: 
#  city: "Atlanta"
#  region: GA
subtitle: "Using deep neural networks to learn multiscale basis functions for the solution of stochastic PDEs"
abstract: "The applicability of traditional methods for stochastic partial differential equations (SPDEs) including Monte Carlo (MC) methods (and its variants), operator based methods, moment methods and generalized polynomial chaos (gPC) is typically restricted by the fact that they are either incapable of dealing with the curse of dimensionality or require a vast number of evaluations of the (generally expensive) forward model to obtain convergent statistics. The challenge is compounded when one is dealing with multiscale systems which require resolving small-scale effects on the large scale to get accurate predictions. We demonstrate a modification of the multiscale finite element method (MFEM) where the multiscale basis functions are predicted using a deep neural network (DNN). The DNN is trained with data obtained by solving the corresponding homogeneous PDE on coarse block elements of the finite element (FE) grid with a broad range of length scales of the random field. The full solution is obtained by coupling the locally adaptive multiscale basis functions with the global FE formulation. Our approach is validated with examples on steady flow through random porous media."
authors: ["Rohit Tripathy", "Ilias Bilionis"]
tags: [deep learning, uncertainty quantification, surrogate models, machine learning, multiscale, finite element method]
categories: []
date: 2017-03-01T16:00:00Z
lastmod: 2017-03-01T16:00:00Z
featured: false
all_day: true
draft: false

url_slides: https://speakerdeck.com/rohitkt10/learning-msfem-basis-functions-using-dnns

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Multiscale Finite Elements"
  focal_point: "Left"

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: ["High-dimensional Uncertainty Quantification"]


---
