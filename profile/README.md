<h1 align="center">Video-Reason</h1>

<p align="center">
  <b>Towards Reasoning in Visual Generation Models!</b><br>
  We build open-source data, models, tools, and benchmarks for native visual reasoning.
</p>

<p align="center">
  <a href="https://huggingface.co/papers/month/2026-02">
    <img src="https://raw.githubusercontent.com/VBVR-DataFactory/.github/main/assets/paper_of_month.svg" width="420"/>
  </a>
</p>

---

## Research Programs

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://video-reason.com/?v=pro">VBVR-Pro</a></h3>
      <p align="center"><strong>A Scalable and Verifiable Suite for Native Visual Reasoning</strong></p>
      <p>
        VBVR-Pro turns visual reasoning into a scalable, verifiable training and evaluation loop: 300 procedural tasks, aligned image/interleaved text-image/video solutions, and verifiable task-specific evaluation.
      </p>
      <ul>
        <li><strong>300</strong> procedurally generated training tasks</li>
        <li>Task-grounded, verifiable reward scorers</li>
        <li>Image, interleaved text-image, and video model families</li>
      </ul>
      <p align="center">
        <a href="https://huggingface.co/papers/2608.26105">Paper</a> ·
        <a href="https://github.com/Video-Reason/VBVR-Pro">Training and inference code for all modalities</a> ·
        <a href="https://github.com/Video-Reason/VBVR-Pro-Bench">Benchmark evaluation code</a> ·
        <a href="https://huggingface.co/Video-Reason/models?search=VBVR-Pro">Strong baselines trained on VBVR-Pro-Dataset</a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://video-reason.com/">VBVR</a></h3>
      <p align="center"><strong>A Very Big Video Reasoning Suite</strong></p>
      <p>
        Our first investigation on whether video generation models can solve visual reasoning tasks through generation.
      </p>
      <ul>
        <li><strong>Study of data scaling behaviour</li>
        <li>Comprehensive evaluation on proprietary and open-source video models</li>
      </ul>
      <p align="center">
        <a href="https://arxiv.org/abs/2602.20159">Paper</a> ·
        <a href="https://github.com/Video-Reason/VBVR-Wan2.2">Training and inference code for VBVR-Wan2.2 and VBVR-LTX2.3 </a> ·
        <a href="https://github.com/Video-Reason/VBVR-EvalKit">Benchmark evaluation code</a>
      </p>
    </td>
  </tr>
</table>

**Video-Reason** investigates whether generative models can perform genuine reasoning—such as solving chess puzzles, navigating mazes, completing Sudoku, performing mental rotation, and solving Raven's matrices—directly through visual generation. VBVR provides scalable data generation and deterministic evaluation; VBVR-Pro closes the loop with supervised training, reinforcement learning, verifiable rewards, and controlled comparisons across image, interleaved-image, and video generation. All tools are open-source under Apache 2.0.

For documentation, benchmarks, generators, and project updates, visit [Video-Reason.com](https://video-reason.com/).

---

## Core Repositories

### [VBVR-Pro](https://github.com/Video-Reason/VBVR-Pro) — Training and Inference Code

Unified training and inference for the VBVR-Pro image, interleaved-image, and video model families.

### [VBVR-Pro-Bench](https://github.com/Video-Reason/VBVR-Pro-Bench) — Verifiable Benchmark

Task-grounded evaluation and verifiable reward scorers for native visual reasoning.

### [Awesome-Video-Reasoning](https://github.com/Video-Reason/Awesome-Video-Reasoning) — Paper Collection

A curated list of research papers on **reasoning with video generation models**

---

## Links

- **Website**: [Video-Reason.com](https://video-reason.com/)
- **VBVR Paper**: [A Very Big Video Reasoning Suite](https://arxiv.org/abs/2602.20159)
- **VBVR-Pro Paper**: [A Scalable and Verifiable Suite for Native Visual Reasoning](https://arxiv.org/abs/2608.26105)
- **VBVR-Pro Models**: [Browse the model family](https://huggingface.co/Video-Reason/models?search=VBVR-Pro)
- **HuggingFace**: [Video-Reason](https://huggingface.co/Video-Reason)
- **Contact**: [hokinxqdeng@gmail.com](mailto:hokinxqdeng@gmail.com)

---

## Citation

If you use our work in your research, please cite the corresponding paper.

### VBVR

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

### VBVR-Pro

```bibtex
@misc{xu2026vbvrproscalableverifiablesuite,
  title         = {VBVR-Pro: A Scalable and Verifiable Suite for Native Visual Reasoning},
  author        = {Junxiang Xu and Ruisi Wang and Fanyi Pu and Maijunxian Wang and Ran Ji and Tongxi Zhou and Chenyang Gu and Jing Zuo and Hongcan Xiao and Yimeng Geng and Wanqi Yin and Wei Chen and Oscar Qian and Zhengan Yan and Ziqi Huang and Haiwen Diao and Liang Pan and Bo Li and Xiangyu Fan and Dezhi Luo and Fengyuan Yu and Zehong Zhao and Qingying Gao and Tinghui Zhu and Yilan Zhang and Jingqi Tong and Pinyuan Feng and Zhengze Jiang and Letian Wang and Ziyu Guo and Renrui Zhang and Jieneng Chen and Sonia Joseph and Constantin Venhoff and Saman Motamed and Mengyue Yang and Chandra Sripada and Alan Yuille and Philip Torr and Lvmin Zhang and Vikash Kumar and Daniel Khashabi and Nikolaus Kriegeskorte and Rapha{\"e}l Milli{\`e}re and Vincent C. M{\"u}ller and Anyi Rao and Quan Wang and Ziwei Liu and Dahua Lin and Lei Yang and Hokin Deng and Zhongang Cai},
  year          = {2026},
  eprint        = {2608.26105},
  archivePrefix = {arXiv},
  primaryClass  = {cs.CV},
  url           = {https://arxiv.org/abs/2608.26105}
}
```
