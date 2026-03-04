# REVEAL: Multimodal Vision-Language Alignment of Retinal Morphometry and Clinical Risks for Incident AD and Dementia Prediction

This is the project page for the paper:

**REVEAL: Multimodal Vision-Language Alignment of Retinal Morphometry and Clinical Risks for Incident AD and Dementia Prediction**

[Seowung Leem](https://openreview.net/profile?id=~Seowung_Leem1)<sup>1</sup>, [Lin Gu](https://openreview.net/profile?id=~Lin_Gu4)<sup>2</sup>, [Chenyu You](https://chenyuyou.me/)<sup>3,4</sup>, [Kuang Gong](https://openreview.net/profile?id=~Kuang_Gong2)<sup>1</sup>, [Ruogu Fang](https://ruogu-fang.github.io/)<sup>1*</sup>

<sup>1</sup>J. Crayton Pruitt Family Dept. of Biomedical Engineering, University of Florida
<sup>2</sup>Research Institute of Electrical Communication, Tohoku University
<sup>3</sup>Dept. of Applied Mathematics & Statistics, Stony Brook University
<sup>4</sup>Dept. of Computer Science, Stony Brook University

Published at **MIDL 2026** (Medical Imaging with Deep Learning)

[[Paper]](https://openreview.net/pdf?id=aOKAXRHXVw) [[OpenReview]](https://openreview.net/forum?id=aOKAXRHXVw)

## About

REVEAL (**RE**tinal-risk **V**ision-language **E**arly **A**lzheimer's **L**earning) aligns color fundus photographs with individualized disease-specific risk profiles for incident AD and dementia prediction -- on average **8 years before diagnosis** (range: 1-11 years). We propose a group-aware contrastive learning (GACL) strategy that clusters patients with similar retinal morphometry and risk factors as positive pairs, strengthening multimodal alignment.

## Local Development

This is a static website with no build step. To preview locally:

```bash
python3 -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000) in your browser.

## Citation

```bibtex
@inproceedings{leem2026reveal,
  title={REVEAL: Multimodal Vision--Language Alignment of Retinal Morphometry and Clinical Risks for Incident AD and Dementia Prediction},
  author={Leem, Seowung and Gu, Lin and You, Chenyu and Gong, Kuang and Fang, Ruogu},
  booktitle={Medical Imaging with Deep Learning},
  year={2026}
}
```

## Acknowledgments

This research has been conducted using data from UK Biobank (application ID 48388). This material is based upon work supported by the National Science Foundation under Grant No. NSF 2123809.

## Website License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />
This website is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>. The template is borrowed from [Nerfies](https://github.com/nerfies/nerfies.github.io).
