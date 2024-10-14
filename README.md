# Topological Network Alignment using Self-Supervised Siamese Model

This repository contains the implementation of **Topological Network Alignment using a Self-Supervised Siamese Model**. The method aligns two networks based on their topology and node features using a self-supervised Siamese learning framework.

## How to Run the Code

### 1. Run `Graphlet_imap.py`
### 1. Run `SST-align.py`
To run the `Graphlet_imap.py` and `SST-align.py` scripts, you need to provide several arguments, including graph files, feature files, and an actual map for the evaluation.

#### Usage

```bash
python Graphlet_imap.py <graph1> <graph2> <features1> <features2> <actual_map> <p>

```bash
python SST-align.py <graph1> <graph2> <features1> <features2> <init_map> <actual_map> <learning_rate> <each_number> <batch_size> <dimension> <topk>

