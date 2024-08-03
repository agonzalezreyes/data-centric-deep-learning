# Week 3 Project: Confidence learning on sentiments

```
pip install -e .
```

This project will implement confidence learning to identify elements for relabeling. Please download a dataset of precomputed embeddings [here](https://drive.google.com/file/d/12UtQMwfSgm4FpXSFZvLDNLO8VGxzCPYq/view?usp=sharing). Please `conflearn_project/data` with the unzipped file.

# Results

MODEL W/O CONFIDENCE LEARNING  : 88.21% {"loss": 0.30393412709236145, "acc": 0.8821250200271606}

MODEL WITH CONFIDENCE LEARNING : 92.41X%  {"loss": 0.1771405190229416, "acc": 0.9241874814033508}