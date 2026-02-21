<h1 align="center">Video-Reason</h1>

<p align="center">
  <b>Towards Reasoning in Video Generation Models?</b><br>
  We build open-source tools to generate, evaluate, and understand reasoning in video models.
</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/badge/license-Apache%202.0-green" />
  <img alt="Generators" src="https://img.shields.io/badge/generators-300+-orange" />
  <img alt="Evaluators" src="https://img.shields.io/badge/evaluators-100+-blue" />
</p>

---

**Very Big Video Reasoning (VBVR)** is a research initiative investigating whether video generation models can perform genuine reasoning — solving chess puzzles, navigating mazes, completing Sudoku, mental rotation, and Raven's matrices — purely through visual generation. [VBVR-DataFactory](https://github.com/Video-Reason/VBVR-DataFactory) implements **data generation** at scale, and [VBVR-EvalKit](https://github.com/Video-Reason/VBVR-EvalKit) implements **unified inference** across 37 commercial and open-source video models, and **deterministic evaluation** with 100+ rule-based benchmarks. All tools are open-source under Apache 2.0. 

For all generators, checkout https://github.com/VBVR-DataFactory

For documentation, benchmarks, and project updates, see:
https://video-reason.com/

---

## Repositories

### [VBVR-EvalKit](https://github.com/Video-Reason/VBVR-EvalKit) — Evaluation Toolkit

Unified inference and evaluation across **37 video generation models**.

### [VBVR-DataFactory](https://github.com/Video-Reason/VBVR-DataFactory) — Scalable Data Generation

Distributed data generation system built on **AWS Lambda** with **300+ generators**.

### [Awesome-Video-Reasoning](https://github.com/Video-Reason/Awesome-Video-Reasoning) — Paper Collection

A curated list of research papers on **reasoning with video generation models**

---

## Community

- **Website**: [video-reason.com](https://video-reason.com/)
- **Slack**: [Join our workspace](https://join.slack.com/t/vm-dataset/shared_invite/zt-3mdb2lkye-lm7ZC4OGxxRRMEi1M65hKQ)
- **HuggingFace**: [Video-Reason](https://huggingface.co/Video-Reason)
- **Contact**: [hokinxqdeng@gmail.com](mailto:hokinxqdeng@gmail.com)

---

## Citation

If you use VBVR in your research, please cite:

```bibtex
@article{vbvr2026,
  title   = {A Very Big Video Reasoning Suite},
  author  = {Wang, Maijunxian and Wang, Ruisi and Lin, Juyi and Ji, Ran and
             Wiedemer, Thaddäus and Gao, Qingying and Luo, Dezhi and
             Qian, Yaoyao and Huang, Lianyu and Hong, Zelong and Ge, Jiahui and
             Ma, Qianli and He, Hang and Zhou, Yifan and Guo, Lingzi and
             Mei, Lantao and Li, Jiachen and Xing, Hanwen and Zhao, Tianqi and
             Yu, Fengyuan and Xiao, Weihang and Jiao, Yizheng and
             Hou, Jianheng and Zhang, Danyang and Xu, Pengcheng and
             Zhong, Boyang and Zhao, Zehong and Fang, Gaoyun and Kitaoka, John and
             Xu, Yile and Xu, Hua and Blacutt, Kenton and Nguyen, Tin and
             Song, Siyuan and Sun, Haoran and Wen, Shaoyue and He, Linyang and
             Wang, Runming and Wang, Yanzhi and Yang, Mengyue and Ma, Ziqiao and
             Millière, Raphaël and Shi, Freda and Vasconcelos, Nuno and
             Khashabi, Daniel and Yuille, Alan and Du, Yilun and Liu, Ziming and
             Lin, Dahua and Liu, Ziwei and Kumar, Vikash and Li, Yijiang and
             Yang, Lei and Cai, Zhongang and Deng, Hokin},
  year    = {2026}
}
```

<p align="center">
  <img src="https://raw.githubusercontent.com/Video-Reason/VBVR-EvalKit/main/assets/logo.png" alt="VBVR Logo" width="180">
</p>
