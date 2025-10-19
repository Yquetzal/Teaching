# Internships proposed by Rémy Cazabet 
### Location
Internships will take place at LIRIS Lab, Lyon 1 University, Lyon, France.

### Subject 1: Fast community detection in dynamic networks by optimizing Longitudinal Modularity
Community detection, also known as graph clustering, is a classic unsupervised problem on graphs/networks. 

Most real-world networks are dynamic: economic transactions, online social networks, interactions between individuals, etc. Discovering communities in dynamic networks is still a challenge, as no widespread method exists.

We recently proposed Longitudinal-Modularity, an adaptation of the Modularity for temporal networks (https://epjdatascience.springeropen.com/articles/10.1140/epjds/s13688-025-00529-x). It is the first objective function adapting modularity for link streams, i.e., continuous-time temporal networks.

We later proposed a first method to optimize this quality function on link streams, with the LAGO algorithm (https://arxiv.org/abs/2510.00741). This method has good performance, but do not scale to large networks. 

Your objective in this internship will be to propose a method for optimizing L-Modularity on large temporal networks. Although you will be free to use any relevant method, we will favor Big Data Frameworks such as PySpark. Compared with LAGO, we will be ready to accept some loss in quality optimization for large gains in scalability.

### Subject 2: GNN for Community Detection in networks without attributes
Graph Neural Networks (GNN) achieve state of the art performance on network tasks such as link prediction and node classification.
