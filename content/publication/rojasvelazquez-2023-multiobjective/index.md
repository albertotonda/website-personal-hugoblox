---
title: 'Multi-objective Evolutionary Discretization of Gene Expression Profiles: Application
  to COVID-19 Severity Prediction'
authors:
- David Rojas-Velazquez
- Alberto Tonda
- Itzel Rodriguez-Guerra
- Aletta D. Kraneveld
- Alejandro Lopez-Rincon
date: '2023-01-01'
publishDate: '2024-12-17T18:33:40.823061Z'
publication_types:
- paper-conference
publication: '*Applications of Evolutionary Computation*'
abstract: 'Machine learning models can use information from gene expressions in patients
  to efficiently predict the severity of symptoms for several diseases. Medical experts,
  however, still need to understand the reasoning behind the predictions before trusting
  them. In their day-to-day practice, physicians prefer using gene expression profiles,
  consisting of a discretized subset of all data from gene expressions: in these profiles,
  genes are typically reported as either over-expressed or under-expressed, using
  discretization thresholds computed on data from a healthy control group. A discretized
  profile allows medical experts to quickly categorize patients at a glance. Building
  on previous works related to the automatic discretization of patient profiles, we
  present a novel approach that frames the problem as a multi-objective optimization
  task: on the one hand, after discretization, the medical expert would prefer to
  have as few different profiles as possible, to be able to classify patients in an
  intuitive way; on the other hand, the loss of information has to be minimized. Loss
  of information can be estimated using the performance of a classifier trained on
  the discretized gene expression levels. We apply one common state-of-the-art evolutionary
  multi-objective algorithm, NSGA-II, to the discretization of a dataset of COVID-19
  patients that developed either mild or severe symptoms. The results show not only
  that the solutions found by the approach dominate traditional discretization based
  on statistical analysis and are more generally valid than those obtained through
  single-objective optimization, but that the candidate Pareto-optimal solutions preserve
  the sense-making that practitioners find necessary to trust the results.'
---