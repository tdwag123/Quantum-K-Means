# Quantum-K-Means
A basic implementation of Quantum K-Means.
## Notes for Quantum K-Means
### Overview of difference between QK-Means and K-Means
**Core Idea:** Use a **swap test** circuit to compute the fidelity between two quantum states. The fidelity is then converted into a distance metric to perform standard K-Means clustering.
### References
Kerenidis, I., Landman, J., & Prakash, A. (2022). Quantum Algorithms for Learning via Neural Networks. arXiv preprint arXiv:2212.06691. [Link](https://arxiv.org/abs/2212.06691)
### Potential Improvements & Next Steps
-Better initialization such as K-means++ initialization or q-means initialization
-Run on the real quantum computers at IBM
-Think about how/if fidelity fairs at sparse data in higher dimensions. Can QC offer a fix to that? Is there a reason to use QC for something here other than speedup?
