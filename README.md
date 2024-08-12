# Fake-News-Detection-Graph-CNN

Used graph convolution operation to classify news articles as real/fake.
Graph convolution is a useful method when the data-points have some(or more) relations with other data-points.
For a conventional deep-learning scheme, it is not feasible to efficiently depict these inter-node relations, which can be interpreted as 'edges' between data-points.
For such situations a graphical structure serves the best at capturing all the details and relations among data-points.
And a GNN comes in handy to handle graph structured data.

The main idea of GNNs is to aggregate data from connected nodes to have some spatial knowledge of the data points, along with the type and strength of relation they have with other data points. Which is achieved using graph convolution operation.

The idea is very similar to routing algorithms in connected networks where nodes pass self-information to other nodes and receive local data to estimate its spatial information in the graph.

One can study the uses of GNNs in more detail in recent papers or can watch some youtube videos for a brief introduction.
