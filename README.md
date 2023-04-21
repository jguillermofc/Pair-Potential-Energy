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
can be considered as supplementary material for **Predicting the optimal value of $\alpha$**.

**This repository omits everything else in the paper (except section 5.2):**

1. Introduction
2. Background
    * 2.1. Multi-objctive optimization
    * 2.2. Definition of PPFs
3. Diversity-preserving mechanisms: a brief review
4. Fast greedy removal algorithm
5. Analysis of parameters
    * 5.1. Approximating the optimal value of $\alpha$
        * 5.1.1. Newton-based $\alpha$ aproximation for $U_{\alpha}^{\mathcal{K}}$
        * 5.1.2. Genetic-based $\alpha$ aproximation for $U_{\alpha}^{\mathcal{K}}$ 
    * 5.2. Predicting the optimal value of $\alpha$  
6. On the utilization of PPFs in multi-objetive optimization
   * 6.1. PPF-based reference points sets
   * 6.2. PPF-based archiving
   * 6.3. Limitations on the use of PPFs
7. Conclusions and future work

**If a more detailed explanation is needed, we recommend reading the content of this repository side by side with a copy of the paper.**

## **Supplementary material**

In the following link, you can download all the supplementary material, including plots, source code, and reference sets: [supplementary material](https://drive.google.com/drive/folders/1A5t6jugHHEUeAWwZ-amltfwxvNme0qOp?usp=sharing)

## Cite the paper
If the paper or the code provided in this repository helps you in your research, you can cite the paper using the following BibTeX entry:

@article{Falcon2023,
   author = {Jes{\'u}s Guillermo Falc{\'o}n-Cardona and Edgar {Covantes Osuna} and Carlos A. {Coello Coello} and Hisao Ishibuchi},
   title = {On the utilization of pair-potential energy functions in multi-objective optimization},
   journal = {Swarm and Evolutionary Computation},
   volume = {79},
   pages = {101-308},
   year = {2023},
   issn = {2210-6502},
   doi = {https://doi.org/10.1016/j.swevo.2023.101308},
   url = {https://www.sciencedirect.com/science/article/pii/S2210650223000810}
}
