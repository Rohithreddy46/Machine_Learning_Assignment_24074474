# Escaping the Linearity Trap: PCA versus Deep Autoencoders

This repository contains the educational materials for a postgraduate-level tutorial demonstrating the mathematical and spatial limitations of linear dimensionality reduction. Using a synthetic three-dimensional manifold dataset, this tutorial proves the mathematical equivalence of Principal Component Analysis and a linear neural network. It illustrates the concept of the linearity trap and false proximities in compressed latent spaces, and shows how deep neural networks utilizing non-linear activation functions can successfully learn topology and unroll complex manifolds into linearly separable two-dimensional representations.

To reduce cognitive load for learners, the complex visualization logic has been strictly separated from the core machine learning implementation. The primary interactive material contains the underlying theory, model architectures, and training loops, while modularized plotting functions are stored in a separate utilities module. Strict environment versioning is utilized to guarantee stability, and this documentation provides general setup and usage instructions.

To ensure full reproducibility, this project relies on standard machine learning libraries including PyTorch, scikit-learn, Matplotlib, and NumPy. Simply clone this repository to your local machine using a standard version control client and install the required dependencies using your preferred Python package manager.

To run the demonstration, launch an interactive Python computing environment within the cloned directory and open the primary tutorial. Read through the formatted explanations and execute the steps sequentially. The environment will automatically generate the synthetic dataset, train both the linear and deep models, and output the comparative loss convergence and latent space heatmaps.

This pedagogical tool was designed with strict adherence to digital accessibility standards to ensure an inclusive learning environment. All data plots utilize a perceptually uniform, colorblind-safe palette to ensure critical data contrasts remain distinct for all readers. High-contrast line styles are used for overlapping convergence graphs. The accompanying tutorial utilizes strict semantic hierarchy for seamless screen-reader navigation, and every figure is accompanied by descriptive alt-text that explicitly explains the educational takeaway.

This project is open-source and licensed for free modification and distribution for both educational and commercial purposes.
