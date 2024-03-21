# multimodal-reading-group

---
| Date | Paper | Authors | Comments |
| :--- | :---- | :------ | :------- |
| 01.02.2024 | [Visual Instruction Tuning](https://arxiv.org/abs/2304.08485) | H. Liu, C. Li, Q. Wu, Y. J. Lee ||
| 08.02.2024 | [When and why vision-language models behave like bags-of-words, and what to do about it?](https://arxiv.org/abs/2210.01936) | M. Yuksekgonul, F. Bianchi, P. Kalluri, D. Jurafsky, J. Zou | Why did they expect that CLIP will take a word order into account given that CLIP is trained to match a bag-of-words with a corresponding image? |
| 22.02.2024 | [Learning Transferable Visual Models From Natural Language Supervision](https://arxiv.org/abs/2103.00020) | A. Radford, J.W. Kim, C. Hallacy, A. Ramesh, G.Goh, S. Agarwal, G. Sastry, A. Askell, P. Mishkin, J. Clark, G. Krueger, I. Sutskever | See also [open source implementation](https://github.com/mlfoundations/open_clip) of CLIP; [Scaling laws for contrastive language-image learning](https://arxiv.org/abs/2212.07143)| 
| 29.02.2024 | Continue | | Fig. 2 is unclear. How do they obtain a vector for a bag-of-words? | 
| 07.03.2024 | Still (sic!) continue | | It seems that they train using BoW, even though their inference pipeline does not reflect this. | 
| 14.03.2024 | [Sigmoid Loss for Language Image Pre-Training](https://arxiv.org/abs/2303.15343) | X. Zhai, B. Mustafa, A. Kolesnikov, L. Beyer ||
| 21.03.2024 | Continue | | |
---


<details>
<summary> Datasets and benchmarks </summary>

- [ ] Liang et al. [MULTIBENCH: Multiscale Benchmarks for Multimodal Representation Learning](https://github.com/pliang279/MultiBench)
</details>

<details>
<summary> Surveys </summary>

- [ ] Liang et al. [Foundations & Trends in Multimodal Machine Learning: Principles, Challenges, and Open Questions](https://arxiv.org/abs/2209.03430)
</details>

<details> 
<summary> Representation Learning </summary>

<details>
<summary> Latent Space Structure </summary>

- [ ] Liang et at [Mind the Gap: Understanding the Modality Gap in Multi-modal Contrastive Representation Learning](https://github.com/Weixin-Liang/Modality-Gap)
- [x] Yuksekgonul et al. [When and why vision-language models behave like bags-of-words, and what to do about it?](https://arxiv.org/abs/2210.01936)
</details>

<details>
<summary> Fusion </summary>

- [x] Liu et al. [Visual Instruction Tuning](https://arxiv.org/abs/2304.08485)
- [x] Radford et al. [Learning Transferable Visual Models From Natural Language Supervision](https://arxiv.org/abs/2103.00020)
- [x] Zhai et al. [Sigmoid Loss for Language Image Pre-Training](https://arxiv.org/abs/2303.15343)
- [ ] Nagrani et al. [Attention Bottlenecks for Multimodal Fusion](https://arxiv.org/pdf/2107.00135.pdf)
- [ ] Baevski et al. [data2vec: A General Framework for Self-supervised Learning in Speech, Vision and Language](https://arxiv.org/abs/2202.03555)
- [ ] Recasens et al. [Zorro: the masked multimodal transformer](https://arxiv.org/abs/2301.09595)
- [ ] Jaegle et al. [Perceiver: General Perception with Iterative Attention](https://arxiv.org/abs/2103.03206)
- [ ] Liu et al. [Universal Vision-Language Dense Retrieval: Learning A Unified Representation Space For Multi-Modal Retrieval](https://arxiv.org/abs/2209.00179)
- [ ] Kwon et al. [Masked Vision And Language Modeling For Multi-Modal Representation Learning](https://arxiv.org/abs/2208.02131)
- [ ] Liang et al. [High-Modality Multimodal Transformer: Quantifying Modality & Interaction Heterogeneity for High-Modality Representation Learning](https://arxiv.org/abs/2203.01311)
- [ ] Girdhar et al. [OMNIVORE: A Single Model for Many Visual Modalities](https://facebookresearch.github.io/omnivore/)
- [ ] Shvetsova et al. [Everything at Once – Multi-modal Fusion Transformer for Video Retrieval](https://github.com/ninatu/everything_at_once)
</details>

<details>
<summary> Modality Competition. Quantitative Methods of Detection of Suboptimality. </summary>
  
- [ ] Wang et al. [What Makes Training Multi-modal Classification Networks Hard?](https://arxiv.org/abs/1905.12681)
- [ ] Wu et al. [Characterizing and Overcoming the Greedy Nature of Learning in Multi-modal Deep Neural Networks](https://arxiv.org/abs/2202.05306)
- [ ] Huang et al. [Modality Competition: What Makes Joint Training of Multi-modal Network Fail in Deep Learning? (Provably)](https://arxiv.org/abs/2203.12221)
</details>
