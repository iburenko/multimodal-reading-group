# multimodal-reading-group

---
| Date | Paper | Authors | Code | Demo | Comments |
| :--- | :---- | :------ | :--- | :--- | :------- |
| 01.02.2024 | [Visual Instruction Tuning](https://arxiv.org/abs/2304.08485) | H. Liu, C. Li, Q. Wu, Y. J. Lee | [GitHub](https://github.com/haotian-liu/LLaVA) [Project Page](https://llava-vl.github.io/)|[Demo](https://llava.hliu.cc/)||
| 08.02.2024 | [When and why vision-language models behave like bags-of-words, and what to do about it?](https://arxiv.org/abs/2210.01936) | M. Yuksekgonul, F. Bianchi, P. Kalluri, D. Jurafsky, J. Zou | https://github.com/mertyg/vision-language-models-are-bows| [Colab](https://colab.research.google.com/drive/1Rmn8CYXRFg4eC458vkBHwAdVKgS03e5D?usp=sharing) | Why did they expect that CLIP will take a word order into account given that CLIP is trained to match a bag-of-words with a corresponding image? |
| 22.02.2024 | [Learning Transferable Visual Models From Natural Language Supervision](https://arxiv.org/abs/2103.00020) | A. Radford, J.W. Kim, C. Hallacy, A. Ramesh, G.Goh, S. Agarwal, G. Sastry, A. Askell, P. Mishkin, J. Clark, G. Krueger, I. Sutskever | [GitHub](https://github.com/openai/CLIP) [Project Page](https://openai.com/research/clip) |[Colab](https://colab.research.google.com/github/openai/clip/blob/master/notebooks/Interacting_with_CLIP.ipynb) | See also [open source implementation](https://github.com/mlfoundations/open_clip) of CLIP; [Scaling laws for contrastive language-image learning](https://arxiv.org/abs/2212.07143)| 
| 29.02.2024 | Continue | | Fig. 2 is unclear. How do they obtain a vector for a bag-of-words? | 
| 07.03.2024 | Still (sic!) continue | | It seems that they train using BoW, even though their inference pipeline does not reflect this. | 
| 14.03.2024 | [Sigmoid Loss for Language Image Pre-Training](https://arxiv.org/abs/2303.15343) | X. Zhai, B. Mustafa, A. Kolesnikov, L. Beyer | [HuggingFace](https://huggingface.co/docs/transformers/en/model_doc/siglip) | |
| 21.03.2024 | Continue | | |
| 28.03.2024 | [Mind the Gap: Understanding the Modality Gap in Multi-modal Contrastive Representation Learning](https://arxiv.org/abs/2203.02053) | W. Liang, Y. Zhang, Y. Kwon, S. Yeung, J. Zou | [GitHub](https://github.com/Weixin-Liang/Modality-Gap) [Project Page](https://modalitygap.readthedocs.io/en/latest/) | |
| 04.04.2024 | [What Makes Training Multi-modal Classification Networks Hard?](https://arxiv.org/abs/1905.12681) | Wang, Tran, Feiszli | |
| 11.04.2024 | [MultiBench: Multiscale Benchmarks for Multimodal Representation Learning](https://arxiv.org/abs/2107.07502) | Liang, Lyu, Fan, Wu, Cheng, Wu, Chen, Wu, Lee, Zhu, Salakhutdinaov, Morency | [GitHub](https://github.com/pliang279/MultiBench) [Project Page](https://cmu-multicomp-lab.github.io/multibench/) | [Demos](https://github.com/pliang279/MultiBench/tree/main/examples)|
| 16.04.2024 | [Eyes Wide Shut? Exploring the Visual Shortcomings of Multimodal LLMs](https://arxiv.org/abs/2401.06209) | Tong, Liu, Zhai, Ma, LeCun, Xie | [GitHub](https://github.com/tsb0601/MMVP) [Project Page](https://tsb0601.github.io/mmvp_blog/)| [HuggingFace](https://huggingface.co/MMVP) |
| 23.04.2024 | [Scaling (Down) CLIP: A Comprehensive Analysis of Data, Architecture, and Training Strategies](https://arxiv.org/abs/2404.08197) | Li, Xie, Cubuk | |
| 30.04.2024 | [Chameleon: Plug-and-Play Compositional Reasoning with Large Language Models](https://arxiv.org/abs/2304.09842) | Lu, Peng, Cheng, Galley, Chang, Wu, Zhu, Gao | [GitHub](https://github.com/lupantech/chameleon-llm), [Project Page](https://chameleon-llm.github.io/) | 
| 07.05.2024 | [Many-Shot In-Context Learning](https://arxiv.org/abs/2404.11018) | Agarwal, Singh, Zhang, Bohnet, Chan, Anand, Abbas, Nova, Co-Reyes, Chu, Behbahani, Faust, Larochelle | Not Provided | 
| 28.05.2024 | [BABILong: a long-context needle-in-a-haystack benchmark for LLMs](https://arxiv.org/abs/2402.10790) | Kuratob, Bulatov, Anokhin, Sorokin, Sorokin, Burtsev | [GitHub](https://github.com/booydar/babilong) 
| 04.06.2024 | Continue |
| 11.06.2024 | [4M: Massively Multimodal Masked Modeling](https://arxiv.org/abs/2312.06647) | Mizrahi, Bachmann, Kar, Yeo, Gao, Dehghan, Zamir | [GitHub](https://github.com/apple/ml-4m) [Project Page](https://4m.epfl.ch/)
| 18.06.2024 | Continue |
| 25.06.2024 | [GLaMM: Pixel Grounding Large Multimodal Model](https://arxiv.org/abs/2311.03356) | Rasheed, Maaz, Shaji, Shaker, Khan, Cholakkal, Anwer, Xing, Yang, Khan | [GitHub](https://github.com/mbzuai-oryx/groundingLMM) [Project Page](https://mbzuai-oryx.github.io/groundingLMM/) | [Demo](https://glamm.mbzuai-oryx.ngrok.app/) |
| 02.07.2024 | Code Reading Group |
| 09.07.2024 | Knowledge Distillation | [Gemma 2 (pdf)](https://storage.googleapis.com/deepmind-media/gemma/gemma-2-report.pdf), [MobileLLM](https://arxiv.org/abs/2402.14905), [Knowledge distillation](https://arxiv.org/abs/2106.05237), [On-Policy distillation of Language Models](https://arxiv.org/abs/2306.13649)
| 16.07.2024 | [Whiteboard-of-Thought: Thinking Step-by-Step Across Modalities](https://arxiv.org/abs/2406.14562) | Menon, Zemel, Vondrick | [Project Page](https://whiteboard.cs.columbia.edu/)
| 23.07.2024 | [Multimodal Neurons in Artificial Neural Networks](https://distill.pub/2021/multimodal-neurons/) | Goh, Cammarata, Voss, Carter, Petrov, Schubert, Radford, Olah |
| 30.07.2024 | Continue + (very briefly) [CLIPPO](https://arxiv.org/abs/2212.08045) |
| 06.08.2024 | [Does my multimodal model learn cross-modal interactions? It's harder to tell than you might think!](https://arxiv.org/abs/2010.06572) | Hessel, Lee |
| 13.08.2024 | Graph of Thoughts and Monte Carlo Tree Search | Monte Carlo Tree Search from [Accessing GPT-4 level Mathematical Olympiad Solutions via Monte Carlo Tree Self-refine with LLaMa-3 8B](https://arxiv.org/abs/2406.07394); [Graph of Thoughts](https://arxiv.org/abs/2308.09687); [Large Language Monkeys](https://arxiv.org/abs/2407.21787); [STaR: Self-Taught Reasoner](https://arxiv.org/abs/2203.14465); [Agent Hospital: A Simulacrum of Hospital with Evolvable Medical Agents](https://arxiv.org/abs/2405.02957); Bonus! [DeepSeek-Prover-V1.5](https://arxiv.org/abs/2408.08152) | [Tinygrad example of MCTS](https://github.com/tinygrad/tinygrad/blob/63a8bc29d4e82626c1f579d33ef94a8b0b2822bd/extra/mcts_search.py#L74) 
| 15.10.2024 |
| 22.10.2024 | [Calibration Multimodal Learning](https://openreview.net/forum?id=hTWqB327Oay) | Ma, Zhang, Wu, Fu, Hu |
| 08.11.2024 | Towards Mamba: the S4 model and topic around: [HiPPo](https://arxiv.org/abs/2008.07669), [S4 paper](https://arxiv.org/abs/2111.00396), [Annotated S4 blog post](https://srush.github.io/annotated-s4/) | Gu, Goel, Ré | [GitHub](https://github.com/state-spaces/s4) |
| 15.11.2024 | Continue: HiPPO and S4 | 
| 22.11.2024 | Continue: Mamba & differences between Transformers and SSMs | 
| 07.02.2025 | **RLHF Block.** Part 1. Motivation and the RLHF fine-tuning | Stiennon and friends [Learning to summarize from human feedback](https://arxiv.org/abs/2009.01325) (RLHF for summarisation); Ouyang and friends [Training language models to follow instructions with human feedback](https://arxiv.org/abs/2203.02155) (RLHF for wide range of NLP-related tasks) | 
| 14.02.2025 | **RLHF Block.** Part 2. Motivation and the RLHF fine-tuning | [Stiennon et al.](https://arxiv.org/abs/2009.01325), [Ouyand et al.](https://arxiv.org/abs/2203.02155) + Ziegler et al. [Fine-Tuning Language Models from Human Preferences](https://arxiv.org/abs/1909.08593) |
| 21.02.2025 | **RLHF Block.** Part 3. Motivation and the RLHF fine-tuning | Finish discussing [Ouyand et al.](https://arxiv.org/abs/2203.02155) |
| 24.02.2025 | **RLHF Block.** Part 4. Reinforcement Learning. Q-Learning and PPO | TBA |
---


<details>
<summary> Datasets and benchmarks </summary>

- [x] Liang et al. [MULTIBENCH: Multiscale Benchmarks for Multimodal Representation Learning](https://github.com/pliang279/MultiBench)
</details>

<details>
<summary> Surveys </summary>

- [ ] Liang et al. [Foundations & Trends in Multimodal Machine Learning: Principles, Challenges, and Open Questions](https://arxiv.org/abs/2209.03430)
</details>

<details> 
<summary> Representation Learning </summary>

<details>
<summary> Latent Space Structure </summary>

- [x] Liang et at [Mind the Gap: Understanding the Modality Gap in Multi-modal Contrastive Representation Learning](https://github.com/Weixin-Liang/Modality-Gap)
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
  
- [x] Wang et al. [What Makes Training Multi-modal Classification Networks Hard?](https://arxiv.org/abs/1905.12681)
- [ ] Wu et al. [Characterizing and Overcoming the Greedy Nature of Learning in Multi-modal Deep Neural Networks](https://arxiv.org/abs/2202.05306)
- [ ] Huang et al. [Modality Competition: What Makes Joint Training of Multi-modal Network Fail in Deep Learning? (Provably)](https://arxiv.org/abs/2203.12221)
</details>
