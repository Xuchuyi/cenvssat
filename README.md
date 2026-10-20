Figure scripts and data for the paper “The Connection between Halo Assembly History and the Stellar Distribution I: The Central Stellar Mass - Richness Plane” by Shuo Xu, Song Huang, Alexie Leauthaud, Benedikt Diemer, Katya Leidig, Conghao Zhou, Carlo Cannarozzo, submitted to ApJ.
arxiv: https://arxiv.org/abs/2609.14488

## Contents

- `FigureNotebooks/`: Jupyter notebooks that produce each figure in the paper. Each notebook is named after the figure it generates:
  - `Fig1b.ipynb`, `Fig1acd.ipynb` — Figure 1
  - `Fig2.ipynb` to `Fig10.ipynb` — Figures 2 to 10
  - `FigA1.ipynb`, `FigA2.ipynb` — Appendix A figures
  - `FigB.ipynb`, `FigB1.ipynb` — Appendix B figures
  - `FigC1.ipynb` — Appendix C figure

  Each notebook can be run top to bottom to reproduce the corresponding figure.

- `Data/`: data products used by the notebooks. These are derived from the IllustrisTNG simulations (TNG100-1 and TNG300-1, snapshot 72) and the SDSS DR8 redMapper cluster catalog.

## Requirements:

Python 3 with the following packages: numpy, matplotlib, scipy, astropy, pandas, photutils, palettable, scikit-learn, matplotlib-venn, pingouin

## License

The code in this repository is released under the MIT License (see `LICENSE`). The data products are derived from IllustrisTNG and SDSS and remain subject to their respective data policies.
