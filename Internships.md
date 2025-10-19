# Internships proposed by Rémy Cazabet, Academic year 2025/2026
### Location
Internships will take place at LIRIS Lab, Lyon 1 University, Lyon, France.

### Funding
I have funding for 2 of these internships this year: Subject 1 and one of Subject 2 or Subject 3.

### PhD opportunities
I do not have funding for PhD students this year. If a student is in the top 25% of their class, it is possible to candidate for public funding. I also often receive PhD offers in relevant topics around June/July.

### Subject 1: Fast community detection in dynamic networks by optimizing Longitudinal Modularity
Community detection, also known as graph clustering, is a classic unsupervised problem on graphs/networks. 

Most real-world networks are dynamic: economic transactions, online social networks, interactions between individuals, etc. Discovering communities in dynamic networks is still a challenge, as no widespread method exists.

We recently proposed Longitudinal-Modularity, an adaptation of the Modularity for temporal networks (https://epjdatascience.springeropen.com/articles/10.1140/epjds/s13688-025-00529-x). It is the first objective function adapting modularity for link streams, i.e., continuous-time temporal networks.

We later proposed a first method to optimize this quality function on link streams, with the LAGO algorithm (https://arxiv.org/abs/2510.00741). This method has good performance, but do not scale to large networks. 

Your objective in this internship will be to propose a method for optimizing L-Modularity on large temporal networks. Although you will be free to use any relevant method, we will favor Big Data Frameworks such as PySpark. Compared with LAGO, we will be ready to accept some loss in quality optimization for large gains in scalability.

In this internship, you will work closely with a PhD student who proposed L-Modularity and LAGO.

### Subject 2: GNN for Community Detection in networks without attributes
Graph Neural Networks (GNN) achieve state-of-the-art performance on network tasks such as link prediction and node classification. However, they still struggle with unsupervised tasks, such as community detection. In this exploratory research internship, we will explore various approaches to perform community detection with GNNs.
* We will take inspiration from existing methods, such as the adaptation to GNNs of Infomap (https://proceedings.neurips.cc/paper_files/paper/2024/hash/1f59562caae05e6aae0ffd1145bea5da-Abstract-Conference.html) and Modularity (https://www.jmlr.org/papers/volume24/20-998/20-998.pdf).
* We will focus on networks without attributes, an uncommon scenario with GNNs. This requires defining ad-hoc node attributes, which can be done with various heuristics. We will explore the most promising one and search for new strategies
* We will focus on adapting Stochastic Block Model methods, and compare quantitatively the performance achieved by our model with the best methods for SBM inference with traditional approaches.
* One of the main challenges to tackle will be 1) parsimony: how to automatically discover the right number of clusters? 2)Adapting the SBM objective function to make it fully differentiable.

### Subject 3: SHAP-Like multi-model graph XAI
In the context of link prediction, explaining why a particular link is predicted is a challenge. Many methods have been proposed already, but they mostly rely on **local explanations**, i.e., for a particular pair of nodes, the explanation consists on a weighted subgraph. But interpreting this subgraph is still at the charge of the user. Instead, in this internship, we will design a new XAI model to explain link prediction by additive model combination. The principle will be similar to SHAP: The probability of predicting a link will be decomposed as a sum of effects coming from various sources. However, instead of being a combination of node variables, we will instead consider various graph models. The principle will be to first fit various graph models to the network of interest: louvain communities, SBMs, latent space models, core periphery, etc. Then for each pair of node, our objective will be to compute the gain due to each of these models compared with using a subset of the other models, and/or node attributes. 
