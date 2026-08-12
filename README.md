# BayesOpt-Trajectory
Behavioural Metric Analysis of Large Language Model-Based Bayesian
Optimization Algorithms
✨ Highlights\\
🔍 Code Evolution Graph (CEG) – A structural analysis framework for understanding how LLM-generated Bayesian optimization algorithms evolve through the evolutionary search process
🌐 Search Trajectory Network (STN) – A behavioural analysis framework for visualizing and characterizing how generated algorithms explore and exploit the optimization landscape
🧬 Evolutionary Structure Analysis – Reconstructs algorithmic lineage across generations and analyzes mutation, crossover, and parent–offspring relationships
📊 Graph-Based Interpretability – Uses graph topology, AST features, code-complexity descriptors, and evolutionary metadata to characterize generated algorithms
🧠 Explainable Algorithm Analysis – Combines PCA, t-SNE, Random Forest, and SHAP to identify structural characteristics associated with optimization performance
🔄Structure + Behaviour – Integrates AOCC performance evaluation with CEG and STN analysis to provide a comprehensive view of LLM-generated optimization algorithms

## Requirements

### CEG

- Python 3.11
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Lizard
- Scikit-learn
- SHAP

### STN

- Python 3.11
- NumPy
- Pandas
- igraph
- Matplotlib

> The STN implementation in this repository is adapted from the original Search
> Trajectory Networks framework by Ochoa, Malan, and Blum. The original STN
> implementation is R-based and uses `igraph`, `plyr`, and `tidyr`.
