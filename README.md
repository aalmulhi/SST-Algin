# Topological Network Alignment using Self-Supervised Siamese Model

This repository contains the implementation of **Topological Network Alignment using a Self-Supervised Siamese Model**. The method aligns two networks based on their topology and node features using a self-supervised Siamese learning framework.

## How to Run the Code

To run the `Graphlet_imap.py` and `SST-align.py` scripts, you need to provide several arguments, including graph files, feature files, and an actual map for the evaluation.

### 1. Run `Graphlet_imap.py`

#### Usage

```bash
python Graphlet_imap.py data/graph1.txt data/graph2.txt data/features1.csv data/features2.csv mappings/actual_map.txt 100
python SST-align.py data/graph1.txt data/graph2.txt data/features1.csv data/features2.csv mappings/init_map.txt mappings/actual_map.txt 0.001 100 64 128 5
