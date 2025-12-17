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

1. Chen Li, Sijie Chen, Yixin Chen, Haiyang Bian, Minsheng Hao, **Lei Wei**\*, Xuegong Zhang. TFcomb identifies transcription factor combinations for cellular reprogramming based on single-cell multiomics data. *Genome Research*, 2025.
1. Haiyang Bian, Yixin Chen, **Lei Wei**\*, Xuegong Zhang\*. uHAF: a unified hierarchical annotation framework for cell type standardization and harmonization. *Bioinformatics*, 2025: btaf149.
1. Haochen Li, Tianxing Ma, Zetong Zhao, Yixin Chen, Xi Xi, Xiaofei Zhao, Xiaoxiang Zhou, Yibo Gao, **Lei Wei**\*, Xuegong Zhang. scTML: a pan-cancer single-cell landscape of multiple mutation types. *Nucleic Acids Research*, 2024: gkae898.
1. Haoxiao Cai, Xiaoran Zhang, Rong Qiao, Xiaowo Wang\*, **Lei Wei**\*. Efficient computation by molecular competition networks. *Physical Review Research*, 2024, 6(3): 033208.
1. Haoxiang Gao, Kui Hua, Xinze Wu, **Lei Wei**\*, Sijie Chen, Qijin Yin, Rui Jiang, Xuegong Zhang\*. Building a learnable universal coordinate system for single-cell atlas with a joint-VAE model. *Communications Biology*, 2024, 7(1): 977.
1. Haiyang Bian, Yixin Chen, Xiaomin Dong, Chen Li, Minsheng Hao, Sijie Chen, Jinyi Hu, Maosong Sun, **Lei Wei**\*, Xuegong Zhang\*. scMulan: a multitask generative pre-trained language model for single-cell analysis. RECOMB, 2024: 479-482.
1. Chuxi Xiao, Yixin Chen, Qiuchen Meng, **Lei Wei**\*, Xuegong Zhang. Benchmarking multi-omics integration algorithms across single-cell RNA and ATAC data. *Briefings in Bioinformatics*, 2024, 25(2): bbae095.
2. Qiuchen Meng,  **Lei Wei**\*,   Kun Ma,   Ming Shi,   Xinyi Lin,   Joshua W K Ho,   Yinqing Li\*, Xuegong Zhang. scDecouple: decoupling cellular response from infected proportion bias in scCRISPR-seq. *Briefings in Bioinformatics*, 2024, 25(2): bbae011.
3. Minsheng Hao, Erpai Luo, Yixin Chen, Yanhong Wu, Chen Li, Sijie Chen, Haoxiang Gao, Haiyang Bian, Jin Gu, **Lei Wei**\*, Xuegong Zhang\*. STEM enables mapping of single-cell and spatial transcriptomics data with transfer learning. *Communications Biology*, 2024, 7(1): 56.
4. Haochen Li, Tianxing Ma, Minsheng Hao, Wenbo Guo, Jin Gu, Xuegong Zhang\*, **Lei Wei**\*. Decoding functional cell–cell communication events by multi-view graph learning on spatial transcriptomics. *Briefings in Bioinformatics*, 2023, 24(6): bbad359.
5. Wei Zhang, Hanwen Xu, Rong Qiao, Bixi Zhong, Xianglin Zhang, Jin Gu, Xuegong Zhang, **Lei Wei**\*, Xiaowo Wang\*. ARIC: accurate and robust inference of cell type proportions from bulk gene expression or DNA methylation data. *Briefings in Bioinformatics*. 2022, 23: bbab362.
6. **Lei Wei**#, Shuailin Li#, Pengcheng Zhang, Tao Hu, Michael Q. Zhang, Zhen Xie, Xiaowo Wang. Characterizing microRNA-mediated modulation of gene expression noise and its effect on synthetic gene circuits. *Cell Reports*, 2021, 36: 109573.
7. Tao Hu#, **Lei Wei**#, Shuailin Li, Tianrun Cheng, Xuegong Zhang, Xiaowo Wang. Single-cell transcriptomes reveal characteristics of micrornas in gene expression noise reduction. *Genomics, Proteomics & Bioinformatics*, 2021, 19: 394–407.
19.	Jiaqi Li#, **Lei Wei**#, Xianglin Zhang, Wei Zhang, Haochen Wang, Bixi Zhong, Zhen Xie, Hairong Lv, Xiaowo Wang, DISMIR: Deep learning-based noninvasive cancer detection by integrating DNA sequence and methylation information of individual cell-free DNA reads. *Briefings in Bioinformatics*, 2021, 22(6): bbab250.
20.	Wei Zhang, **Lei Wei**\*, Jiaqi Huang, Bixi Zhong, Jiaqi Li, Hanwen Xu, Shuying He, Yu Liu, Juhong Liu, Hairong Lv, Xiaowo Wang\*, cfDNApipe: a comprehensive quality control and analysis pipeline for cell-free DNA high-throughput sequencing data. *Bioinformatics*, 2021, 37: 4251–4252.
21.	Xuehui Liu#, **Lei Wei**#, Qiongye Dong, Liyang Liu, Michael Q Zhang, Zhen Xie, Xiaowo Wang. A large-scale CRISPR screen and identification of essential genes in cellular senescence bypass. *Aging (Albany NY)*, 2019, 11: 4011.
26.	**Lei Wei**#, Ye Yuan#, Tao Hu, Shuailin Li, Tianrun Cheng, Jinzhi Lei, Zhen Xie, Michael Q Zhang, Xiaowo Wang, Regulation by competition: a hidden layer of gene regulatory network. *Quantitative Biology*, 2019, 7: 110–121.



  

# Talks
- *2024.01*, Anhui University, Hefei.
- *2023.12*, 10th Young Bioinformatics PI Workshop, Shanghai.
- *2023.11*, Spatial Biology Congress Asia, Singapore.
- *2022.03*, The 1st Chinese Intelligent Health and Bioinformatics Conference (IHB) \[第一届智能健康与生物信息大会], Vitual (Fuzhou).
- *2021.12*, Chinese Academic Conference on Tumor Biomarker (CCTB) 2021 \[2021年中国肿瘤标志物学术大会], Vitual (Shenyang).
- *2020.12*, Bioinformatics and Intelligent Information Processing Conference (BIIP) 2020 \[生物信息学与智能信息处理2020学术年会], Virtual (Chengdu).

# Academic Services
- Review activity
  - *Nature Methods*
  - *Nature Physics*
  - *Nature Communications*
  - *National Science Review*
  - *Nucleic Acids Research*
  - *Genome Research*
  - *Cell Genomics*
  - *Cell Reports Methods*
  - *PLoS Computational Biology*
  - *BMC Bioinformatics*
  - *Journal of Medical Internet Research*
  - *Journal of Theoretical Biology*
  - *Quantitative Biology*
