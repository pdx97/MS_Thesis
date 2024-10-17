# MS_Thesis
My Master Thesis Work

# <h1>Title</h1>


Dynamic Edge Weighting in Relational Graph Convolutional Networks: Enhancing Sample Efficiency via Graph Attention in Reinforcement Learning


# <h2> Abstract</h1>
Reinforcement Learning (RL) has achieved remarkable success across a variety of do-
mains, yet sample complexity remains a challenge, especially when actions are taken in the
real world. To improve the effectiveness of RL, researchers have turned to deep neural net-
works that learn useful representations of the data that can improve and speed up the learning process. In particular, Graph Neural Networks (GNNs) have emerged as a powerful tool
for handling data with inherent graph structures, such as social networks, communication
systems, and biological networks. Despite these advances, traditional approaches using Relational Graph Convolutional Networks (R-GCNs) often rely on statically weighted graphs,
which do not adequately capture the dynamic nature of many RL environments. To overcome this limitation, in this study, we propose an integration of Graph Attention within an
R-GCN framework for model-free RL algorithms called REAGLE (Reinforcement learning
with Edge Attention Networks) . This technique applies dynamic edge weighting, treating
connections (relations) unequally based on their current relevance. By dynamically prioritizing relations, our model focuses computational resources on the most crucial information at each step, thereby improving sample efficiency. We validate our approach across
different Minigrid environments, including the Boxworld domain, a grid-world navigation
challenge designed to evaluate relational reasoning capabilities. Our results demonstrate
that REAGLE surpasses conventional graph-based reinforcement learning algorithms by
achieving faster learning, better decision quality, and significantly lower sample complexity.

<figure>
    <img src="Heatmaps and Visualizations/High_Level_architecture.drawio (2).png" alt="REAGLE Framework" style="width:100%;max-width:600px;">
    <figcaption style="text-align:center;">Overview of the Framework.</figcaption>
</figure>






