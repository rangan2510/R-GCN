
# Residual GCN

## Potential Titles
- Multi-species Protein association prediction using residual graph convolutional network
- rGCN: a residual graph convolutional network model to predict multi species protein inter-connection using biochemical and physiological features

## Authors

Rangan Das, Bikram Boote

## Abstract

Graph Convolutional Networks (GCNs) have recently received a lot of attention for their capability of representation learning on non-Euclidian feature spaces. GCNs aggregate the neighbouring node features and attributes to learn graph representations. Like traditional deep learning models, the representation power of GCNs also increases with the increasing number of layers. However, it also increases the difficulty associated with training such models. Deep GCNs suffer from issues like vanishing gradient or overfitting. In this paper, we explored skip connections in GCNs and proposed a deep residual graph convolutional neural network for predicting node properties in a protein-protein interaction network. The proposed model is an improvement over traditional deep learning models and present state-of-the-art graph learning algorithms. 




## Introduction

Graph Convolutional Networks (GCNs) have gained a lot of traction recently with the increased availability of graph datasets. GCNs are a generalization of the convolutional neural networks (CNNs) that works on unstructured data, such as graphs. These graph neural networks are called convolutional because the filter parameters are shared all across the graph or a subset of the graph. Graph convolutions in GCNs are implemented using a message passing technique. The model learns by taking features of vertices of a graph as well as the connectivity of the graph in the form of an adjacency matrix and produces a vertex-level output. In each GCN layer, node features are updated by propagating information via adjacent nodes. GCNs have shown potential in multiple domains that deal with unstructured data, such as social networks, recommendation systems, bioinformatics, text mining and many more. However, most GCN based models rely on shallow learning models and may fail to discovery more complex patterns present in the graph. 

On the other hand, deep learning models have proven to be reliable in multiple areas. Deep convolutional neural networks (CNNs) have achieved exceptional performance in the domains of computer vision or natural language processing. The reason for the popularity of CNNs is because they can be trained very reliably even when the architecture is multiple layers deep. In many state-of-the-art computer vision problems, CNNs have been used which have over a hundred layers. CNNs mostly deal with structured data where the tensor elements are present in a meaningful order.  Localized filters in the convolution layers can be easily trained because of the grid-like nature of the images. However, graphs do not have any form of fixed tensor ordering. This makes training GCNs much more difficult than training CNNs \cite{}.

Recent works have also focused on training deeper GCNs. They show how increasing the depth of these networks also improves performance. However, increasing the depth of GCNs also makes the convergence of the network more difficult. Like deep CNNs, GCNs suffer from issues such as over-fitting and vanishing gradient. Stacking multiple layers in GCN also leads to the problem of over-smoothing. Over-smoothing occurs when the representation of nodes of different classes become indistinguishable. Another issue with training deep networks is the issue of degradation. Degradation happens when the accuracy of the network gets saturated quickly and then rapidly degrades. The issue persists in both CNNs and GCNs, where increasing the depth of the network increases the training error. These are some of the issues why most recent state-of-the-art GCNs are shallow in nature \cite{}. These issues have addressed in CNNs by using skip connections that were introduced in ResNets.  This allowed the deeper layers of the network to learn from the input to the shallower layers. It also provided the gradient additional paths, making the networks easier to optimize. A similar approach can be used for GCNs to create deeper models. 

In this paper, we propose a deep GCN for predicting node properties in a protein-protein interaction (PPI) graph that makes use to skip connections or residual connections. Using residual connections enable the model to go deeper and perform better than the traditional state-of-the-art graph learning models. 

Contributions: The contributions of this paper are as follows:
Residual connections in the case of graph convolutions are widely unexplored. The model proposed in this paper makes use of graph convolutions as well as GraphSAGE, an inductive representation learning for graphs, which have not been done before.
The paper proposes a deep residual graph convolutional network for PPI that is _ layers deep and outperforms standard models in that task.
The model can be further used for predicting molecular properties of unknown proteins and aid in prognosis and drug discovery.


## Representation Learning on Graphs
[short desc of graph conv + SAGEconv]

## Residual Graph Convolution Networks

## Methodology

## Results
### Ablation Study

## Conclusion


