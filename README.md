# Computer methods in engineering #

### About this repository ###

This repository contains materials for the course [TPG4155 - Computer Methods in Engineering](https://www.ntnu.edu/studies/courses/TPG4155). All material is stored as jupyter notebook files. Please install jupyter notebook from the [jupyter website](https://jupyter.org/) if you want to run the Python codes on your own.

## Content ##

<!-- en liten intro om python og hva er en class og en instance o.l.  -->
[Introduction](lectures/pythonIntro.ipynb)
<!-- fortløpende legger vi inn øvinger på nett, med løsningsforslag -->

### Differential equations ###

<!-- skrive om ODE til classebasert, med arv (inheritense) av class når vi legger til en ny metode -->
* [Ordinary differential equations](lectures/ordinaryDifferentialEquations.ipynb) - [Exercise](exercises/exercise1.pdf) ([Solution](exercises/solution1.pdf))
* [Partial differential equations](lectures/partialDifferentialEquations.ipynb) - [Exercise](exercises/exercise2.pdf) ([Solution](exercises/solution2.pdf))
  * [Elliptic equations](lectures/ellipticEquations.ipynb) (Laplace equation) - [Exercise](exercises/exercise3.pdf) ([Solution](exercises/solution3.pdf))
  * [Parabolic equations](lectures/parabolicEquations.ipynb) (heat equation/diffusivity equation)
  * [Hyperbolic equations](lectures/hyperbolicEquations.ipynb)(wave equation)
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
  * [Simulated Annealing](lectures/simulatedAnnealing.ipynb)
  * [Evolutionary algorithms](lectures/evoluationaryAlgorithms.ipynb)
    * [Genetic algorithm](lectures/geneticAlgorithm.ipynb)
    * [Particle swarm optimization](lectures/particleSwarmOptimization.ipynb)
* [Automatic differentiation](lectures/automaticDifferentiation.ipynb)


### Neural networks ###

<!-- clustering (k-means), suport vector machine, decision trees, eksempler med bruk av scikit-learn -->
* [Neural networks](lectures/neuralNetworks.ipynb)
<!-- dimensions redusering (både med nevrale netverk og egenvektorer/egenverdier) - U-nets -->
<!-- diffusjonsmodeller for å generere nye eksempler -->

### Exercises
* [Exercise 1](exercises/exercise1.pdf)
   * [Solution 1](exercises/solution1.pdf)
* [Exercise 2](exercises/exercise2.pdf)
   * [Solution 2](exercises/solution2.pdf)
* [Exercise 3](exercises/exercise3.pdf)
   * [Solution 3](exercises/solution3.pdf)
