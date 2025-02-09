---
title: Accurate RNA velocity estimation based on multibatch network reveals complex
  lineage in batch scRNA-seq data
authors:
- admin
- Xinyang Guo
- Jie Qin
- Lin Gao
- Fen Ju
- Chenguang Zhao
- Liang Yu
date: '2024-01-01'
publishDate: '2025-02-05T11:53:58.879412Z'
publication_types:
- article-journal
publication: '*BMC Biology*'
# doi: 10.1186/s12915-024-02085-8
links:
- name: URL
  url: https://doi.org/10.1186/s12915-024-02085-8

# Mannual add
featured: true
# url_pdf: https://bmcbiol.biomedcentral.com/counter/pdf/10.1186/s12915-024-02085-8.pdf
url_code: https://github.com/HuangDDU/velovgi_workstation

abstract: RNA velocity, as an extension of trajectory inference, is an effective method for understanding cell development using single-cell RNA sequencing (scRNA-seq) experiments. However, existing RNA velocity methods are limited by the batch effect because they cannot directly correct for batch effects in the input data, which comprises spliced and unspliced matrices in a proportional relationship. This limitation can lead to an incorrect velocity stream. This paper introduces VeloVGI, which addresses this issue innovatively in two key ways. Firstly, it employs an optimal transport (OT) and mutual nearest neighbor (MNN) approach to construct neighbors in batch data. This strategy overcomes the limitations of existing methods that are affected by the batch effect. Secondly, VeloVGI improves upon VeloVI’s velocity estimation by incorporating the graph structure into the encoder for more effective feature extraction. The effectiveness of VeloVGI is demonstrated in various scenarios, including the mouse spinal cord and olfactory bulb tissue, as well as on several public datasets. The results show that VeloVGI outperformed other methods in terms of metric performance.
---
