# Computer methods in geoscience #

### About this repository ###

This repository contains materials for the course [TPG4155 - Applied Computer Methods in Petroleum Science](https://www.ntnu.edu/studies/courses/TPG4155). All material is stored as jupyter notebook files. Please install jupyter notebook from the [jupyter website](https://jupyter.org/) if you want to run the Python codes on your own.

## Content ##

### Differential equations ###

* [Ordinary differential equations](lectures/ordinaryDifferentialEquations.ipynb)
* [Partial differential equations](lectures/partialDifferentialEquations.ipynb)
  * [Elliptic equations](lectures/ellipticEquations.ipynb) (Laplace equation)
  * [Parabolic equations](lectures/parabolicEquations.ipynb) (heat equation/diffusivity equation)
  *  Hyperbolic equations
      * [Wave equation 1D](lectures/waveEquation1D.ipynb)
      * [Wave equation 2D](lectures/waveEquation2D.ipynb)

### Optimization ###

* [Introduction](lectures/optimization.ipynb)
* [Bracket search](lectures/bracketSearch.ipynb)
* Gradient based optimization (local)
  * [Gradient descent](lectures/gradientDescent.ipynb)
  * [Conjugate gradient method](lectures/conjugateGradientMethod.ipynb)
  * [LU decomposition](lectures/ludecomposition.ipynb)
  * [Derivative-free optimization](lectures/derivativeFreeOptimization.ipynb) (global)
  * [Pattern search](lectures/patternSearch.ipynb)
  * [Nelder-Mead](lectures/nelderMead.ipynb)
  * Simulated Anhealing
  * [Evolutionary algorithms](lectures/evoluationaryAlgorithms.ipynb)
    * [Genetic algorithm](lectures/geneticAlgorithm.ipynb)
    * [Particle swarm optimization](lectures/particleSwarmOptimization.ipynb)
* Automatic differentiation
  * Forward mode
  * Backward mode (adjoints)


### Neural networks ###

* Simple neural network
  * Application to MNIST data
