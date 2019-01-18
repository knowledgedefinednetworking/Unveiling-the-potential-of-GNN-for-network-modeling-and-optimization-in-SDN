# Unveiling the potential of GNN for network modeling and optimization in SDN

Network modeling is a critical component for building self-driving Software-Defined Networks, particularly to find optimal routing schemes that meet the goals set by administrators. However, existing modeling techniques do not meet the requirements to provide accurate estimations of relevant performance metrics such as delay and jitter. In this paper we propose a novel Graph Neural Network (GNN) model able to understand the complex relationship between topology, routing and input traffic to produce accurate estimates of the per-source/destination pair mean delay and jitter. GNN are tailored to learn and model information structured as graphs and as a result, our model is able to generalize over arbitrary topologies, routing schemes and variable traffic intensity. In the paper we show that our model provides accurate estimates of delay and jitter (worst case $R^2=0.86$) when testing against topologies, routing and traffic not seen during training. In addition, we present the potential of the model for network operation by presenting several use-cases that show its effective use in per-source/destination pair delay/jitter routing optimization and its generalization capabilities by reasoning in topologies and routing schemes not seen during training.

[URL arXiv](http://people.ac.upc.edu/pbarlet/)


<table>
  <tr>
    <td><img src="/assets/breakout.gif?raw=true" width="200"></td>
    <td><img src="/assets/cartpole.gif?raw=true" width="200"></td>
    <td><img src="/assets/pendulum.gif?raw=true" width="200"></td>
  </tr>
</table>

Imlementation is provided in  [routenet](routenet). 
