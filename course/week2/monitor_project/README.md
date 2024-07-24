# Week 2 Project: Monitoring distribution shift

```
pip install -e .
```

This project will have learners monitor deep learning systems for distribution shift using their predictions.

### Download dataset

In your terminal, please run
```
pip install gdown
```
Then, run the following:
```
gdown --id 1hdwWYFNJiCI_zFHWTMce6TETyj20GHG9
```
This will download a 3gb file of precomputed text embeddings to a file `data.zip`. Unzip the file and replace `monitor_project/data` with the unzipped folder. 

# Accuracy Report
BASELINE ACCURACY: 
- English: 88.5%
- Spanish: 55.2%
    ```bash
    Results on English reviews: {'acc': 0.884521484375, 'loss': 0.29274338483810425}
    Results on Spanish reviews: {'acc': 0.552001953125, 'loss': 1.031832218170166}
    ```

RETRAINED ACCURACY: 
- English: 88.5%
- Spanish: 72.9%
    ```bash
    Results on English reviews: {'acc': 0.885498046875, 'loss': 0.28970128297805786}
    Results on Spanish reviews: {'acc': 0.72998046875, 'loss': 0.5444539785385132}
    ```