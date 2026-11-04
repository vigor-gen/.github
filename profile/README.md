# VIGOR

**VIGOR: Zero-Shot Visual Generalization via Latent-Space Consistency in Model-Based Reinforcement Learning**<br>
*NeurIPS 2026*

[**Project Page**](https://vigor-gen.github.io) | [**NeurIPS 2026**](https://neurips.cc/virtual/2026/poster/153294) | Paper (coming soon) | [**arXiv**](https://arxiv.org/abs/2610.02801)

This organization hosts the project page and the official source code for **VIGOR** (**VI**sual **G**eneralization via latent-space c**O**nsistency in model-based **R**L). VIGOR is a plug-in framework that lets a model-based RL agent trained only on clean pixels generalize **zero-shot** to visual distractions it has never seen, such as background, color, lighting, and camera-position changes. It needs no test-time data and no adaptation.

## Authors

| Author | Affiliation |
| :--- | :--- |
| [Mingyu Park](https://mngupark.github.io)\* | ETRI, KAIST |
| [Samyeul Noh](https://urobot.kaist.ac.kr/url_teams/mr-samyeul-noh/)\* | ETRI, KAIST |
| [Hyun Myung](https://urobot.kaist.ac.kr/url_teams/prof-hyunmyung/)† | KAIST |
| [Donghwan Lee](https://sites.google.com/site/donghwanleehome/pi)† | KAIST |

\* Equal contribution &nbsp;&nbsp; † Equal advising

**Institutions:** [Electronics and Telecommunications Research Institute (ETRI)](https://www.etri.re.kr) · [Korea Advanced Institute of Science and Technology (KAIST)](https://www.kaist.ac.kr)

## Repositories

| Repository | Description |
| :--- | :--- |
| [`vigor-gen.github.io`](https://github.com/vigor-gen/vigor-gen.github.io) | Source of the [project page](https://vigor-gen.github.io): overview video, method, results, rollout gallery, and supplementary results. |
| [`tdmpc2-vigor`](https://github.com/vigor-gen/tdmpc2-vigor) | **TD-MPC2+VIGOR**, the default instantiation on a decoder-free world model with MPC planning. |
| [`dreamerv3-vigor`](https://github.com/vigor-gen/dreamerv3-vigor) | **DreamerV3+VIGOR**, the instantiation on a decoder-based RSSM world model with actor-critic learning. |

## Citation

```bibtex
@article{park2026vigor,
  title={VIGOR: Zero-Shot Visual Generalization via Latent-Space Consistency in Model-Based Reinforcement Learning},
  author={Park, Mingyu and Noh, Samyeul and Myung, Hyun and Lee, Donghwan},
  journal={arXiv preprint arXiv:2610.02801},
  year={2026}
}
```
