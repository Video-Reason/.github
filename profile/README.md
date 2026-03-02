<h1 align="center">Video-Reason</h1>

<p align="center">
  <b>Towards Reasoning in Video Generation Models!</b><br>
  We build open-source tools to generate, evaluate, and understand reasoning in video models.
</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/badge/license-Apache%202.0-green" />
  <img alt="Generators" src="https://img.shields.io/badge/generators-300+-orange" />
  <img alt="Evaluators" src="https://img.shields.io/badge/evaluators-100+-blue" />
</p>

<p align="center">
  <a href="https://huggingface.co/papers/month/2026-02">
    <img src="https://raw.githubusercontent.com/VBVR-DataFactory/.github/main/assets/paper_of_month.svg" width="420"/>
  </a>
</p>

---

**Very Big Video Reasoning (VBVR)** is a research initiative investigating whether video generation models can perform genuine reasoning — i.e. solving chess puzzles, navigating mazes, completing Sudoku, mental rotation, and Raven's matrices — purely through visual generation. [VBVR-DataFactory](https://github.com/Video-Reason/VBVR-DataFactory) is a **highly efficient, serverless data-generation engine** powered by **AWS Lambda** — capable of producing millions of puzzle instances in minutes with 300+ generators, near-linear horizontal scaling, and minimal infrastructure cost. [VBVR-EvalKit](https://github.com/Video-Reason/VBVR-EvalKit) implements **unified inference** across 37 commercial and open-source video models, and **deterministic evaluation** with 100+ rule-based benchmarks. All tools are open-source under Apache 2.0.

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

## Links

- **Website**: [Video-Reason.com](https://video-reason.com/)
- **Paper**: [A Very Big Video Reasoning Suite](https://arxiv.org/abs/2602.20159v1)
- **Slack**: [Join our workspace](https://join.slack.com/t/video-reason/shared_invite/zt-3qqf23icm-UC29fatWWYsIuzRNBR1lgg)
- **HuggingFace**: [Video-Reason](https://huggingface.co/Video-Reason)
- **Contact**: [hokinxqdeng@gmail.com](mailto:hokinxqdeng@gmail.com)

---

## Citation

If you use VBVR in your research, please cite:

```bibtex
@article{vbvr2026,
  title   = {A Very Big Video Reasoning Suite},
  author  = {Wang, Maijunxian and Wang, Ruisi and Lin, Juyi and Ji, Ran and
             Wiedemer, Thadd{\"a}us and Gao, Qingying and Luo, Dezhi and
             Qian, Yaoyao and Huang, Lianyu and Hong, Zelong and Ge, Jiahui and
             Ma, Qianli and He, Hang and Zhou, Yifan and Guo, Lingzi and
             Mei, Lantao and Li, Jiachen and Xing, Hanwen and Zhao, Tianqi and
             Yu, Fengyuan and Xiao, Weihang and Jiao, Yizheng and
             Hou, Jianheng and Zhang, Danyang and Xu, Pengcheng and
             Zhong, Boyang and Zhao, Zehong and Fang, Gaoyun and Kitaoka, John and
             Xu, Yile and Xu, Hua and Blacutt, Kenton and Nguyen, Tin and
             Song, Siyuan and Sun, Haoran and Wen, Shaoyue and He, Linyang and
             Wang, Runming and Wang, Yanzhi and Yang, Mengyue and Ma, Ziqiao and
             Milli{\`e}re, Rapha{\"e}l and Shi, Freda and Vasconcelos, Nuno and
             Khashabi, Daniel and Yuille, Alan and Du, Yilun and Liu, Ziming and
             Lin, Dahua and Liu, Ziwei and Kumar, Vikash and Li, Yijiang and
             Yang, Lei and Cai, Zhongang and Deng, Hokin},
  journal = {arXiv preprint arXiv:2602.20159},
  year    = {2026},
  url     = {https://arxiv.org/abs/2602.20159}
}
```
