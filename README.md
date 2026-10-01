# Propedia 26 — Supplementary Material

> **Important:** Please check the latest version at https://github.com/LBS-UFMG/propedia26-sm


Propedia 26 is the 2026 release of the Propedia database, a comprehensive and curated collection of protein–peptide interaction complexes. This update significantly expands the scope of the previous versions, doubling the number of available entries and providing machine-learning-ready datasets for computational biology, structural bioinformatics, and AI-driven research.

The data report PDF with statistics on missing data is available at **data/feature_statistics**.

## Links

- **Web-tool**: https://bioinfo.dcc.ufmg.br/propedia26

- **Source-code**: https://github.com/LBS-UFMG/propedia26

- **Supplementary material**: https://github.com/LBS-UFMG/propedia26-sm


## How to use

Download this supplementary dataset or clone the repository:

```
git clone https://github.com/propedia/propedia26_sm.git
```


Load data in Python:

```
import pandas as pd

propedia = pd.read_csv('data/propedia26_v7.csv', sep=';')
```



## Citation

If you use Propedia 26 in your research, please cite:

Mariano et al. PROPEDIA 26: AN EXPANDED AND UPDATED DATABASE OF PROTEIN-PEPTIDE INTERACTIONS FOR MACHINE LEARNING APPLICATIONS. NAR. 2027.


## Licence

All Propedia 26 data are released under the CC BY 4.0 License.
You are free to use, share, and adapt the data, provided that appropriate credit is given.
