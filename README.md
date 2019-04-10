# Unveiling the potential of GNN for network modeling and optimization in SDN

#### K. Rusek, J. Suárez-Varela, A. Mestres, P. Barlet-Ros, A. Cabellos-Aparicio.
Proceedings of the 2019 ACM Symposium on SDN Research (SOSR), pp. 140-151, San Jose, April 2019. 

Link to paper: [arXiv:1901.08113](https://arxiv.org/abs/1901.08113).

#### Citation
You can cite this paper as follows:

```
@inproceedings{gnnnetworks,
  title={Unveiling the potential of {GNN} for network modeling and optimization in {SDN}},
  author={Rusek, Krzysztof and Su\'arez-Varela, Jos\'e and Mestres, Albert and Barlet-Ros, Pere and Cabellos-Aparicio, Albert},
  booktitle={Proceedings of the ACM Symposium on SDN Research (SOSR)},
  pages={140-151},
  year={2019}
}
```

## Abstract
Network modeling is a critical component for building self-driving Software-Defined Networks, particularly to find optimal routing schemes that meet the goals set by administrators. However, existing modeling techniques do not meet the requirements to provide accurate estimations of relevant performance metrics such as delay and jitter. In this paper we propose a novel Graph Neural Network (GNN) model able to understand the complex relationship between topology, routing and input traffic to produce accurate estimates of the per-source/destination pair mean delay and jitter. GNN are tailored to learn and model information structured as graphs and as a result, our model is able to generalize over arbitrary topologies, routing schemes and variable traffic intensity. In the paper we show that our model provides accurate estimates of delay and jitter (worst case R<sup>2</sup>=0.86) when testing against topologies, routing and traffic not seen during training. In addition, we present the potential of the model for network operation by presenting several use-cases that show its effective use in per-source/destination pair delay/jitter routing optimization and its generalization capabilities by reasoning in topologies and routing schemes not seen during training.

We provide the source code of [routenet](https://github.com/knowledgedefinednetworking/net2vec/tree/master/routenet) and give some instructions on how to train new models.

We also provide access to the [datasets](datasets) and the [models](trained_models) already trained that we used for the evaluation of the accuracy in our paper.

<p align="center"> 
  <img src="/assets/scheme_GNN_model.PNG" width="400" alt>
</p>
<p align="center"> 
    <em>Schematic representation of RouteNet</em>
</p>

<p align="center"> 
  <img src="/assets/routenet_architecture.PNG" width="700" alt>
</p>
<p align="center"> 
    <em>Internal architecture of RouteNet</em>
</p>
