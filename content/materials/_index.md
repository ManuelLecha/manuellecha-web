# Materials

{{< math >}}

## Seminars

### (01-02-2023) The Geometric Deep Learning Blueprint [[SLIDES]](./GDL%20Seminar.pdf)

In this talk at the [HupBa](https://hupba.com) seminar I delved into the foundational aspects of the Geometric Deep Learning (GDL) blueprint, concentrating on the first three chapters of the [Geometric Deep Learning Proto Book](https://arxiv.org/abs/2104.13478). As a mathematician, I am particularly enthusiastic about this approach, which leverages geometric priors such as invariance and equivariance with respect to group actions as a general framework for building novel deep neural network architectures.

The seminar provided an overview of GDL's mathematical foundations, highlighting the principles and mathematical underpinnings that enable the framework to respect the structure and geometry of data across various domains.

By integrating geometric properties like symmetry, locality, and multiscale processing, GDL promotes efficient learning and helps to mitigate the curse of dimensionality, ultimately enhancing the performance of models on complex, high-dimensional data.

### (18-01-2023) Multiparameter Persistent Homogy [[SLIDES]](./MPH%20Seminar.pdf)

In this talk at the [HupBa](https://hupba.com) seminar I introduced the theory of Multiparameter Persistent Homology to the group.

Multiparameter Persistent Homology (MPH) is the persistence theory associated with multifiltrations, i.e., with persistence modules indexed by a product of total order categories. Although the $1D$-persistence theory enjoys many excellent properties, several reasons motivate us to consider multifiltrations. For instance, MPH might be a natural choice when working with datasets with outliers or significant variations of density or with data that comes naturally equipped with any real-valued function, such as time-varying data.

MPH yields more flexible and richer data invariants than $1D$-persistence, but also involves dealing with more complex objects. Multiparameter persistence modules can be viewed as commutative diagrams of vector spaces, which have been deeply studied in quiver representation theory. This theory provides an insightful perspective on the classification of MPH modules, which have wild representation types, making any possible parametrization hopeless. 

Invariants like the Hilbert function, the rank invariant, and the multigraded Betti numbers serve as a surrogate for the $1D$-barcode in MPH and play a central role in applications.

## Theses

### MSc Thesis [[PDF]](./MSc%20Thesis.pdf)

**Title:** General Persistence Theory: Towards Multiparameter Persistent Homology. <br>

{{< toggle Abstract >}}
Topological data analysis (TDA) emerged as a field of research aiming to obtain topological descriptors of datasets. Persistent Homology was elaborated in the early 2000's as a first theoretical approach to obtain such descriptors. In particular, Persistent Homology seeks to estimate the homology of data's underlying topology. The general pipeline involves two main steps: Given a dataset $\mathcal{X}$, we

1. Build a commutative diagram $F(\mathcal{X})$ of topological spaces, also known as filtration, which we presume might contain meaningful information about the actual topology of $\mathcal{X}$,
   
2. Compute the $n$-th homology of the diagram $F(\mathcal{X})$ to algebraically analyse the resulting object $H_n \circ F(\mathcal{X})$, the persistence module.

This work aims to explore Persistence Theory in its full generality and comprehensively introduce its background. As a particular instance of persistence theory, we first examine one parameter persistence theory, which arises from uniparametric filtrations of spaces. Although enjoying many excellent properties, we provide sufficient examples showing that it does often not capture the structure of interest in addition of being sensitive to outliers. Therefore, we are motivated to consider multiparametric filtrations, which led us to Multiparamer Persistence Theory. Multiparameter persistence modules are more flexible and richer than the ones arising from one parameter persistence. However, as a result, they become more complex and opaque, which motivates us to seek alternative invariants.
{{< /toggle >}} 

### BSc Thesis [[PDF]](./BSc%20Thesis.pdf)
**Title:** Persistent Homology: Functional Summaries of Persistence Diagrams for Time Series Analysis. <br>
{{< toggle Abstract >}}
Topological data analysis (TDA) is a recently emerged field of study, a point of confluence between Algebraic Topology, Statistics and Computation Theory, born to develop a new set of tools capable of extracting qualitative and quantitative information from the data's underlying geometrical and topological structure. In these notes, we first present the theoretical foundations of the flagship tool of TDA, persistent homology.
Later, we provide a framework that allows us to understand homological persistence from a statistical perspective. The latter comprises a set of maps called functional summaries, which map persistence diagrams -a common representation of persistence homology- to $L$-Lipschitz functions, a more convenient representation for data analysis. We present persistence landscapes, silhouettes, and a new functional summary candidate based on persistence entropy under this framework.

From this point on, we will focus our work on TDA for time series, and more specifically, financial time series. First, we present the time-delay embedding and the sliding window approach, two methodologies that will allow us to transform time series into sequences of point clouds, which is essential for applying homological persistence tools. 

Subsequently, we prove that the results reflected on the dependency relationship between persistence landscapes functional norms and variance-covariance for multivariate time series embedded via the sliding window method are valid for time series understanding them as a realization of a weakly stationary stochastic process, and assuming that the point clouds are obtained by means of time delay embedding. Furthermore, we assert that the validity of the results provided in and the validity of our adaptation hold for silhouettes.

Moreover, we provide two distinct Python frameworks for classical and topological data analysis, which serves us to validate results. First, we provide a collection of tools to simulate time series from standard probability distributions and time series models such as AR(1), ARCH(1), GARCH(1,1). We present the necessary tools to embed, plot, and compute, topological summaries such persistence diagrams, persistence landscapes (and their corresponding $L_p$ norms), silhouettes (and their corresponding $L_p$ norms), persistence entropy, ES and NES functions. Analogous work is done regarding statistical and topological data analysis of stock index data.
{{< /toggle >}} 





