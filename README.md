This repo contains my solutions to the tasks for both QML and CMS/E2E. Although I proposed for the QMLHEP "Quantum Graph Neural Networks for High Energy Physics at the LHC" project, I chose to tackle some classical tasks too, which are the CMS files. This is a description:

* QMLHEP_task_i.ipynb - my notebook for task I, where some basic operations on variational circuits are performed using Pennylane.
* QMLHEP_task_ii.ipynb - classical Graph Neural Networks (GNN) for quark vs gluon tagging.
* QMLHEP_task_iii.ipynb - my sincere comments on quantum computing and quantum machine learning.
* QMLHEP_task_V.ipynb - contains a skectch and implementation of a Quantum Lie-Equivariant GNN (my proposal).
* QMLHEP_task_VI.ipynb - "FidelityNet" is proposed and implemented for quantum representation learning.
* QMLHEP_task_VIII.ipynb - a classical vision transformer is trained on MNIST using Torch Lightning, and then some ideas are discussed for a variational form.

* CMS_task_i.ipynb - photons vs electrons trained on ResNet-15, which was implemented from scratch.
* CMS_task_iii_e.ipynb - a convolutional autoencoder is trained on MNIST, and later two approaches are tried for learning an infinitesimal operator of rotations. The first is the same as in the oracle preserving latent flow, and the other one from the LieGAN. An extra step extract the metric tensor from the learned algebras.
* CMS_task_iii_g.ipynb - classical Graph Neural Networks (GNN) for quark vs gluon tagging (the same as in QMLHEP task II).
