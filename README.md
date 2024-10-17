# MS_Thesis
My Master Thesis Work

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>REAGLE Framework</title>
</head>
<body>

    <h1>Reinforcement Learning with Edge Attention Networks (REAGLE)</h1>

    <p>Reinforcement Learning (RL) has achieved remarkable success across a variety of domains, yet sample complexity remains a challenge, especially when actions are taken in the real world. To improve the effectiveness of RL, researchers have turned to deep neural networks that learn useful representations of the data that can improve and speed up the learning process.</p>

    <p>In particular, Graph Neural Networks (GNNs) have emerged as a powerful tool for handling data with inherent graph structures, such as social networks, communication systems, and biological networks. Despite these advances, traditional approaches using Relational Graph Convolutional Networks (R-GCNs) often rely on statically weighted graphs, which do not adequately capture the dynamic nature of many RL environments.</p>

    <p>To overcome this limitation, in this study, we propose an integration of Graph Attention within an R-GCN framework for model-free RL algorithms called <strong>REAGLE</strong> (Reinforcement learning with Edge Attention Networks). This technique applies dynamic edge weighting, treating connections (relations) unequally based on their current relevance. By dynamically prioritizing relations, our model focuses computational resources on the most crucial information at each step, thereby improving sample efficiency.</p>

    <p>We validate our approach across different Minigrid environments, including the Boxworld domain, a grid-world navigation challenge designed to evaluate relational reasoning capabilities. Our results demonstrate that REAGLE surpasses conventional graph-based reinforcement learning algorithms by achieving faster learning, better decision quality, and significantly lower sample complexity.</p>

    <!-- Add Image -->
    <figure>
        <img src="reagle-framework.png" alt="REAGLE Framework" style="width:100%;max-width:600px;">
        <figcaption>Figure: REAGLE Framework demonstrating dynamic edge weighting in RL environments.</figcaption>
    </figure>

</body>
</html>






