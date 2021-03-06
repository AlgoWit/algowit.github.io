---
title: G-SMOTE
category: notes
description: "Geometric SMOTE: A geometrically enhanced drop-in replacement for SMOTE."
icon: gsmote.png
publication: https://www.sciencedirect.com/science/article/pii/S0020025519305353?via%3Dihub
---

<img src="/assets/images/publications/gsmote.png" class="img-fluid" alt="Geometric SMOTE">

### Abstract

Classification of imbalanced datasets is a challenging task for standard algorithms. Although many methods exist to address this problem in different ways, generating artificial data for the minority class is a more general approach compared to algorithmic modifications. SMOTE algorithm, as well as any other oversampling method based on the SMOTE mechanism, generates synthetic samples along line segments that join minority class instances. In this paper we propose Geometric SMOTE (G-SMOTE) as a enhancement of the SMOTE data generation mechanism. G-SMOTE generates synthetic samples in a geometric region of the input space, around each selected minority instance. While in the basic configuration this region is a hyper-sphere, G-SMOTE allows its deformation to a hyper-spheroid. The performance of G-SMOTE is compared against SMOTE as well as baseline methods. We present empirical results that show a significant improvement in the quality of the generated data when G-SMOTE is used as an oversampling algorithm. An implementation of G-SMOTE is made available in the Python programming language.

