# Mathematical foundations of data analysis
Winter semester 22-23, University of Leipzig, 10-INF-DS201

Goals:
- Understand the definitions of standard data science terms, and the associated mathematical terms
- Understand the proofs of how commonly used techniques in data science work
- Implement the algorithms and examples with a computer program
- Investigate the math behind your favorite topic in data science

We first cover two introductory topics
1. Linear algebra
  - Subspaces
  - Orthogonality
  - The pseudo-inverse
  - the singular value decomposition
2. Probability Theory

We then proceed with the following four themes commonly seen in data science

3. Network analysis
  - Graphs and the Laplace matrix
  - The spectrum of a graph
  - Markov processes in networks
  - Centrality measures
4. Machine learning
  - Data, models, and learning
  - Regeression in statistical models
  - Principal component analysis (method for dimension reduction)
  - Support vector machines (binary classification method)
5. Topological data analysis
  - Simplicial complexes and homology
6. Matrices and tensors
  - Low rank matrices and tensors
---

## Course Information 
- From 11. October 2022 through 1. February 2023
- Tuesdays 11:15-12:45 (Lecture)
- Wednesdays 15:15 - 16:45 (Seminar)
- SG 2-14

- Contact: samantha.fairchild(at)mis.mpg.de
- Office hours: Tuesdays and Wednesdays after class, and by email.

Grading scheme:
- 10% Homework: assigned every other week, hand in 1 problem for grading.
- 40% Project: Due 18.01 in class: Pick a data science topic and learn about the math behind it. Must include 1 proof and 1 example (~2 pages)
- 50% Exam: written theory exam covering entire course, mainly computations and examples.

---
## Course Schedule

| Date | Topics |
|------|--------|
|  11.10    |  Orthogonal projections and the Pseudo-Inverse |
|12.10| No class (Immatrikulationsfeier)|
|  18.10    |   (Katerina Papagiannouli) Probability theory introduction: Random variables and Bayes' Theorem |
|  19.10    |   (Simone  Steinbruechel) (uniqueness of) singular value decompositions |
|25.10| Expected Value and Variance, the normal distribution|
|26.10| Network Analysis: the Laplace matrix|
|01.11| Spectrum of a graph, and the relationship to structure of a graph (HW 1 due)|
|02.11|(SM) Eigenvectors of the Laplace matrix, Notebook 2 Example|
|08.11|(SM) Diameter of a graph, spanning trees, and definition of a Markov process|
|09.11|(SM) Transition matrices and stationary distributions|
|15.11| (Katerina Papagiannouli) Existence and uniqueness of stationary distributions, Metropolis--Hastings algorithm |
|16.11| No class (Buß- und Bettag)|
|22.11|(SM) Machine Learning: Data, models, and learning (HW 2 due) |
|23.11|(SM) Linear regression, least squares, MLE|
|29.11| Non-linear regression, MAP and Bayesian approach (Notebook 4)|
|30.11| Nueral networks |
|6.12|Support vector machines (primal)|
|7.12| Dual SVMs and Kernels (Notebook 5, HW 3 due)|
|13.12| Deriving the Dual SVM |
|14.12| Principal component analysis (PCA)|
|20.12| PCA continued, Notebook 6 (HW 4 due)|
|21.12-03.01|Winter Break|
|4.01| Topological data analysis: Simplicies|
|10.01| Simplicial complexes, Čech and Vietoris-Rips complex|
|11.01| Comparing Čech and Vietoris-Rips complex, homology of planar complexes|
|17.01| Homology, Betti numbers, Euler characteristic|
|18.01| Persistent homology, Notebook 6|
|24.01| Review topics: Pseudoinverse, Metropolis Hastings algorithm, application of Markov processes to data science, Min-cut definitions (HW 5 due)|
|25.01| Continue Review topics|
|31.01| Practice final exam|
|1.02|Going through solutions to practice final exam|
|14.02| Final exam from 11:15-12:45 in Raum: S 110, Seminarraum Ort: Semi|


---

## Julia und Jupyter Notebooks

This repository contains the [Jupyter Notebooks](https://github.com/skfairchild/MathData-Winter22-23) from the class.

In order to use the notebooks:

* Download the notebooks (Click on the green `Code` Button or download as Zip File or use a Git Client such as [Github Desktop](https://desktop.github.com) oder [Sublime](https://www.sublimemerge.com)).
* Download the newest version of Juila [here](https://julialang.org/downloads/).
* Start Juila.
* Enter the package manager by putting in `]` in the package manager.
* `add IJulia`
* Leave the package manager with a backspace.
* `using IJulia` 
* `notebook()` 

Then a browser window should open, in which the local saved notebooks can be opened.D

Other material from the [Julia Academy](https://github.com/JuliaAcademy):

* [Introduction to Julia](https://github.com/JuliaAcademy/Introduction-to-Julia)

* [Data Science](https://github.com/JuliaAcademy/DataScience)

* [Foundations of Machine Learning](https://github.com/JuliaAcademy/Foundations-of-Machine-Learning)

* [Data Frames](https://github.com/JuliaAcademy/DataFrames)

---

## Literature
The following materials are chosen to complement the [course lecture notes](https://raw.githubusercontent.com/skfairchild/MathData-Winter22-23/main/MathData.pdf)

### 1. Linear Algebra

[The Fundamental Theorem of Linear Algebra](https://www.engineering.iastate.edu/~julied/classes/CE570/Notes/strangpaper.pdf), Gilbert Strang.

### 2. Probability Theory

[Wikipedia Artikel](https://en.wikipedia.org/wiki/Probability_theory)

[Basic Probability Theory](https://faculty.math.illinois.edu/~r-ash/BPT/BPT.pdf), Robert B. Ash.

### 3. Network Analysis

[Spectral Graph Theory](https://mathweb.ucsd.edu/~fan/research/revised.html)
(insbesondere Kapitel 1), Fan Chung.

[Spectral Graph Theory](https://resources.mpi-inf.mpg.de/departments/d1/teaching/ws11/SGT/) (insbesondere Vorlesung 5), Thomas Sauerwald and He Sun

[Graph Theory in the Information Age](https://mathweb.ucsd.edu/~fan/wp/graph.pdf), Fan Chung.

[Computer Science Theory for the Information Age](https://www.cs.cmu.edu/~venkatg/teaching/CStheory-infoage/) (insbesondere Notes 5), Venkatesan Guruswami and Ravi Kannan.

### 4. Machine Learning

[Mathematics for Machine Learning](https://mml-book.github.io/book/mml-book.pdf) (insbesondere Kapitel 8-12), Marc Peter Deisenroth, A. Aldo Faisal und Cheng Soon Ong.

[Neural Network Theory](http://www.pc-petersen.eu/Neural_Network_Theory.pdf), Philipp Christian Petersen

### 5. Topological Data Analysis

[Topological Data Analysis Spring 2020](https://www.few.vu.nl/~botnan/lecture_notes.pdf), Magnus Bakke Botnan.

[Topological Data Analysis](https://fugacci.github.io/home/notes.html), Ulderico Fugacci.

### 6. Matrices and Tensors

[Geometric Methods on Low-Rank Matrix and Tensor Manifolds](https://link.springer.com/content/pdf/10.1007%2F978-3-030-31351-7_9.pdf), André Uschmajew and Bart Vandereycken.

[Tensor Decompositions and Applications](https://www.kolda.net/publication/TensorReview.pdf),
Tamara G. Kolda und Brett W. Bader.


