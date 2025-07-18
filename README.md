<!-- # rLLM (**[Documentation](https://relationllm.readthedocs.io/en/latest/)**|**[Paper](https://arxiv.org/abs/2407.20157)**) -->

<p align="center"><img src="docs/source/_static/logo.png" alt="rLLM logo" width="400px" /></p>
<p align="center">
|  <a href="https://relationllm.readthedocs.io/en/latest/"><b>Documentation</b></a>  
|  <a href="https://rllm-project.github.io/"><b>Blog</b></a>  
|  <a href="https://arxiv.org/abs/2407.20157"><b>Paper</b></a>  
|  <a href="https://zhengwang100.github.io/pdf/rllm_introduction240811.pdf"><b>Slide</b></a>  |
</p>

----

*Latest News* 🔥  
- [2025.04] Released the course videos "Special Topic on Table Learning (Spring 2025, SJTU)". Check out the [course page](https://zhengwang100.github.io/course/table-learning-2025/) or visit our [YouTube channel](https://www.youtube.com/watch?v=aebkqnSghTw&list=PLtbYCaVzygjLZrYCuoz6nTJdUzMzIUohh).
- [2025.01] We’ve updated to **rLLM v0.1.1** for improved uniformity between Transform and Convolution operations. See our [blog](https://rllm-project.github.io/2025-01-10-rLLM-v0.1.1-Achieving-Greater-Uniformity-Between-Transform-and-Convolution/).
- [2024.12] rLLM was featured in the famous technical magzine **MIT Technology Review**. Read the report [here (Chinese)](https://www.mittrchina.com/news/detail/14162) or [here (English)](https://www-mittrchina-com.translate.goog/news/detail/14162?_x_tr_sl=auto&_x_tr_tl=en&_x_tr_hl=en&_x_tr_pto=wapp).  
- [2024.11] This work has been approved by **Snowflake** (AI Data Cloud leader, NYSE: $57.46B) as a nice tool for RTL-type tasks. See paper: [arXiv:2411.11829](https://arxiv.org/abs/2411.11829).
- [2024.10] We have recently added the state-of-the-art GNN method **OGC** [[TNNLS 2024](https://arxiv.org/abs/2309.13599)], the TNN method **ExcelFormer** [[KDD 2024](https://arxiv.org/abs/2301.02819)] and **Trompt** [[ICML 2023](https://arxiv.org/abs/2305.18446)].  
- [2024.08] **rLLM is supported by the CCF-Huawei Populus Grove Fund (CCF-华为胡杨林基金数据库专项).** This project focuses on *Tabular Data Governance for AI Tasks*. Watch a short introduction video on Huawei's official account: [📺 Bilibili](https://www.bilibili.com/video/BV1qz421i7Yz). 
- [2024.07] We have released rLLM (v0.1), and the detailed documentation is now available: [rLLM Documentation](https://relationllm.readthedocs.io/en/latest/).
  
---
## About

**rLLM** (relationLLM) is an easy-to-use Pytorch library for Relational Table Learning (RTL) with LLMs, by performing two key functions:
1. Breaks down state-of-the-art GNNs, LLMs, and TNNs as standardized modules.
2. Facilitates novel model building in a "combine, align, and co-train" way.  


<p align="center">
  <img width="400" height="310" src="https://zhengwang100.github.io/img/rllm/rllm_overview.png">
</p>

### How to Try

Let's run an RTL-type method [BRIDGE](./examples/bridge) as an example:

```bash
# cd ./examples
# set parameters if necessary

python bridge/bridge_tml1m.py
python bridge/bridge_tlf2k.py
python bridge/bridge_tacm12k.py
```

### Highlight Features

- **LLM-friendly:** Modular interface designed for LLM-oriented applications, integrating smoothly with LangChain and Hugging Face transformers.
- **One-Fit-All Potential:**  Processes various graphs (like Social/Citation/E-commerce Networks) by treating them as multiple tables linked by foreigner keys.
- **Novel Datasets:**  Introduces three new relational table datasets useful for RTL model design. Includes the standard classification task, with examples.
- **Community Support:**  Maintained by students and teachers from Shanghai Jiao Tong University and Tsinghua University. Supports the SJTU undergraduate course "Content Understanding (NIS4301)" and the graduate course "Social Network Analysis (NIS8023)".

## Implemented Methods

rLLM includes over 15 state-of-the-art GNN and TNN models, ideal for both standalone use and building RTL-type methods. Highlighted models include:  

- **OGC**: *From Cluster Assumption to Graph Convolution: Graph-based Semi-Supervised Learning Revisited* [[TNNLS 2024](https://arxiv.org/abs/2309.13599)] [[Example](https://github.com/rllm-team/rllm/blob/main/examples/ogc.py)]  
- **ExcelFormer**: *ExcelFormer: A Neural Network Surpassing GBDTs on Tabular Data* [[KDD 2024](https://arxiv.org/abs/2301.02819)] [[Example](https://github.com/rllm-team/rllm/blob/main/examples/excelformer.py)]  
- **TAPE**: *Harnessing Explanations: LLM-to-LM Interpreter for Enhanced Text-Attributed Graph Representation Learning* [[ICLR 2024](https://arxiv.org/abs/2305.19523)] [[Example](https://github.com/rllm-team/rllm/tree/main/examples/tape)]  
- **Label-Free-GNN**: *Label-free Node Classification on Graphs with Large Language Models* [[ICLR 2024](https://arxiv.org/abs/2310.04668)] [[Example](https://github.com/rllm-team/rllm/blob/main/examples/ogc.py)]  
- **Trompt**: *Towards a Better Deep Neural Network for Tabular Data*  [[ICML 2023](https://arxiv.org/abs/2305.18446)] [[Example](https://github.com/rllm-team/rllm/blob/main/examples/trompt.py)]  
- ...  

## Contributing

Contribution is always welcomed. All contributions must be made through pull requests and are subject to review by the committers. For more details, please refer to our [[contribution guide](https://drive.google.com/file/d/1EFchbdcu54ZSuV-DR7y4fJh51yKM6Vo5/view?usp=drive_link])].

### Todo List

- [x] Code structure optimization
- [x] Support for more TNNs
- [ ] Large-scale RTL training
- [ ] LLM prompt optimization

## Sponsor

<table>
  <tr>
    <td align="center">
      <a href="https://www.nsfc.gov.cn/english/site_1/">
        <img src="https://www.nsfc.gov.cn/english/site_1/images/logo.jpg" width="160" /><br/>
        National Natural Science Foundation of China
      </a>
    </td>
    <td align="center">
      <a href="https://stcsm.sh.gov.cn/">
        <img src="https://stcsm.sh.gov.cn/images/logo_zz.png" width="130" /><br/>
        Natural Science Foundation of Shanghai
      </a>
    </td>
    <td align="center">
      <a href="https://tc.ccf.org.cn/">
        <img src="https://tc.ccf.org.cn/upload/resources/image/2021/06/09/159361.png" width="90" /><br/>
        CCF-Huawei Populus Grove Fund
      </a>
    </td>
  </tr>
</table>

*For more cooperation, feel free to contact [Zheng Wang](https://zhengwang100.github.io/).*



## Citation
```
@article{rllm2024,
      title={rLLM: Relational Table Learning with LLMs}, 
      author={Weichen Li and Xiaotong Huang and Jianwu Zheng and Zheng Wang and Chaokun Wang and Li Pan and Jianhua Li},
      year={2024},
      eprint={2407.20157},
      archivePrefix={arXiv},
      primaryClass={cs.AI},
      url={https://arxiv.org/abs/2407.20157}, 
}
```
