# Week 3 Project: Active learning on fashion classifier

```
pip install -e .
```

This project will investigate various strategies to identify elements for relabeling.

# README
python scripts/test.py run {'acc': 0.3021000027656555, 'loss': 7.151782989501953}
python scripts/test.py run --test_type offline {'acc': 0.8526358008384705, 'loss': 0.4197469651699066}

MODEL (DEFAULT).    : XX.X% {'acc': 0.3021000027656555, 'loss': 7.151782989501953}
MODEL (RANDOM)      : XX.X% {'acc': 0.33580002188682556, 'loss': 1.8263455629348755}
MODEL (UNCERTAINTY) : XX.X% {'acc': 0.3557000756263733, 'loss': 3.1805648803710938}
MODEL (MARGIN)      : XX.X%
MODEL (ENTROPY)     : XX.X%
MODEL (AUGMENT)     : XX.X%
