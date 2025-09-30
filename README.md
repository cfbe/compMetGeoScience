# Computer methods in engineering #

### About this repository ###

This repository contains materials for the course [TPG4155 - Computer Methods in Engineering](https://www.ntnu.edu/studies/courses/TPG4155). All material is stored as jupyter notebook files. Please install jupyter notebook from the [jupyter website](https://jupyter.org/) if you want to run the Python codes on your own.

## Content ##

<!-- Modelling and simulation, computer methods, in general -->
<!-- Add data preprocessing, noise, sensors, with a lot of examples -->
<!-- Challenges with origin of data -->
<!-- Also introduce an overview of methods, such as machine learning, digital twin, regression -->

[Introduction](lectures/pythonIntro.ipynb)


### Differential equations ###

* [Ordinary differential equations](lectures/ordinaryDifferentialEquations.ipynb) - [Exercise](exercises/exerciseODE.pdf) ([Solution](exercises/solutionODE.pdf))
* [Partial differential equations](lectures/partialDifferentialEquations.ipynb) - [Exercise](exercises/exerciseFiniteDifferences.pdf) ([Solution](exercises/solutionFiniteDifferences.pdf))
  * [Elliptic equations](lectures/ellipticEquations.ipynb) (Laplace equation) - [Exercise](exercises/exerciseElliptic.pdf) ([Solution](exercises/solutionElliptic.pdf))
  * [Parabolic equations](lectures/parabolicEquations.ipynb) (heat equation/diffusivity equation) - [Exercise](exercises/exerciseParabolic.pdf) ([Solution](exercises/solutionParabolic.pdf))
  * [Hyperbolic equations](lectures/hyperbolicEquations.ipynb) (wave equation) - [Exercise](exercises/exerciseHyperbolic.pdf) ([Solution](exercises/solutionHyperbolic.pdf))


### Optimization ###

* [Introduction](lectures/optimization.ipynb)
* [Bracket search](lectures/bracketSearch.ipynb) - [Exercise](exercises/exerciseBracket.pdf) ([Solution](exercises/solutionBracket.pdf))
* [Gradient methods](lectures/gradientMethods.ipynb) (local)
  * [Gradient descent](lectures/gradientDescent.ipynb)- [Exercise](exercises/exerciseGradientDescent.pdf) ([Solution](exercises/solutionGradientDescent.pdf))
  * [Conjugate gradient method](lectures/conjugateGradientMethod.ipynb) - [Exercise](exercises/exerciseCG.pdf) ([Solution](exercises/solutionCG.pdf))
  * [LU decomposition](lectures/ludecomposition.ipynb) - [Exercise](exercises/exerciseLU.pdf) ([Solution](exercises/solutionLU.pdf))
* [Derivative-free optimization](lectures/derivativeFreeOptimization.ipynb) (global)
  * [Pattern search](lectures/patternSearch.ipynb) - [Exercise](exercises/exercisePatternSearch.pdf) ([Solution](exercises/solutionPatternSearch.pdf))
  * [Nelder-Mead](lectures/nelderMead.ipynb) - [Exercise](exercises/exerciseNelderMead.pdf) ([Solution](exercises/solutionNelderMead.pdf))
  * [Simulated Annealing](lectures/simulatedAnnealing.ipynb)
  * [Evolutionary algorithms](lectures/evolutionaryAlgorithms.ipynb)
    * [Genetic algorithm](lectures/geneticAlgorithm.ipynb)
    * [Particle swarm optimization](lectures/particleSwarmOptimization.ipynb)
* [Automatic differentiation](lectures/automaticDifferentiation.ipynb)

<!-- A full section on automation and cybernetics: feedback control, PID, real-time data cleaning and filtering, and real-time optimization 2.5 weeks -->

### Machine learning ###
* [Neural networks](lectures/neuralNetworks.ipynb)
* [Clustering and Classification algorithms](lectures/clusteringAlgorithms.ipynb)
    * [K-means algorithm](lectures/kmeansAlgorithm.ipynb)
    * [Support vector machine](lectures/supportvectorMachine.ipynb)
    * [Decision Trees](lectures/decisionTree.ipynb)
* [Dimensionality reduction](lectures/dimensionalityReduction.ipynb)

<!-- heading: generative metoder -->
<!-- Underdel 1: transformers, innkludert chatbot (Elisa eksempel?) -->
<!-- Underdel 2: diffusjonsmodeller for å generere nye eksempler -->


<!--
### Exercises
* [Exercise 1](exercises/exercise1.pdf)
   * [Solution 1](exercises/solution1.pdf)
* [Exercise 2](exercises/exercise2.pdf)
   * [Solution 2](exercises/solution2.pdf)
* [Exercise 3](exercises/exercise3.pdf)
   * [Solution 3](exercises/solution3.pdf)
* [Exercise 4](exercises/exercise4.pdf)
   * [Solution 4](exercises/solution4.pdf)
   * [wave1d](exercises/wave1d.ipynb)
* [Exercise 5](exercises/exercise5.pdf)
   * [Solution 5](exercises/solution5.pdf)
* [Exercise 6](exercises/exercise6.pdf)
   * [Solution 6](exercises/solution6.pdf)
* [Exercise 7](exercises/exercise7.pdf)
   * [Solution 7](exercises/solution7.pdf)
* [Exercise 8](exercises/exercise8.pdf)
   * [Solution 8](exercises/solution8.pdf)
   * [Solution-code](exercises/solution-code.ipynb)
* [Exercise 9](exercises/exercise9.pdf)
   * [Solution 9](exercises/solution9.pdf)
-->