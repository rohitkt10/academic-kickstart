---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Deep neural networks for multifidelity uncertainty quantification"
event: "SIAM Annual Meeting"
location: "Garden Grove, CA"
#address: 
#  city: "Pittsburgh"
#  region: PA
subtitle: "Leveraging information for multiple sources to construct accurate surrogate models"
abstract: "A common scenario in computational science is the availability of a suite of simulators solving the same physical problem, such that the simulators are at varying levels of cost/fidelity. High fidelity simulators are more accurate but are computationally expensive, whereas low fidelity models can be evaluated cheaply while suffering from reduced accuracy. Additionally, many engineering applications are characterized by model parameters / boundary conditions / initial conditions etc. which are not known exactly. The surrogate-based approach to uncertainty quantification requires one to evaluate the forward model enough times such that one can construct a cheap (but accurate) approximation to the numerical solver. If the outputs from the simulators of varying fidelities are correlated, one can leverage information from low-fidelity simulators to augment information from a small number of evaluations of the high-fidelity simulator to construct an accurate surrogate model. In this work, we demonstrate a deep neural network (DNN) approach for constructing accurate surrogate models for uncertainty quantification by fusing information from multifidelity sources. DNNs are naturally suited for multifidelity information fusion because of the hierarchical representation of information. Our approach is validated on synthetic examples and demonstrated on real application examples from advanced manufacturing."
authors: ["Rohit Tripathy", "Ilias Bilionis"]
tags: [deep learning, uncertainty quantification, surrogate models, machine learning, multifidelity]
categories: []
date: 2018-04-16T16:00:00Z
lastmod: 2018-04-16T16:00:00Z
featured: false
all_day: true
draft: false

url_slides: https://speakerdeck.com/rohitkt10/learning-deep-neural-network-dnn-surrogate-models-for-uq

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
