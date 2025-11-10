# ML-for-Material-Discovery-High-Entropy-Perovskite-Oxides
Machine-Learning Guided discovery of High Entropy Perovskite oxides via oxygen vacancy Engineering. In this project, we deployed an integrated framework that combines density functional theory (DFT) calculations, machine learning (ML) and experimental validations do predict oxygen vacancy formation energies in HEPO electrocatalysts.

# Introduction
This Repository accompanies the paper published as; 

https://onlinelibrary.wiley.com/doi/10.1002/smll.202501946

It contains the source code and data pipeline for building and training the OxiGraphX model — a novel graph neural network framework based on the CEAL-WF layer for accurate prediction of oxygen vacancy formation energies (OVFEs) in high-entropy perovskite oxides.

OxiGraphX, is introduced as a novel graph neural network (GNN) model designed to capture the complex relationships among structure, composition, and atomic chemical environments for accurate prediction of oxygen vacancy formation energies (OVFEs) in HEPOs. By integrating machine learning (ML), density functional theory (DFT), and experimental validation, this model demonstrates an efficient framework for rapidly and accurately screening HEPO electrocatalysts for oxygen evolution reaction (OER).
It contains the source code and data pipeline for building and training the OxiGraphX model — a novel graph neural network framework based on the CEAL-WF layer for accurate prediction of oxygen vacancy formation energies (OVFEs) in high-entropy perovskite oxides.

Scheme 1 depicts the material development framework encompassing DFT calculations, ML predictions, and experimental validations. To the best of our knowledge, this framework presents a pioneering effort that translates ML outcomes into laboratory experiments. This innovative framework empowers researchers to leverage ML models to predict diverse properties essential for experimental studies.

   ![image](https://github.com/user-attachments/assets/54855468-726c-40c2-984d-3b4abbfc5c36)

Integrated framework featuring ML, DFT, and experiments for OVFE prediction in HEPOs


Scheme 2 illustrates the structure of the Chemical Environment Adaptive Learning with Learnable Weighting Functions (CEAL-WF) layer and provides an overview of the OxiGraphX model for OVFE prediction in HEPOs.

![image](https://github.com/user-attachments/assets/63acf221-1fa9-4c38-bd3c-49357ef1b4c2)

Scheme 2: a) The architecture of the CEAL-WF convolutional layer. b) Overview of OxiGraphX model for OVFE prediction in HEPOs.





