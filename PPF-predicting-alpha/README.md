# **On the utilization of pair-potential energy functions in multi-objective optimization**

by Jesús Guillermo Falcón-Cardona<sup>a</sup>, Edgar Covantes Osuna<sup>a</sup>, Carlos A. Coello Coello<sup>b</sup>, and Hisao Ishibuchi<sup>c</sup>

<sup>a</sup> Tecnológico de Monterrey, School of Engineering and Sciences, Av. Eugenio Garza Sada 2501 Sur, Col. Tecnológico, 
Monterrey, Nuevo León, México 64849.

<sup>b</sup> CINVESTAV-IPN, Department of Computer Science, Av. IPN 2508, Col. San Pedro Zacatenco, México City, México 07360.

<sup>c</sup> Southern University of Science and Technology, Department of Computer Science and Engineering, 1088 Xueyuan Avenue, 
Shenzhen, People's Republic of China, 518055.

This repository contains a companion notebook for the paper titled with the same name. For readability, the notebook 
can be considered as supplementary material for **Section 3.2.2. Predicting $\alpha$**. 

The $\alpha$ parameter is the most critical one in the study of pair-potential energy functions since it 
controls the rate of decrease of the kernels. Hence, it directly influences the overall pair-potential energy 
of the Pareto front approximation which impacts its diversity. In this repository, we provide a DNN to determine 
how to set $\alpha$ to generate the Pareto front approximations that adequately represent the underlying manifold.

**This repository omits everything else in the paper (except section 3.2.2):**

---
1. Introduction
2. Background
    * 2.1. Multi-objctive optimization
    * 2.2. Pair-potential energy functions
3. On the utilization of pair-potential energy functions
    * 3.1. Approximating the pair-potential energy-based subset selection problem
    * 3.2. Analysis of parameters
        *  3.2.1. Approximating $\alpha$
        *  [3.2.2. Predicting ](https://github.com/jguillermofc/Pair-Potential-Energy/blob/main/PPF-predicting-alpha/pair-potential-functions-predicting-alpha.ipynb)$\alpha$
    * 3.3. Pair-potential energy-based reference sets
    * 3.4. Pair-potential energy-based archiving
4. Conclusions and future work

**If a more detailed explanation is needed, we recommend reading the notebook side by side with a copy of the paper.**
