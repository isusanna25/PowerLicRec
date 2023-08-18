# Open Source License Recommendation for Power Industry Software

## Overview

This repository contains the implementation of a novel framework for recommending open source licenses for software projects within the power industry. The framework consists of two stages: data processing and license recommendation. The goal is to help software developers in the power industry overcome obstacles in understanding and selecting appropriate licenses for their open source projects.

## Background

In the context of developing a decentralized renewable energy system within the smart grid industry, it is crucial to establish secure and appropriate licensing procedures for open source software. However, developers often face challenges in comprehending and selecting licenses due to factors such as legal complexities, license compatibility, and the evolving landscape of the open source movement in the power industry.

## Objective

The main objective of this project is to comprehensively examine the licenses of open source projects within the power industry. The ultimate aim is to provide insights and recommendations that contribute to the successful completion and popularity of software projects in this domain.

## Methodology

To achieve our objective, we followed a structured methodology:

1. **Data Collection:** We analyzed a vast dataset of 274,442 open source repositories related to 40 electricity-related keywords from GitHub.

2. **Clustering:** We applied the K-means clustering algorithm to group repositories with similar characteristics into 6 major clusters.

3. **License Prediction:** Using the clustering results, we employed the random forest method to predict suitable licenses for new repositories. The model's accuracy was evaluated and achieved an impressive 96% accuracy.

## Results

Our analysis yielded the following key findings:

- Different clusters of open source repositories in the power industry exhibit distinct licensing preferences based on their specific objectives.
- The MIT license emerged as the most popular choice due to its permissive nature.
- Clusters valuing copyleft principles preferred the GPL-3.0 license, while those emphasizing closed-source derivatives protection favored Apache-2.0 and BSD-3-Clause licenses.
- The content of open source projects serves as a meaningful indicator for license recommendation.

## Conclusion

This repository presents a comprehensive approach to understanding and recommending open source licenses for software projects within the power industry. The insights and recommendations provided here contribute to the advancement of license selection practices in this domain and offer valuable guidance to software developers working on decentralized renewable energy systems and smart grid technologies.

---

*Disclaimer: The information and recommendations provided in this repository are based on the analysis conducted up to September 2021. The landscape of open source licensing and the power industry may have evolved since then.*
