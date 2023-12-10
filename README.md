# ABI
Machine Learning Modeling for Task #2 of Adaptive Business Intelligence Course on MAPi.

---
## Installation Dependencies

```bash
conda create -n abi python=3.10
conda activate abi
pip install -r requirements.txt
```

---
## Steps of the project

```mermaid
graph LR
    A[Data] --> B[Preprocessing]
    B --> C[Modeling]
    C --> D[Evaluation]
    D --> E[Results]
```