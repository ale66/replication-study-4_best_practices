## replication-study-4_best_practices

A Python replication study of Chan et al., 2021, Computational Communication Research, 3(1), DOI: [10.5117/CCR2021.1.001.CHAN](https://doi.org/10.5117/CCR2021.1.001.CHAN).

The auxiliary materials were found in [github.com/chainsawriot/ots/](https://github.com/chainsawriot/ots/).

To get started, a sample dataset consisting of about 1k articles from the UK press is available.
Get the articles from HuggingFace via this template code.

```python
import pandas as pd

DATA = 'hf://datasets/theoracle/guardian_article_prov/guardian_autotrain.csv'

mydf = pd.read_csv(DATA)

print(mydf.columns)          # see available columns

print(mydf["text"].iloc[0]) # text of the first article
```


This is a template to feed a GitHub Classroom assignment.
