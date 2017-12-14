Code
====

This folder contains the notebooks with the course material separated into different parts covering a subset of the material. Each part is intended to be done in sequence, and has exercises that can be optionally done in order to improve understanding.

The code is mostly written using ODL and TensorFlow, but some parts also has PyTorch code available.

Part 0 : Installation
---------------------
[part0_install](part0_install.ipynb) gives installation instructions needed to run the following notebooks.

Part 1 : Basic ODL
------------------
This part aims to introduce basic ODL concepts such as spaces, vectors and operators and uses these concepts to solve a basic inverse problem (denoising) with a TV prior.

* [part1_tv_denoising](part1_tv_denoising.ipynb)
* [part1_using_a_different_solver](part1_using_a_different_solver.ipynb)
* [part1_exercises](part1_exercises.ipynb)

Part 2 : Basic Machine Learning
-------------------------------
Introduces machine learning on its own, and in particular focuses on classifying handwritten digits from the MNIST dataset

* [part2_classification](part2_classification.ipynb) ([PyTorch](part2_classification_pytorch.ipynb))
* [part2_exercises](part2_exercises.ipynb)

Part 3 : Machine Learning and Inverse Problems
----------------------------------------------
Gives an overview of machine-learning based methods to solve inverse problems. See also the [slides](../presentations/machine_learning_intro_JA.pdf).

* [part3_learned_reconstruction](part3_learned_reconstruction.ipynb) ([PyTorch](part3_learned_reconstruction_pytorch.ipynb))
* [part3_exercises](part3_exercises.ipynb)

Part 4 : ODL for large scale problems
-------------------------------------
This final part combines some of the above concepts and should allow users to use ODL in order to solve large scale problems in imaging, it does this by providing some examples.

* [part4_real_data](part4_real_data.ipynb)
* [part4_spectral_ct](part4_spectral_ct.ipynb)
