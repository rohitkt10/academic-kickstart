---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Probablistic Active Subspaces"
event: "ASME Verification & Validation Symposium 2016"
address: 
  city: "Las Vegas"
  region: NV
subtitle: "Building in dimensionality reduction into Gaussian process regression models"
abstract: "Gaussian process regression (GPR) is an immensely popular choice for computational scientists as a surrogate model for various uncertainty quantification tasks. However, it's appliacability is limited by it's poor scalability to high input dimensions. In this I demonstrate a methodology for scaling GPR to high-dimensional stochastic parameter spaces by recovering the *active subspace* of the quantity of interest. To do this, this active subspace projection matrix is posed as the hyperparameter of the Gaussian process covariance kernel and it's entries are learned by maximizing the likelihood of the data."
authors: ["Rohit Tripathy", "Ilias Bilionis"]
tags: [gaussian processes, uncertainty quantification, surrogate models, machine learning]
categories: []
date: 2016-05-18T16:00:00Z
lastmod: 2016-05-18T16:00:00Z
featured: false
all_day: true
draft: false

url_slides: https://speakerdeck.com/rohitkt10/asme-v-and-v-2016-talk-on-probabilistic-active-subspaces

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Active Subspace GPR"
  focal_point: "Center"

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: ["High-dimensional Uncertainty Quantification"]


---
