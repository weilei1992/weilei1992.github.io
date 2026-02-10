---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I'm now a Research Assistant Professor at BNRIST, Tsinghua University. I'm a member of [Prof. Xuegong Zhang's Lab](http://xglab.tech/member/index.html). 
My research interest includes single-cell bioinformatics and AI-assisted synthetic biology.

# Working Experience
- *2022.01 - now*, Research Assistant Professor, BNRIST, Tsinghua University.
- *2019.12 - 2021.12*, Postdoc Research Fellow, Department of Automation, Tsinghua University. Supervisor: Prof. Xiaowo Wang.

# Educations
- *2013.08 - 2019.10*, Ph.D., Department of Automation, Tsinghua University. Supervisor: Prof. Michael Q. Zhang & Prof. Xiaowo Wang.
- *2009.08 - 2013.07*, B.Eng., Department of Automation, Tsinghua University.

# Selected Publications 

Full publication list at [Google Scholar](https://scholar.google.com.hk/citations?user=F1jKMakAAAAJ) <a href='https://scholar.google.com/citations?user=F1jKMakAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.

## Works I love but are still waiting for acceptance

1. [How different AI models understand cells differently](https://www.biorxiv.org/content/biorxiv/early/2026/01/30/2026.01.29.702682.full.pdf).
2. [Unified multimodal learning enables generalized cellular response prediction to diverse perturbations](https://www.biorxiv.org/content/biorxiv/early/2026/01/24/2025.11.13.688367.full.pdf).
3. [DrVD-Bench: Do Vision-Language Models Reason Like Human Doctors in Medical Image Diagnosis?](https://arxiv.org/pdf/2505.24173).
4. [Benchmarking AI scientists in omics data-driven biological research](https://arxiv.org/abs/2505.08341).
5. [GeST: Towards Building A Generative Pretrained Transformer for Learning Cellular Spatial Context](https://www.biorxiv.org/content/10.1101/2025.04.09.648072.full.pdf).
6. [CellTok: Early-Fusion Multimodal Large Language Model for Single-Cell Transcriptomics via Tokenization](https://www.biorxiv.org/content/10.1101/2025.10.22.684047.full.pdf).
7. [Querying functional and structural niches on spatial transcriptomics data](https://arxiv.org/pdf/2410.10652).
8. [Benchmarking AI Models for In Silico Gene Perturbation of Cells](https://www.biorxiv.org/content/biorxiv/early/2024/12/22/2024.12.20.629581.full.pdf).

## Selected published articles

1. Qiuchen Meng, Xinze Wu, Wenchang Chen, Yubo Zhao, Chen Li, Zheng Wei, Xiaocheng Zeng, Jiaqi Li, Xi Xi, Sijie Chen, Catherine Zhang, Shengquan Chen, Jiaqi Li, Xiaowo Wang, Rui Jiang , **Lei Wei**\*, Xuegong Zhang\*. [A generic reference defined by consensus peaks for single-cell ATAC-seq data analysis](https://www.nature.com/articles/s41467-026-69461-6). *Nature Communications*, 2026.
1. Xiaofei Zhao, **Lei Wei**\*, Zhen Xie, Xuegong Zhang\*. [NeoGuider: neoepitope prediction using advanced feature engineering](https://doi.org/10.1186/s13073-025-01592-9). *Genome Medicine*, 2026.
1. Xi Xi, Yixin Chen, Xinze Wu, Minsheng Hao, Jiaqi Li, Haiyang Bian, Qiuchen Meng, Fanhong Li, Chen Li, Chuxi Xiao, Xiaomin Dong, Renke You, Yifan Xiong, Peng Yang, Zijing Gao, Xuejian Cui, Yan Pan, Zhen Li, Wenrui Li, Zhuofeng Li, Xiaoyang Chen, Yanfei Cui, Hairong Lv, Rui Jiang, **Lei Wei**\*, Xuegong Zhang\*. [hECA v2.0: an AI-ready ensemble cell atlas of single-cell RNA and ATAC sequencing data](https://www.nature.com/articles/s41597-025-06426-2). *Scientific Data*, 2025. 
1. Chen Li, Sijie Chen, Yixin Chen, Haiyang Bian, Minsheng Hao, **Lei Wei**\*, Xuegong Zhang. [TFcomb identifies transcription factor combinations for cellular reprogramming based on single-cell multiomics data](https://genome.cshlp.org/content/35/6/1429.full). *Genome Research*, 2025.
1. Haiyang Bian, Yixin Chen, **Lei Wei**\*, Xuegong Zhang\*. [uHAF: a unified hierarchical annotation framework for cell type standardization and harmonization](https://doi.org/10.1093/bioinformatics/btaf149). *Bioinformatics*, 2025.
2. Xiaofei Zhao, **Lei Wei**\*, Xuegong Zhang. [Computational methods and data resources for predicting tumor neoantigens](https://doi.org/10.1093/bib/bbaf302). *Briefings in Bioinformatics*, 2025.
1. Haochen Li, Tianxing Ma, Zetong Zhao, Yixin Chen, Xi Xi, Xiaofei Zhao, Xiaoxiang Zhou, Yibo Gao, **Lei Wei**\*, Xuegong Zhang. [scTML: a pan-cancer single-cell landscape of multiple mutation types](https://doi.org/10.1093/nar/gkae898). *Nucleic Acids Research*, 2024.
1. Haoxiao Cai, Xiaoran Zhang, Rong Qiao, Xiaowo Wang\*, **Lei Wei**\*. [Efficient computation by molecular competition networks](https://doi.org/10.1103/PhysRevResearch.6.033208). *Physical Review Research*, 2024.
1. Haoxiang Gao, Kui Hua, Xinze Wu, **Lei Wei**\*, Sijie Chen, Qijin Yin, Rui Jiang, Xuegong Zhang\*. [Building a learnable universal coordinate system for single-cell atlas with a joint-VAE model](https://www.nature.com/articles/s42003-024-06564-0). *Communications Biology*, 2024.
1. Haiyang Bian, Yixin Chen, Xiaomin Dong, Chen Li, Minsheng Hao, Sijie Chen, Jinyi Hu, Maosong Sun, **Lei Wei**\*, Xuegong Zhang\*. [scMulan: a multitask generative pre-trained language model for single-cell analysis](https://link.springer.com/chapter/10.1007/978-1-0716-3989-4_57). RECOMB, 2024.
1. Chuxi Xiao, Yixin Chen, Qiuchen Meng, **Lei Wei**\*, Xuegong Zhang. [Benchmarking multi-omics integration algorithms across single-cell RNA and ATAC data](https://doi.org/10.1093/bib/bbae095). *Briefings in Bioinformatics*, 2024.
2. Qiuchen Meng,  **Lei Wei**\*,   Kun Ma,   Ming Shi,   Xinyi Lin,   Joshua W K Ho,   Yinqing Li\*, Xuegong Zhang. [scDecouple: decoupling cellular response from infected proportion bias in scCRISPR-seq](https://doi.org/10.1093/bib/bbae011). *Briefings in Bioinformatics*, 2024.
3. Minsheng Hao, Erpai Luo, Yixin Chen, Yanhong Wu, Chen Li, Sijie Chen, Haoxiang Gao, Haiyang Bian, Jin Gu, **Lei Wei**\*, Xuegong Zhang\*. [STEM enables mapping of single-cell and spatial transcriptomics data with transfer learning](https://www.nature.com/articles/s42003-023-05640-1). *Communications Biology*, 2024.
4. Haochen Li, Tianxing Ma, Minsheng Hao, Wenbo Guo, Jin Gu, Xuegong Zhang\*, **Lei Wei**\*. [Decoding functional cell–cell communication events by multi-view graph learning on spatial transcriptomics](https://doi.org/10.1093/bib/bbad359). *Briefings in Bioinformatics*, 2023.
5. Wei Zhang, Hanwen Xu, Rong Qiao, Bixi Zhong, Xianglin Zhang, Jin Gu, Xuegong Zhang, **Lei Wei**\*, Xiaowo Wang\*. [ARIC: accurate and robust inference of cell type proportions from bulk gene expression or DNA methylation data](https://doi.org/10.1093/bib/bbab362). *Briefings in Bioinformatics*. 2022.
6. **Lei Wei**#, Shuailin Li#, Pengcheng Zhang, Tao Hu, Michael Q. Zhang, Zhen Xie, Xiaowo Wang. [Characterizing microRNA-mediated modulation of gene expression noise and its effect on synthetic gene circuits](https://doi.org/10.1016/j.celrep.2021.109573). *Cell Reports*, 2021.
7. Tao Hu#, **Lei Wei**#, Shuailin Li, Tianrun Cheng, Xuegong Zhang, Xiaowo Wang. [Single-cell transcriptomes reveal characteristics of micrornas in gene expression noise reduction](https://doi.org/10.1016/j.gpb.2021.05.002). *Genomics, Proteomics & Bioinformatics*, 2021.
19.	Jiaqi Li#, **Lei Wei**#, Xianglin Zhang, Wei Zhang, Haochen Wang, Bixi Zhong, Zhen Xie, Hairong Lv, Xiaowo Wang, [DISMIR: Deep learning-based noninvasive cancer detection by integrating DNA sequence and methylation information of individual cell-free DNA reads](https://doi.org/10.1093/bib/bbab250). *Briefings in Bioinformatics*, 2021.
20.	Wei Zhang, **Lei Wei**\*, Jiaqi Huang, Bixi Zhong, Jiaqi Li, Hanwen Xu, Shuying He, Yu Liu, Juhong Liu, Hairong Lv, Xiaowo Wang\*, [cfDNApipe: a comprehensive quality control and analysis pipeline for cell-free DNA high-throughput sequencing data](https://doi.org/10.1093/bioinformatics/btab413). *Bioinformatics*, 2021.
21.	Xuehui Liu#, **Lei Wei**#, Qiongye Dong, Liyang Liu, Michael Q Zhang, Zhen Xie, Xiaowo Wang. [A large-scale CRISPR screen and identification of essential genes in cellular senescence bypass](https://doi.org/10.18632/aging.102034). *Aging (Albany NY)*, 2019.
26.	**Lei Wei**#, Ye Yuan#, Tao Hu, Shuailin Li, Tianrun Cheng, Jinzhi Lei, Zhen Xie, Michael Q Zhang, Xiaowo Wang, [Regulation by competition: a hidden layer of gene regulatory network](https://doi.org/10.1186/s12920-020-0686-1). *Quantitative Biology*, 2019.



  

# Talks
- *2024.01*, Anhui University, Hefei.
- *2023.12*, 10th Young Bioinformatics PI Workshop, Shanghai.
- *2023.11*, Spatial Biology Congress Asia, Singapore.
- *2022.03*, The 1st Chinese Intelligent Health and Bioinformatics Conference (IHB) \[第一届智能健康与生物信息大会], Vitual (Fuzhou).
- *2021.12*, Chinese Academic Conference on Tumor Biomarker (CCTB) 2021 \[2021年中国肿瘤标志物学术大会], Vitual (Shenyang).
- *2020.12*, Bioinformatics and Intelligent Information Processing Conference (BIIP) 2020 \[生物信息学与智能信息处理2020学术年会], Virtual (Chengdu).

# Academic Services
- Review activity
  - *BMC Bioinformatics*
  - *Cell Genomics*
  - *Cell Reports Methods*
  - *Genome Medicine*
  - *Genome Research*
  - *Journal of Medical Internet Research*
  - *Journal of Theoretical Biology*
  - *National Science Review*
  - *Nature Communications*
  - *Nature Methods* 
  - *Nature Physics*
  - *Nucleic Acids Research* 
  - *PLoS Computational Biology*
  - *Quantitative Biology*
