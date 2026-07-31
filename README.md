<h1 align="center">
  <img src="assets/icon2.png" height="60" align="center" alt="" />&nbsp;ShadowDancer
</h1>

<p align="center"><b>Teaching Video World Models Any Action from a Video and Its Shadow</b></p>

<div align="center">

[![Website](https://img.shields.io/badge/Website-ShadowDancer-blue)](https://shadowdancer-1.github.io/)
[![arXiv](https://img.shields.io/badge/arXiv-2607.28362-red)](https://arxiv.org/abs/2607.28362)
<!-- [![HuggingFace](https://img.shields.io/badge/🤗%20Weights-ShadowDancer-yellow)](TODO_hf_url) -->

</div>

> #### [ShadowDancer: Teaching Video World Models Any Action by Learning Unified Dynamics Representations from a Video and Its Shadow](https://arxiv.org/abs/2607.28362)
>
> ##### [Jin Cao](https://jin-cao-tma.github.io/), Zian Meng, [Kaipeng Zhang](https://kpzhang93.github.io/)&dagger;  (&dagger; corresponding author)

<p align="center">
  <img src="assets/teaser.png" width="100%" alt="ShadowDancer teaser" />
</p>

ShadowDancer gives interactive video world models an **any-action, frame-level control** interface: point at a demonstration clip and the model re-enacts that action in a new world. The key idea is to observe the same dynamics **twice** — a *shadow pair* is two frame-synchronized renders of one dynamics under independently resampled appearance — and learn actions by *cross-shadow prediction*, so that whatever the pairing resamples is discarded by construction and whatever it preserves becomes the controllable action. Any demonstrated clip thereby becomes a reusable action asset, replayed without labels, motion estimators, or fine-tuning.

## Citation

```bibtex
@misc{cao2026shadow,
  title={ShadowDancer: Teaching Video World Models Any Action by Learning Unified Dynamics Representations from a Video and Its Shadow},
  author={Jin Cao and Zian Meng and Kaipeng Zhang},
  year={2026},
  eprint={2607.28362},
  archivePrefix={arXiv},
  primaryClass={cs.CV},
  url={https://arxiv.org/abs/2607.28362},
}
```
