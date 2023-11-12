# Extending Sparse Dictionary Learning Methods for Adversarial Robustness

This repository contains the PDF of my joint MSc thesis at ELTE with Balázs Mészáros supervised by Dr. habil. András Lőrincz and Dr. Dávid Szeghy. It also contains a corresponding presentation. The code for this project is still private, once it's published it will be linked here.

## Abstract

Despite their state-of-the-art performance on many tasks, deep neural networks have been shown to be vulnerable to adversarial attacks. Sparse coding methods using Basis Pursuit (BP) are appealing as they have provable robustness guarantees against such attacks. These guarantees were extended in previous work to more generalized forms of regularization, including the group case and its generalizations, multi-layer extension and the Deep-Pursuit method. However, applying and scaling such methods in practice is not straightforward due to training difficulties. In this work, we lay out and further expand on our experiments reported in [[1]](#1). and try to bridge the gap between theory and practice by utilizing training tricks such as batch normalization, different regularization methods, pre- and layer-wise training. Specifically, we conduct experiments on sparse, group sparse and pooled group sparse models to verify their robustness. We also study their multi-layer extensions using the Deep Pursuit architecture. To overcome BP’s slowness, we consider feedforward estimations to provide inference time speed ups using linear transformers, shallow and deep dense networks. We report robustness evaluations against IFGSM attacks on a synthetic dataset and MNIST.

## Related Paper

<a id="1" href="https://www.scitepress.org/Papers/2022/111389/111389.pdf">[1]</a> 
Dávid Szeghy., Mahmoud Aslan., Áron Fóthi., Balázs Mészáros., Zoltán Milacski., and András Lőrincz. (2022). 
**Structural Extensions of Basis Pursuit: Guarantees on Adversarial Robustness**
In: Proceedings of the 3rd International Conference on Deep Learning Theory and Applications - DeLTA, INSTICC. SciTePress, 2022, pp. 77–85. isbn: 978-989-758-584-5. doi: 10.5220/0011138900003277.
