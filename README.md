# Topological Network Alignment using Self-Supervised Siamese Model

This repository contains the implementation of **Topological Network Alignment using a Self-Supervised Siamese Model**. The method aligns two networks based on their topology and node features using a self-supervised Siamese learning framework.

## How to Run the Code

To execute the `SST-align.py` script, several arguments must be provided, including input graph files, feature files, and various hyperparameters for the alignment process.

### Usage

```bash
python SST-align.py <graph1> <graph2> <features1> <features2> <init_map> <actual_map> <learning_rate> <each_number> <batch_size> <dimension> <topk>

