# Week 3 Project: Active learning on fashion classifier

```
pip install -e .
```

This project will investigate various strategies to identify elements for relabeling.

# README

### Production Dataset Results 

MODEL (DEFAULT).    : 30.21% {'acc': 0.3021000027656555, 'loss': 7.151782989501953}
MODEL (RANDOM)      : 33.58% {'acc': 0.33580002188682556, 'loss': 1.8263455629348755}
MODEL (UNCERTAINTY) : 35.57% {'acc': 0.3557000756263733, 'loss': 3.1805648803710938}
MODEL (MARGIN)      : 44.87% {'acc': 0.44870004057884216, 'loss': 1.7129864692687988}
MODEL (ENTROPY)     : 40.51% {'acc': 0.405100017786026, 'loss': 3.4584286212921143}
MODEL (AUGMENT)     : 43.39% {'acc': 0.43390002846717834, 'loss': 2.996901273727417}
