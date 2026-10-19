# MLIP-Phase-Transition-NNMO

[![CHGNet](https://img.shields.io/badge/CHGNet-Fine--Tuned-blue.svg)](https://chgnet.lbl.gov/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**Accelerating structural evolution modeling of Mg- and S-doped P2-Na2/3Ni1/3Mn2/3O2 cathodes via combined DFT and machine-learning interatomic potentials**

This repository contains the fine-tuned Machine-Learning Interatomic Potential (MLIP) based on the **CHGNet** architecture, along with the complete Density Functional Theory (DFT) datasets (training, validation, and testing sets) in extended XYZ format. This model is specifically developed to investigate the P2–O2 phase transition and structural stability of pristine and doped P2-type Na2/3Ni1/3Mn2/3O2 (NMO) cathodes for sodium-ion batteries (SIBs).

## 📖 Overview

The irreversible P2–O2 phase transition during deep desodiation causes severe structural degradation in Na2/3Ni1/3Mn2/3O2 cathodes. By combining DFT calculations with a fine-tuned CHGNet MLIP, we established a robust computational workflow to overcome the severe limitations of system size and simulation time in conventional DFT evaluations. 

This model successfully enables large-scale supercell simulations and molecular dynamics (MD) to capture long-range interlayer interactions and local structural distortions. Our results demonstrate that incorporating redox-inactive Mg2+ significantly improves structural stability by postponing the phase transition to $x \approx 0.17$, while bulk S-doping induces structural degradation at deep desodiation levels.

## 📝 Citation

This work is currently under revision. If you use this model or dataset in your research before publication, please cite it as an unpublished manuscript:

```bibtex
@article{YenWu2026,
  title={Accelerating structural evolution modeling of Mg- and S-doped P2-Na2/3Ni1/3Mn2/3O2 cathodes via combined DFT and machine-learning interatomic potentials},
  author={Yen, Shih-Ying and Wu, Liang-Ting and Kaghazchi, Payam and Jiang, Jyh-Chiang},
  journal={Under revision},
  year={2026}
}
