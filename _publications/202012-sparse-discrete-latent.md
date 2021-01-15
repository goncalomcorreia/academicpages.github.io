---
title: "Efficient Marginalization of Discrete and Structured Latent Variables via Sparsity"
collection: publications
permalink: /publication/202012-sparse-discrete-latent
authors: 'Gonçalo M. Correia, Vlad Niculae, Wilker Aziz and André F.T. Martins'
conference: 'In Proceedings of NeurIPS'
conference_year: '2020'
arxiv_link: 'https://arxiv.org/abs/2007.01919'
code_link: 'https://github.com/deep-spin/sparse-marginalization-lvm'
abstract: 'Training neural network models with discrete (categorical or structured) latent variables can be computationally challenging, due to the need for marginalization over large or combinatorial sets. To circumvent this issue, one typically resorts to sampling-based approximations of the true marginal, requiring noisy gradient estimators (e.g., score function estimator) or continuous relaxations with lower-variance reparameterized gradients (e.g., Gumbel-Softmax). In this paper, we propose a new training strategy which replaces these estimators by an exact yet efficient marginalization. To achieve this, we parameterize discrete distributions over latent assignments using differentiable sparse mappings: sparsemax and its structured counterparts. In effect, the support of these distributions is greatly reduced, which enables efficient marginalization. We report successful results in three tasks covering a range of latent variable modeling applications: a semisupervised deep generative model, a latent communication game, and a generative model with a bit-vector latent representation. In all cases, we obtain good performance while still achieving the practicality of sampling-based approximations.'
bibtex: "
@inproceedings{correia2020EfficientMarginalizationDiscrete,
  title = {Efficient {{Marginalization}} of {{Discrete}} and {{Structured Latent Variables}} via {{Sparsity}}},
  booktitle = {Proceedings of {{NeurIPS}}},
  author = {Correia, Gon{\c c}alo M. and Niculae, Vlad and Aziz, Wilker and Martins, Andr{\'e} F. T.},
  year = {2020},
  url = {http://arxiv.org/abs/2007.01919}
}"
comment: "Spotlight paper. <a href='https://slideslive.com/embed/presentation/38937873' target='_blank'>Video</a>"
---