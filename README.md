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


Parameter Data:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rishabdchem/qumode_est_paper/blob/main/h2mol_params.ipynb) | Parameter Data for the H2 Molecule


Visualization Codes:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rishabdchem/qumode_est_paper/blob/main/h2mol_plots.ipynb) | Results Plots in the Manuscript for the H2 Molecule



## Citation <a name="citation"></a>

Please cite the preprint of our work when using this code until the journal version becomes available.

[![Static Badge](https://img.shields.io/badge/2404.10222-B31B1B?logo=arxiv&logoColor=B31B1B&label=quant-ph)](https://arxiv.org/abs/2404.10222)

```
@misc{dutta2024simulatingelectronicstructurebosonic,
      title={Simulating electronic structure on bosonic quantum computers}, 
      author={Rishab Dutta and Nam P. Vu and Chuzhi Xu and Ningyi Lyu and Alexander V. Soudackov and Xiaohan Dan and Haote Li and Chen Wang and Victor S. Batista},
      year={2024},
      eprint={2404.10222},
      archivePrefix={arXiv},
      primaryClass={quant-ph},
      url={https://arxiv.org/abs/2404.10222}, 
}
```


## Contact <a name="contact"></a>

For questions, comments, or support, please contact:

Rishab Dutta (rishab.dutta@yale.edu)



## License <a name="license"></a>

This source code is licensed under the MIT license found in the `LICENSE` file
in the root directory of this source tree.

