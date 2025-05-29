Link Prediction on Knowledge Graphs using PyKEEN and PyTorch Geometric

This project explores link prediction in knowledge graphs using two powerful graph learning libraries:

  PyKEEN: for training knowledge graph embedding models like TransE and DistMult.
  PyTorch Geometric (PyG): for implementing graph neural networks (GNNs) such as GCN.
  We simulate missing links by removing triples from the dataset and evaluate model performance predicting these missing connections.

Project Highlights:

  Data Splitting: Train/validation/test sets created by removing links from the original triples dataset.
  KGE Models: Trained entity embeddings using TransE and DistMult with PyKEEN.
  Similarity-Based Link Prediction: Cosine similarity was used on embeddings to predict links.
  GNN Models: Trained a Graph Convolutional Network (GCN) using PyTorch Geometric.
  Comparative Evaluation: Compared the performance of embedding-based models vs. GNNs using metrics like MRR and Hits@K.

Future Work:

  Try more advanced GNNs like GAT, RGCN, or HGT
  Scale to large-scale KGs (e.g., Freebase, DBpedia)
  Incorporate temporal or multimodal data for richer link prediction
  Evaluate more KGE models (e.g., ComplEx, ConvE)
