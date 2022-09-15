# **On the utilization of pair-potential energy functions in multi-objective optimization**

by Jesús Guillermo Falcón-Cardona<sup>a</sup>, Edgar Covantes Osuna<sup>a</sup>, Carlos A. Coello Coello<sup>b</sup>, and Hisao Ishibuchi<sup>c</sup>

<sup>a</sup> Tecnológico de Monterrey, School of Engineering and Sciences, Av. Eugenio Garza Sada 2501 Sur, Col. Tecnológico, 
Monterrey, Nuevo León, México 64849.

<sup>b</sup> CINVESTAV-IPN, Department of Computer Science, Av. IPN 2508, Col. San Pedro Zacatenco, México City, México 07360.

<sup>c</sup> Southern University of Science and Technology, Department of Computer Science and Engineering, 1088 Xueyuan Avenue, 
Shenzhen, People's Republic of China, 518055.

## **Content**

This repository contains all the experimentation defined in the paper. The file GenerateRefSets.zip contains the source code (in C language) to generate pair-potential 
energy-based reference sets. The instructions for compiling and running the experiments are in the README.txt file inside .zip file.

Also, folder PPF-predicting-alpha contains a companion notebook for the paper titled with the same name. For readability, the notebook 
can be considered as supplementary material for **Section 3.2.2. Predicting $\alpha$**.

**This repository omits everything else in the paper (except section 3.2.2):**

---
1. Introduction
2. Background
    * 2.1. Multi-objctive optimization
    * 2.2. Definition of PPFs
3. On the utilization of pair-potential energy functions
    * 3.1. Approximately solving the PPFSS
    * 3.2. Analysis of parameters
        *  3.2.1. Approximating the optimal value of $\alpha$
        *  [3.2.2. Predicting the optimal value of ](https://github.com/jguillermofc/Pair-Potential-Energy/blob/d5a4727bd154ad1ecf0e16fdd03a4228e31d6d3d/PPF-predicting-alpha/pair-potential-functions-predicting-alpha.ipynb)$\alpha$
    * 3.3. PPF-based reference point sets
    * 3.4. PPF-based archiving
4. Conclusions and future work

**If a more detailed explanation is needed, we recommend reading the notebook side by side with a copy of the paper.**

## **Supplementary material**

In the following link, you can download all the supplementary material, including plots, source code, and reference sets: [supplementary material](https://drive.google.com/drive/folders/1A5t6jugHHEUeAWwZ-amltfwxvNme0qOp?usp=sharing)
