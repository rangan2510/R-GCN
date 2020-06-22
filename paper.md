
# Residual GCN

## Potential Titles
- Multi-species Protein association prediction using residual graph convolutional network
- rGCN: a residual graph convolutional network model to predict multi species protein inter-connection using biochemical and physiological features

## Authors

Rangan Das, Bikram Boote

## Abstract

Graph Convolutional Networks (GCNs) have recently received a lot of attention for their capability of representation learning on non-Euclidian feature spaces. GCNs aggregate the neighbouring node features and attributes to learn graph representations. Like traditional deep learning models, the representation power of GCNs also increases with the increasing number of layers. However, it also increases the difficulty associated with training such models. Deep GCNs suffer from issues like vanishing gradient or overfitting. In this paper, we explored skip connections in GCNs and proposed a deep residual graph convolutional neural network for predicting node properties in a protein-protein interaction network. The proposed model is an improvement over traditional deep learning models and present state-of-the-art graph learning algorithms. 




## Introduction

Graph Convolutional Networks (GCNs) have gained a lot of traction recently with the increased availability of graph datasets. GCNs have shown potential in multiple domains that deal with unstructured data, such as social networks, recommendation systems, bioinformatics, text mining and many more. Graph convolutions in GCNs are implemented using a message passing technique. In each GCN layer, node features are updated by propagating information via adjacent nodes. However, most GCN based models rely on shallow learning models.
The reason for the popularity of Convolutional Neural Networks (CNNs) is because they can be trained very reliably. In many state-of-the-art computer vision problems, CNNs have been used which have over a hundred layers. CNNs mostly deal with structured data where the tensor elements are present in a meaningful order. However, graphs do not have any form of fixed tensor ordering. This makes training GCNs much more difficult than training CNNs \cite{}.
Recent works have also focused on training deeper GCNs and show how increasing the depth of these networks also improves performance. However, increasing the depth of GCNs also makes the convergence of the network more difficult. Like deep CNNs, GCNs suffer from issues such as over-fitting and vanishing gradient. Stacking multiple layers in GCN also leads to the problem of over-smoothing. Over-smoothing occurs when the representation of nodes of different classes become indistinguishable. Another issue with training deep networks is the issue of degradation. Degradation happens when the accuracy of the network gets saturated quickly and then rapidly degrades. The issue persists in both CNNs and GCNs, where increasing the depth of the network increases the training error. These are some of the issues why most recent state-of-the-art GCNs are shallow in nature \cite{}.



## Representation Learning on Graphs
[short desc of graph conv + SAGEconv]

## Residual Graph Convolution Networks

## Results
### Ablation Study

## Conclusion


