[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Static Badge](https://img.shields.io/badge/CQDMQD-00268d?style=flat&logoColor=00268d&label=NSF&labelColor=00268d&color=00268d&link=https%3A%2F%2Fcqdmqd.yale.edu%2F)](https://cqdmqd.yale.edu/)
[![Static Badge](https://img.shields.io/badge/2404.10222-B31B1B?logo=arxiv&logoColor=B31B1B&label=quant-ph)](https://arxiv.org/abs/2404.10222)


# Simulating electronic structure on bosonic quantum computers

This repository provides the data and code necessary to reproduce the results in the manuscript "Simulating electronic structure on bosonic quantum computers".

## Table of Contents

1. [Getting Started](#start)
2. [Citation](#citation)
3. [Contact](#contact)
4. [License](#license)


## Getting Started <a name="start"></a>

To reproduce the manuscript figures and the ansatz optimization, jupyter notebooks are provided, that include all the necessary dependencies. For ease of reproducibility, these can be opened and executed via Google Colab.



Optimization Codes:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rishabdchem/qumode_est_paper/blob/main/universal_ansatz_opt.ipynb) | Universal Qubit-Qumode Ansatz Optimization

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rishabdchem/qumode_est_paper/blob/main/lcu_ecd_opt.ipynb) | Linear Combination of ECD-Rotation Optimization


VQE Codes:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rishabdchem/qumode_est_paper/blob/main/ecd_vqe_h2mol.ipynb) | ECD-VQE Code for the H2 Molecule

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rishabdchem/qumode_est_paper/blob/main/snap_vqe_h2mol.ipynb) | SNAP-VQE Code for the H2 Molecule

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rishabdchem/qumode_est_paper/blob/main/h4mol_snap_vqe.ipynb) | SNAP-VQE Code for the H4 Molecule

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rishabdchem/qumode_est_paper/blob/main/UCCSD_VQE_H4.ipynb) | UCCSD-VQE Code for the H4 Molecule

Parameter Data:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rishabdchem/qumode_est_paper/blob/main/h2mol_params.ipynb) | Parameter Data for the H2 Molecule

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rishabdchem/qumode_est_paper/blob/main/h4mol_params.ipynb) | Parameter Data for the H4 Molecule


Visualization Codes:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rishabdchem/qumode_est_paper/blob/main/h2mol_plots.ipynb) | Results Plots in the Manuscript for the H2 Molecule



## Citation <a name="citation"></a>

```
@article{dutta2025simulating,
  title={Simulating electronic structure on bosonic quantum computers},
  author={Dutta, Rishab and Vu, Nam P and Xu, Chuzhi and Cabral, Delmar GA and Lyu, Ningyi and Soudackov, Alexander V and Dan, Xiaohan and Li, Haote and Wang, Chen and Batista, Victor S},
  journal={Journal of Chemical Theory and Computation},
  volume={21},
  number={5},
  pages={2281--2300},
  year={2025},
  publisher={ACS Publications}
}
```

## Contact <a name="contact"></a>

For questions, comments, or support, please contact:

Rishab Dutta (rishab.dutta@pnnl.gov)


## License <a name="license"></a>

This source code is licensed under the MIT license found in the `LICENSE` file
in the root directory of this source tree.

