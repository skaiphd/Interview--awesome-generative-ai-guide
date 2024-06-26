# :star: :bookmark: awesome-generative-ai-guide

Generative AI is experiencing rapid growth, and this repository serves as a comprehensive hub for updates on generative AI research, interview materials, notebooks, and more!

Explore the following resources:

1. [Monthly Best GenAI Papers List](https://github.com/aishwaryanr/awesome-generative-ai-guide?tab=readme-ov-file#star-best-genai-papers-list-january-2024)
2. [GenAI Interview Resources](https://github.com/aishwaryanr/awesome-generative-ai-guide?tab=readme-ov-file#computer-interview-prep)
3. [Applied LLMs Mastery 2024 (created by Aishwarya Naresh Reganti) course material](https://github.com/aishwaryanr/awesome-generative-ai-guide?tab=readme-ov-file#ongoing-applied-llms-mastery-2024)
4. [List of all GenAI-related free courses (over 75 listed)](https://github.com/aishwaryanr/awesome-generative-ai-guide?tab=readme-ov-file#book-list-of-free-genai-courses)
5. [List of code repositories/notebooks for developing generative AI applications](https://github.com/aishwaryanr/awesome-generative-ai-guide?tab=readme-ov-file#notebook-code-notebooks)

We'll be updating this repository regularly, so keep an eye out for the latest additions!

Happy Learning!

---

## :speaker: Announcements

- Applied LLMs Mastery full course content has been released!!! ([Click Here](https://github.com/aishwaryanr/awesome-generative-ai-guide/blob/main/free_courses/Applied_LLMs_Mastery_2024))
- 5-day roadmap to learn LLM foundations out now! ([Click Here](https://github.com/aishwaryanr/awesome-generative-ai-guide/blob/main/resources/genai_roadmap.md))
- 60 Common GenAI Interview Questions out now! ([Click Here](https://github.com/aishwaryanr/awesome-generative-ai-guide/blob/main/interview_prep/60_gen_ai_questions.md))
- ICLR 2024 paper summaries ([Click Here](https://areganti.notion.site/06f0d4fe46a94d62bff2ae001cfec22c?v=d501ca62e4b745768385d698f173ae14))
- List of free GenAI courses ([Click Here](https://github.com/aishwaryanr/awesome-generative-ai-guide#book-list-of-free-genai-courses))
- Generative AI resources and roadmaps
  - [3-day RAG roadmap](https://github.com/aishwaryanr/awesome-generative-ai-guide/blob/main/resources/RAG_roadmap.md)
  - [5-day LLM foundations roadmap](https://github.com/aishwaryanr/awesome-generative-ai-guide/blob/main/resources/genai_roadmap.md)
  - [5-day LLM agents roadmap](https://github.com/aishwaryanr/awesome-generative-ai-guide/blob/main/resources/agents_roadmap.md)
  - [Agents 101 guide](https://github.com/aishwaryanr/awesome-generative-ai-guide/blob/main/resources/agents_101_guide.md)
  - [Introduction to MM LLMs](https://github.com/aishwaryanr/awesome-generative-ai-guide/blob/main/resources/mm_llms_guide.md)
  - [LLM Lingo Series: Commonly used LLM terms and their easy-to-understand definitions](https://github.com/aishwaryanr/awesome-generative-ai-guide/blob/main/resources/llm_lingo)

---

## :star: Best Gen AI Papers List (May 2024)

\*Updated at the end of every month
| Date | Title | Abstract | Topics |
| --- | --- | --- | --- |
| 31 May 2024 | [LLMs achieve adult human performance on higher-order theory of mind tasks](https://arxiv.org/pdf/2405.18870) | This paper examines the extent to which large language models (LLMs) have developed higher-order theory of mind (ToM); the human ability to reason about multiple mental and emotional states in a recursive manner (e.g. I think that you believe that she knows). This paper builds on prior work by introducing a handwritten test suite – Multi-Order Theory of Mind Q&A – and using it to compare the performance of five LLMs to a newly gathered adult human benchmark. We find that GPT-4 and Flan-PaLM reach adult-level and near adult-level performance on ToM tasks overall, and that GPT-4 exceeds adult performance on 6th order inferences. Our results suggest that there is an interplay between model size and finetuning for the realisation of ToM abilities, and that the best-performing LLMs have developed a generalised capacity for ToM. Given the role that higher-order ToM plays in a wide range of cooperative and competitive human behaviours, these findings have significant implications for user-facing LLM applications. | Theory of Mind |
| 30 May 2024 | [JINA CLIP: Your CLIP Model Is Also Your Text Retriever](https://arxiv.org/pdf/2405.20204) | Contrastive Language-Image Pretraining (CLIP) is widely used to train models to align images and texts in a common embedding space by mapping them to fixed-sized vectors. These models are key to multimodal information retrieval and related tasks. However, CLIP models generally underperform in text-only tasks compared to specialized text models. This creates inefficiencies for information retrieval systems that keep separate embeddings and models for text-only and multimodal tasks. We propose a novel, multi-task contrastive training method to address this issue, which we use to train the jina-clip-v1 model to achieve the state-of-the-art performance on both text-image and text-text retrieval tasks. | Multimodal Models |
| 30 May 2024 | [Parrot: Efficient Serving of LLM-based Applications with Semantic Variable](https://arxiv.org/pdf/2405.19888) | The rise of large language models (LLMs) has enabled LLM-based applications (a.k.a. AI agents or co-pilots), a new software paradigm that combines the strength of LLM and conventional software. Diverse LLM applications from different tenants could design complex workflows using multiple LLM requests to accomplish one task. However, they have to use the over-simplified request-level API provided by today’s public LLM services, losing essential application-level information. Public LLM services have to blindly optimize individual LLM requests, leading to sub-optimal end-to-end performance of LLM applications. This paper introduces Parrot, an LLM service system that focuses on the end-to-end experience of LLM-based applications. Parrot proposes Semantic Variable, a unified abstraction to expose application-level knowledge to public LLM services. A Semantic Variable annotates an input/output variable in the prompt of a request, and creates the data pipeline when connecting multiple LLM requests, providing a natural way to program LLM applications. Exposing Semantic Variables to the public LLM service allows it to perform conventional data flow analysis to uncover the correlation across multiple LLM requests. This correlation opens a brand-new optimization space for the end-to-end performance of LLMbased applications. Extensive evaluations demonstrate that Parrot can achieve up to an order-of-magnitude improvement for popular and practical use cases of LLM applications | LLM Agents |
| 30 May 2024 | [Perplexed by Perplexity: Perplexity-Based Data Pruning With Small Reference Models](https://arxiv.org/pdf/2405.20541) | In this work, we investigate whether small language models can determine highquality subsets of large-scale text datasets that improve the performance of larger language models. While existing work has shown that pruning based on the perplexity of a larger model can yield high-quality data, we investigate whether smaller models can be used for perplexity-based pruning and how pruning is affected by the domain composition of the data being pruned. We demonstrate that for multiple dataset compositions, perplexity-based pruning of pretraining data can significantly improve downstream task performance: pruning based on perplexities computed with a 125 million parameter model improves the average performance on downstream tasks of a 3 billion parameter model by up to 2.04 and achieves up to a 1.45× reduction in pretraining steps to reach commensurate baseline performance. Furthermore, we demonstrate that such perplexity-based data pruning also yields downstream performance gains in the over-trained and data-constrained regimes. | Small Language Models |
| 30 May 2024 | [GNN-RAG: Graph Neural Retrieval for Large Language Model Reasoning](https://arxiv.org/pdf/2405.20139) | Knowledge Graphs (KGs) represent human-crafted factual knowledge in the form of triplets (head, relation, tail), which collectively form a graph. Question Answering over KGs (KGQA) is the task of answering natural questions grounding the reasoning to the information provided by the KG. Large Language Models (LLMs) are the state-of-the-art models for QA tasks due to their remarkable ability to understand natural language. On the other hand, Graph Neural Networks (GNNs) have been widely used for KGQA as they can handle the complex graph information stored in the KG. In this work, we introduce GNN-RAG, a novel method for combining language understanding abilities of LLMs with the reasoning abilities of GNNs in a retrieval-augmented generation (RAG) style. First, a GNN reasons over a dense KG subgraph to retrieve answer candidates for a given question. Second, the shortest paths in the KG that connect question entities and answer candidates are extracted to represent KG reasoning paths. The extracted paths are verbalized and given as input for LLM reasoning with RAG. In our GNN-RAG framework, the GNN acts as a dense subgraph reasoner to extract useful graph information, while the LLM leverages its natural language processing ability for ultimate KGQA. Furthermore, we develop a retrieval augmentation (RA) technique to further boost KGQA performance with GNN-RAG. Experimental results show that GNN-RAG achieves state-of-the-art performance in two widely used KGQA benchmarks (WebQSP and CWQ), outperforming or matching GPT-4 performance with a 7B tuned LLM. In addition, GNN-RAG excels on multi-hop and multi-entity questions outperforming competing approaches by 8.9–15.5% points at answer F1. We provide the code and KGQA results at https://github.com/cmavro/GNN-RAG. | RAG on Knowledge Graphs |
| 29 May 2024 | [Self-Exploring Language Models: Active Preference Elicitation for Online Alignment](https://arxiv.org/pdf/2405.19332) | Preference optimization, particularly through Reinforcement Learning from Human Feedback (RLHF), has achieved significant success in aligning Large Language Models (LLMs) to adhere to human intentions. Unlike offline alignment with a fixed dataset, online feedback collection from humans or AI on model generations typically leads to more capable reward models and better-aligned LLMs through an iterative process. However, achieving a globally accurate reward model requires systematic exploration to generate diverse responses that span the vast space of natural language. Random sampling from standard reward-maximizing LLMs alone is insufficient to fulfill this requirement. To address this issue, we propose a bilevel objective optimistically biased towards potentially high-reward responses to actively explore out-of-distribution regions. By solving the inner-level problem with the reparameterized reward function, the resulting algorithm, named Self-Exploring Language Models (SELM), eliminates the need for a separate RM and iteratively updates the LLM with a straightforward objective. Compared to Direct Preference Optimization (DPO), the SELM objective reduces indiscriminate favor of unseen extrapolations and enhances exploration efficiency. Our experimental results demonstrate that when finetuned on Zephyr-7B-SFT and Llama-3- 8B-Instruct models, SELM significantly boosts the performance on instructionfollowing benchmarks such as MT-Bench and AlpacaEval 2.0, as well as various standard academic benchmarks in different settings. Our code and models are available at https://github.com/shenao-zhang/SELM. | Alignment, Preference Optimization |
| 28 May 2024 | [OpenRLHF: An Easy-to-use, Scalable and High-performance RLHF Framework](https://arxiv.org/pdf/2405.11143) | As large language models (LLMs) continue to grow by scaling laws, reinforcement learning from human feedback (RLHF) has gained significant attention due to its outstanding performance. However, unlike pretraining or fine-tuning a single model, scaling reinforcement learning from human feedback (RLHF) for training large language models poses coordination challenges across four models. We present OpenRLHF, an open-source framework enabling efficient RLHF scaling. Unlike existing RLHF frameworks that co-locate four models on the same GPUs, OpenRLHF re-designs scheduling for the models beyond 70B parameters using Ray, vLLM, and DeepSpeed, leveraging improved resource utilization and diverse training approaches. Integrating seamlessly with Hugging Face, OpenRLHF provides an out-of-the-box solution with optimized algorithms and launch scripts, which ensures user-friendliness. OpenRLHF implements RLHF, DPO, rejection sampling, and other alignment techniques. Empowering state-of-the-art LLM development, OpenRLHF’s code is available at https://github.com/OpenLLMAI/OpenRLHF. | RLHF, Toolkit |
| 28 May 2024 | [LLAMA-NAS: EFFICIENT NEURAL ARCHITECTURE SEARCH FOR LARGE LANGUAGE MODELS](https://arxiv.org/pdf/2405.18377) | The abilities of modern large language models (LLMs) in solving natural language processing, complex reasoning, sentiment analysis and other tasks have been extraordinary which has prompted their extensive adoption. Unfortunately, these abilities come with very high memory and computational costs which precludes the use of LLMs on most hardware platforms. To mitigate this, we propose an effective method of finding Pareto-optimal network architectures based on LLaMA2-7B using one-shot NAS. In particular, we fine-tune LLaMA2-7B only once and then apply genetic algorithmbased search to find smaller, less computationally complex network architectures. We show that, for certain standard benchmark tasks, the pre-trained LLaMA2-7B network is unnecessarily large and complex. More specifically, we demonstrate a 1.5x reduction in model size and 1.3x speedup in throughput for certain tasks with negligible drop in accuracy. In addition to finding smaller, higherperforming network architectures, our method does so more effectively and efficiently than certain pruning or sparsification techniques. Finally, we demonstrate how quantization is complementary to our method and that the size and complexity of the networks we find can be further decreased using quantization. We believe that our work provides a way to automatically create LLMs which can be used on less expensive and more readily available hardware platforms. | Neural Architecture Search, Model Size Reduction |
| 28 May 2024 | [Don’t Forget to Connect! Improving RAG with Graph-based Reranking](https://arxiv.org/pdf/2405.18414) | Retrieval Augmented Generation (RAG) has greatly improved the performance of Large Language Model (LLM) responses by grounding generation with context from existing documents. These systems work well when documents are clearly relevant to a question context. But what about when a document has partial information, or less obvious connections to the context? And how should we reason about connections between documents? In this work, we seek to answer these two core questions about RAG generation. We introduce G-RAG, a reranker based on graph neural networks (GNNs) between the retriever and reader in RAG. Our method combines both connections between documents and semantic information (via Abstract Meaning Representation graphs) to provide a context-informed ranker for RAG. G-RAG outperforms state-of-the-art approaches while having smaller computational footprint. Additionally, we assess the performance of PaLM 2 as a reranker and find it to significantly underperform G-RAG. This result emphasizes the importance of reranking for RAG even when using Large Language Models. | RAG for Reasoning |
| 27 May 2024 | [Meteor: Mamba-based Traversal of Rationale for Large Language and Vision Models](https://arxiv.org/pdf/2405.15574) | The rapid development of large language and vision models (LLVMs) has been driven by advances in visual instruction tuning. Recently, open-source LLVMs have curated high-quality visual instruction tuning datasets and utilized additional vision encoders or multiple computer vision models in order to narrow the performance gap with powerful closed-source LLVMs. These advancements are attributed to multifaceted information required for diverse capabilities, including fundamental image understanding, real-world knowledge about common-sense and non-object concepts (e.g., charts, diagrams, symbols, signs, and math problems), and step-by-step procedures for solving complex questions. Drawing from the multifaceted information, we present a new efficient LLVM, Mamba-based traversal of rationales ( Meteor), which leverages multifaceted rationale to enhance understanding and answering capabilities. To embed lengthy rationales containing abundant information, we employ the Mamba architecture, capable of processing sequential data with linear time complexity. We introduce a new concept of traversal of rationale that facilitates efficient embedding of rationale. Subsequently, the backbone multimodal language model (MLM) is trained to generate answers with the aid of rationale. Through these steps, Meteor achieves significant improvements in vision language performances across multiple evaluation benchmarks requiring diverse capabilities, without scaling up the model size or employing additional vision encoders and computer vision models. Code is available in https://github.com/ByungKwanLee/Meteor. | State Space Models, Multimodal Models |
| 27 May 2024 | [An Introduction to Vision-Language Modeling](https://arxiv.org/pdf/2405.17247) | Following the recent popularity of Large Language Models (LLMs), several attempts have been made to extend them to the visual domain. From having a visual assistant that could guide us through unfamiliar environments to generative models that produce images using only a high-level text description, the vision-language model (VLM) applications will significantly impact our relationship with technology. However, there are many challenges that need to be addressed to improve the reliability of those models. While language is discrete, vision evolves in a much higher dimensional space in which concepts cannot always be easily discretized. To better understand the mechanics behind mapping vision to language, we present this introduction to VLMs which we hope will help anyone who would like to enter the field. First, we introduce what VLMs are, how they work, and how to train them. Then, we present and discuss approaches to evaluate VLMs. Although this work primarily focuses on mapping images to language, we also discuss extending VLMs to videos. | Multimodal Models, Survey |
| 27 May 2024 | [Matryoshka Multimodal Models](https://arxiv.org/pdf/2405.17430) | Large Multimodal Models (LMMs) such as LLaVA have shown strong performance in visual-linguistic reasoning. These models first embed images into a fixed large number of visual tokens and then feed them into a Large Language Model (LLM). However, this design causes an excessive number of tokens for dense visual scenarios such as high-resolution images and videos, leading to great inefficiency. While token pruning and merging methods exist, they produce a single-length output for each image and cannot afford flexibility in trading off information density v.s. efficiency. Inspired by the concept of Matryoshka Dolls, we propose M3 : Matryoshka Multimodal Models, which learns to represent visual content as nested sets of visual tokens that capture information across multiple coarse-to-fine granularities. Our approach offers several unique benefits for LMMs: (1) One can explicitly control the visual granularity per test instance during inference, e.g., adjusting the number of tokens used to represent an image based on the anticipated complexity or simplicity of the content; (2) M3 provides a framework for analyzing the granularity needed for existing datasets, where we find that COCO-style benchmarks only need around 9 visual tokens to obtain an accuracy similar to that of using all 576 tokens; (3) Our approach provides a foundation to explore the best trade-off between performance and visual token length at the sample level, where our investigation reveals that a large gap exists between the oracle upper bound and current fixed-scale representations. | Multimodal Models |
| 27 May 2024 | [Trans-LoRA: towards data-free Transferable Parameter Efficient Finetuning](https://arxiv.org/pdf/2405.17258) | Low-rank adapters (LoRA) and their variants are popular parameter-efficient finetuning (PEFT) techniques that closely match full model fine-tune performance while requiring only a small number of additional parameters. These additional LoRA parameters are specific to the base model being adapted. When the base model needs to be deprecated and replaced with a new one, all the associated LoRA modules need to be re-trained. Such re-training requires access to the data used to train the LoRA for the original base model. This is especially problematic for commercial cloud applications where the LoRA modules and the base models are hosted by service providers who may not be allowed to host proprietary client task data. To address this challenge, we propose Trans-LoRA— a novel method for lossless, nearly data-free transfer of LoRAs across base models. Our approach relies on synthetic data to transfer LoRA modules. Using large language models, we design a synthetic data generator to approximate the data-generating process of the observed task data subset. Training on the resulting synthetic dataset transfers LoRA modules to new models. We show the effectiveness of our approach using both LLama and Gemma model families. Our approach achieves lossless (mostly improved) LoRA transfer between models within and across different base model families, and even between different PEFT methods, on a wide variety of tasks. | PEFT Methods, Fine-Tuning |
| 26 May 2024 | [Self-Play Preference Optimization for Language Model Alignment](https://arxiv.org/pdf/2405.00675) | Traditional reinforcement learning from human feedback (RLHF) approaches relying on parametric models like the Bradley-Terry model fall short in capturing the intransitivity and irrationality in human preferences. Recent advancements suggest that directly working with preference probabilities can yield a more accurate reflection of human preferences, enabling more flexible and accurate language model alignment. In this paper, we propose a self-playbased method for language model alignment, which treats the problem as a constant-sum two-player game aimed at identifying the Nash equilibrium policy. Our approach, dubbed Self-Play Preference Optimization (SPPO), approximates the Nash equilibrium through iterative policy updates and enjoys a theoretical convergence guarantee. Our method can effectively increase the log-likelihood of the chosen response and decrease that of the rejected response, which cannot be trivially achieved by symmetric pairwise loss such as Direct Preference Optimization (DPO) and Identity Preference Optimization (IPO). In our experiments, using only 60k prompts (without responses) from the UltraFeedback dataset and without any prompt augmentation, by leveraging a pre-trained preference model PairRM with only 0.4B parameters, SPPO can obtain a model from fine-tuning Mistral-7B-Instruct-v0.2 that achieves the state-of-the-art lengthcontrolled win-rate of 28.53% against GPT-4-Turbo on AlpacaEval 2.0. It also outperforms the (iterative) DPO and IPO on MT-Bench and the Open LLM Leaderboard. Notably, the strong performance of SPPO is achieved without additional external supervision (e.g., responses, preferences, etc.) from GPT-4 or other stronger language models. | Alignment, Optimization |
| 23 May 2024 | [Not All Language Model Features Are Linear](https://arxiv.org/pdf/2405.14860) | Recent work has proposed the linear representation hypothesis: that language models perform computation by manipulating one-dimensional representations of concepts (“features”) in activation space. In contrast, we explore whether some language model representations may be inherently multi-dimensional. We begin by developing a rigorous definition of irreducible multi-dimensional features based on whether they can be decomposed into either independent or non-co-occurring lower-dimensional features. Motivated by these definitions, we design a scalable method that uses sparse autoencoders to automatically find multi-dimensional features in GPT-2 and Mistral 7B. These auto-discovered features include strikingly interpretable examples, e.g. circular features representing days of the week and months of the year. We identify tasks where these exact circles are used to solve computational problems involving modular arithmetic in days of the week and months of the year. Finally, we provide evidence that these circular features are indeed the fundamental unit of computation in these tasks with intervention experiments on Mistral 7B and Llama 3 8B, and we find further circular representations by breaking down the hidden states for these tasks into interpretable components. | Linear Representation Analysis |
| 23 May 2024 | [AlignGPT: Multi-modal Large Language Models with Adaptive Alignment Capability](https://arxiv.org/pdf/2405.14129) | Multimodal Large Language Models (MLLMs) are widely regarded as crucial in the exploration of Artificial General Intelligence (AGI). The core of MLLMs lies in their capability to achieve cross-modal alignment. To attain this goal, current MLLMs typically follow a two-phase training paradigm: the pre-training phase and the instruction-tuning phase. Despite their success, there are shortcomings in the modeling of alignment capabilities within these models. Firstly, during the pre-training phase, the model usually assumes that all image-text pairs are uniformly aligned, but in fact the degree of alignment between different imagetext pairs is inconsistent. Secondly, the instructions currently used for finetuning incorporate a variety of tasks, different tasks’s instructions usually require different levels of alignment capabilities, but previous MLLMs overlook these differentiated alignment needs. To tackle these issues, we propose a new multimodal large language model AlignGPT. In the pre-training stage, instead of treating all imagetext pairs equally, we assign different levels of alignment capabilities to different image-text pairs. Then, in the instruction-tuning phase, we adaptively combine these different levels of alignment capabilities to meet the dynamic alignment needs of different instructions. Extensive experimental results show that our model achieves competitive performance on 12 benchmarks. | Alignment, Multimodal Model |
| 23 May 2024 | [HippoRAG: Neurobiologically Inspired Long-Term Memory for Large Language Models](https://arxiv.org/pdf/2405.14831) | In order to thrive in hostile and ever-changing natural environments, mammalian brains evolved to store large amounts of knowledge about the world and continually integrate new information while avoiding catastrophic forgetting. Despite the impressive accomplishments, large language models (LLMs), even with retrievalaugmented generation (RAG), still struggle to efficiently and effectively integrate a large amount of new experiences after pre-training. In this work, we introduce HippoRAG, a novel retrieval framework inspired by the hippocampal indexing theory of human long-term memory to enable deeper and more efficient knowledge integration over new experiences. HippoRAG synergistically orchestrates LLMs, knowledge graphs, and the Personalized PageRank algorithm to mimic the different roles of neocortex and hippocampus in human memory. We compare HippoRAG with existing RAG methods on multi-hop question answering and show that our method outperforms the state-of-the-art methods remarkably, by up to 20%. Singlestep retrieval with HippoRAG achieves comparable or better performance than iterative retrieval like IRCoT while being 10-30 times cheaper and 6-13 times faster, and integrating HippoRAG into IRCoT brings further substantial gains. Finally, we show that our method can tackle new types of scenarios that are out of reach of existing methods. | RAG Optimization |
| 21 May 2024 | [OmniGlue: Generalizable Feature Matching with Foundation Model Guidance](https://arxiv.org/pdf/2405.12979) | The image matching field has been witnessing a continuous emergence of novel learnable feature matching techniques, with ever-improving performance on conventional benchmarks. However, our investigation shows that despite these gains, their potential for real-world applications is restricted by their limited generalization capabilities to novel image domains. In this paper, we introduce OmniGlue, the first learnable image matcher that is designed with generalization as a core principle. OmniGlue leverages broad knowledge from a vision foundation model to guide the feature matching process, boosting generalization to domains not seen at training time. Additionally, we propose a novel keypoint position-guided attention mechanism which disentangles spatial and appearance information, leading to enhanced matching descriptors. We perform comprehensive experiments on a suite of 7 datasets with varied image domains, including scenelevel, object-centric and aerial images. OmniGlue’s novel components lead to relative gains on unseen domains of 20.9% with respect to a directly comparable reference model, while also outperforming the recent LightGlue method by 9.5% relatively. Code and model can be found at https: //hwjiang1510.github.io/OmniGlue. | Multimodal Models |
| 20 May 2024 | [MoRA: High-Rank Updating for Parameter-Efficient Fine-Tuning](https://arxiv.org/pdf/2405.12130) | Low-rank adaptation (LoRA) is a popular parameter-efficient fine-tuning (PEFT) method for large language models (LLMs). In this paper, we analyze the impact of low-rank updating, as implemented in LoRA. Our findings suggest that the low-rank updating mechanism may limit the ability of LLMs to effectively learn and memorize new knowledge. Inspired by this observation, we propose a new method called MoRA, which employs a square matrix to achieve high-rank updating while maintaining the same number of trainable parameters. To achieve it, we introduce the corresponding non-parameter operators to reduce the input dimension and increase the output dimension for the square matrix. Furthermore, these operators ensure that the weight can be merged back into LLMs, which makes our method can be deployed like LoRA. We perform a comprehensive evaluation of our method across five tasks: instruction tuning, mathematical reasoning, continual pretraining, memory and pretraining. Our method outperforms LoRA on memoryintensive tasks and achieves comparable performance on other tasks. Our code will be available at https://github.com/kongds/MoRA. | PEFT Approaches, Fine-Tuning |
| 19 May 2024 | [Your Transformer is Secretly Linear](https://arxiv.org/pdf/2405.12250) | This paper reveals a novel linear characteristic exclusive to transformer decoders, including models such as GPT, LLaMA, OPT, BLOOM and others. We analyze embedding transformations between sequential layers, uncovering a near-perfect linear relationship (Procrustes similarity score of 0.99). However, linearity decreases when the residual component is removed due to a consistently low output norm of the transformer layer. Our experiments show that removing or linearly approximating some of the most linear blocks of transformers does not affect significantly the loss or model performance. Moreover, in our pretraining experiments on smaller models we introduce a cosine-similarity-based regularization, aimed at reducing layer linearity. This regularization improves performance metrics on benchmarks like Tiny Stories and SuperGLUE and as well successfully decreases the linearity of the models. This study challenges the existing understanding of transformer architectures, suggesting that their operation may be more linear than previously assumed.1 | Transformer Analysis |
| 18 May 2024 | [Towards Modular LLMs by Building and Reusing a Library of LoRAs](https://arxiv.org/pdf/2405.11157) | The growing number of parameter-efficient adaptations of a base large language model (LLM) calls for studying whether we can reuse such trained adapters to improve performance for new tasks. We study how to best build a library of adapters given multi-task data and devise techniques for both zero-shot and supervised task generalization through routing in such library. We benchmark existing approaches to build this library and introduce model-based clustering, MBC, a method that groups tasks based on the similarity of their adapter parameters, indirectly optimizing for transfer across the multi-task dataset. To re-use the library, we present a novel zero-shot routing mechanism, Arrow, which enables dynamic selection of the most relevant adapters for new inputs without the need for retraining. We experiment with several LLMs, such as Phi-2 and Mistral, on a wide array of held-out tasks, verifying that MBC-based adapters and Arrow routing lead to superior generalization to new tasks. We make steps towards creating modular, adaptable LLMs that can match or outperform traditional joint training. | PEFT Approaches, Fine-Tuning, Toolkit |
| 16 May 2024 | [Chameleon: Mixed-Modal Early-Fusion Foundation Models](https://arxiv.org/pdf/2405.09818) | We present Chameleon, a family of early-fusion token-based mixed-modal models capable of understanding and generating images and text in any arbitrary sequence. We outline a stable training approach from inception, an alignment recipe, and an architectural parameterization tailored for the early-fusion, token-based, mixed-modal setting. The models are evaluated on a comprehensive range of tasks, including visual question answering, image captioning, text generation, image generation, and long-form mixed modal generation. Chameleon demonstrates broad and general capabilities, including state-of-the-art performance in image captioning tasks, outperforms Llama-2 in text-only tasks while being competitive with models such as Mixtral 8x7B and Gemini-Pro, and performs non-trivial image generation, all in a single model. It also matches or exceeds the performance of much larger models, including Gemini Pro and GPT-4V, according to human judgments on a new long-form mixed-modal generation evaluation, where either the prompt or outputs contain mixed sequences of both images and text. Chameleon marks a significant step forward in a unified modeling of full multimodal documents. | Multimodal Models, Foundation Model |
| 16 May 2024 | [Many-Shot In-Context Learning in Multimodal Foundation Models](https://arxiv.org/pdf/2405.09798) | Large language models are well-known to be effective at few-shot in-context learning (ICL). Recent advancements in multimodal foundation models have enabled unprecedentedly long context windows, presenting an opportunity to explore their capability to perform ICL with many more demonstrating examples. In this work, we evaluate the performance of multimodal foundation models scaling from few-shot to many-shot ICL. We benchmark GPT-4o and Gemini 1.5 Pro across 10 datasets spanning multiple domains (natural imagery, medical imagery, remote sensing, and molecular imagery) and tasks (multi-class, multi-label, and fine-grained classification). We observe that many-shot ICL, including up to almost 2,000 multimodal demonstrating examples, leads to substantial improvements compared to few-shot (<100 examples) ICL across all of the datasets. Further, Gemini 1.5 Pro performance continues to improve log-linearly up to the maximum number of tested examples on many datasets. Given the high inference costs associated with the long prompts required for many-shot ICL, we also explore the impact of batching multiple queries in a single API call. We show that batching up to 50 queries can lead to performance improvements under zero-shot and many–shot ICL, with substantial gains in the zero-shot setting on multiple datasets, while drastically reducing per-query cost and latency. Finally, we measure ICL data efficiency of the models, or the rate at which the models learn from more demonstrating examples. We find that while GPT-4o and Gemini 1.5 Pro achieve similar zero-shot performance across the datasets, Gemini 1.5 Pro exhibits higher ICL data efficiency than GPT-4o on most datasets. Our results suggest that many-shot ICL could enable users to efficiently adapt multimodal foundation models to new applications and domains. Our codebase is publicly available at https://github.com/stanfordmlgroup/ManyICL. | ICL, Multimodal Models |
| 15 May 2024 | [LoRA Learns Less and Forgets Less](https://arxiv.org/pdf/2405.09673) | Low-Rank Adaptation (LoRA) is a widely-used parameter-efficient finetuning method for large language models. LoRA saves memory by training only low rank perturbations to selected weight matrices. In this work, we compare the performance of LoRA and full finetuning on two target domains, programming and mathematics. We consider both the instruction finetuning (≈100K prompt-response pairs) and continued pretraining (≈10B unstructured tokens) data regimes. Our results show that, in most settings, LoRA substantially underperforms full finetuning. Nevertheless, LoRA exhibits a desirable form of regularization: it better maintains the base model’s performance on tasks outside the target domain. We show that LoRA provides stronger regularization compared to common techniques such as weight decay and dropout; it also helps maintain more diverse generations. We show that full finetuning learns perturbations with a rank that is 10-100X greater than typical LoRA configurations, possibly explaining some of the reported gaps. We conclude by proposing best practices for finetuning with LoRA. | PEFT Approaches, Fine-Tuning |
| 14 May 2024 | [Understanding the performance gap between online and offline alignment algorithms](https://arxiv.org/pdf/2405.08448) | Reinforcement learning from human feedback (RLHF) is the canonical framework for large language model alignment. However, rising popularity in offline alignment algorithms challenge the need for on-policy sampling in RLHF. Within the context of reward over-optimization, we start with an opening set of experiments that demonstrate the clear advantage of online methods over offline methods. This prompts us to investigate the causes to the performance discrepancy through a series of carefully designed experimental ablations. We show empirically that hypotheses such as offline data coverage and data quality by itself cannot convincingly explain the performance difference. We also find that while offline algorithms train policy to become good at pairwise classification, it is worse at generations; in the meantime the policies trained by online algorithms are good at generations while worse at pairwise classification. This hints at a unique interplay between discriminative and generative capabilities, which is greatly impacted by the sampling process. Lastly, we observe that the performance discrepancy persists for both contrastive and non-contrastive loss functions, and appears not to be addressed by simply scaling up policy networks. Taken together, our study sheds light on the pivotal role of on-policy sampling in AI alignment, and hints at certain fundamental challenges of offline alignment algorithms. | Alignment |
| 13 May 2024 | [RLHF Workflow: From Reward Modeling to Online RLHF](https://arxiv.org/pdf/2405.07863) | We present the workflow of Online Iterative Reinforcement Learning from Human Feedback (RLHF) in this technical report, which is widely reported to outperform its offline counterpart by a large margin in the recent large language model (LLM) literature. However, existing open-source RLHF projects are still largely confined to the offline learning setting. In this technical report, we aim to fill in this gap and provide a detailed recipe that is easy to reproduce for online iterative RLHF. In particular, since online human feedback is usually infeasible for open-source communities with limited resources, we start by constructing preference models using a diverse set of open-source datasets and use the constructed proxy preference model to approximate human feedback. Then, we discuss the theoretical insights and algorithmic principles behind online iterative RLHF, followed by a detailed practical implementation. Our trained LLM, SFR-Iterative-DPO-LLaMA-3-8B-R, achieves impressive performance on LLM chatbot benchmarks, including AlpacaEval-2, Arena-Hard, and MT-Bench, as well as other academic benchmarks such as HumanEval and TruthfulQA. We have shown that supervised fine-tuning (SFT) and iterative RLHF can obtain state-of-the-art performance with fully open-source datasets. Further, we have made our models, curated datasets, and comprehensive step-by-step code guidebooks publicly available. Please refer to https://github.com/RLHFlow/RLHF-Reward-Modeling and https://github.com/RLHFlow/Online-RLHF for more detailed information. | Preference Optimization, RLHF |
| 2 May 2024 | [PROMETHEUS 2: An Open Source Language Model Specialized in Evaluating Other Language Models](https://arxiv.org/pdf/2405.01535) | Proprietary LMs such as GPT-4 are often employed to assess the quality of responses from various LMs. However, concerns including transparency, controllability, and affordability strongly motivate the development of opensource LMs specialized in evaluations. On the other hand, existing open evaluator LMs exhibit critical shortcomings: 1) they issue scores that significantly diverge from those assigned by humans, and 2) they lack the flexibility to perform both direct assessment and pairwise ranking, the two most prevalent forms of assessment. Additionally, they do not possess the ability to evaluate based on custom evaluation criteria, focusing instead on general attributes like helpfulness and harmlessness. To address these issues, we introduce Prometheus 2, a more powerful evaluator LM than it’s predecessor that closely mirrors human and GPT-4 judgements. Moreover, it is capable of processing both direct assessment and pair-wise ranking formats grouped with a user-defined evaluation criteria. On four direct assessment benchmarks and four pairwise ranking benchmarks, PROMETHEUS 2 scores the highest correlation and agreement with humans and proprietary LM judges among all tested open evaluator LMs. Our models, code, and data are all publicly available 1 . | Evaluation, Agents |
| 2 May 2024 | [WILDCHAT: 1M CHATGPT INTERACTION LOGS IN THE WILD](https://arxiv.org/pdf/2405.01470) | Chatbots such as GPT-4 and ChatGPT are now serving millions of users. Despite their widespread use, there remains a lack of public datasets showcasing how these tools are used by a population of users in practice. To bridge this gap, we offered free access to ChatGPT for online users in exchange for their affirmative, consensual opt-in to anonymously collect their chat transcripts and request headers. From this, we compiled WILDCHAT, a corpus of 1 million user-ChatGPT conversations, which consists of over 2.5 million interaction turns. We compare WILDCHAT with other popular user-chatbot interaction datasets, and find that our dataset offers the most diverse user prompts, contains the largest number of languages, and presents the richest variety of potentially toxic use-cases for researchers to study. In addition to timestamped chat transcripts, we enrich the dataset with demographic data, including state, country, and hashed IP addresses, alongside request headers. This augmentation allows for more detailed analysis of user behaviors across different geographical regions and temporal dimensions. Finally, because it captures a broad range of use cases, we demonstrate the dataset’s potential utility in fine-tuning instruction-following models. WILDCHAT is released at https://wildchat.allen.ai under AI2 ImpACT Licenses1 . | Benchmark, Evaluation |
| 2 May 2024 | [STORYDIFFUSION: CONSISTENT SELF-ATTENTION FOR LONG-RANGE IMAGE AND VIDEO GENERATION](https://arxiv.org/pdf/2405.01434) | For recent diffusion-based generative models, maintaining consistent content across a series of generated images, especially those containing subjects and complex details, presents a significant challenge. In this paper, we propose a new way of self-attention calculation, termed Consistent Self-Attention, that significantly boosts the consistency between the generated images and augments prevalent pretrained diffusion-based text-to-image models in a zero-shot manner. To extend our method to long-range video generation, we further introduce a novel semantic space temporal motion prediction module, named Semantic Motion Predictor. It is trained to estimate the motion conditions between two provided images in the semantic spaces. This module converts the generated sequence of images into videos with smooth transitions and consistent subjects that are significantly more stable than the modules based on latent spaces only, especially in the context of long video generation. By merging these two novel components, our framework, referred to as StoryDiffusion, can describe a text-based story with consistent images or videos encompassing a rich variety of contents. The proposed StoryDiffusion encompasses pioneering explorations in visual story generation with the presentation of images and videos, which we hope could inspire more research from the aspect of architectural modifications. | Multimodal Models, Diffusion |
| 2 May 2024 | [FLAME : Factuality-Aware Alignment for Large Language Models](https://arxiv.org/pdf/2405.01525) | Alignment is a standard procedure to fine-tune pre-trained large language models (LLMs) to follow natural language instructions and serve as helpful AI assistants. We have observed, however, that the conventional alignment process fails to enhance the factual accuracy of LLMs, and often leads to the generation of more false facts (i.e. hallucination). In this paper, we study how to make the LLM alignment process more factual, by first identifying factors that lead to hallucination in both alignment steps: supervised fine-tuning (SFT) and reinforcement learning (RL). In particular, we find that training the LLM on new knowledge or unfamiliar texts can encourage hallucination. This makes SFT less factual as it trains on human labeled data that may be novel to the LLM. Furthermore, reward functions used in standard RL can also encourage hallucination, because it guides the LLM to provide more helpful responses on a diverse set of instructions, often preferring longer and more detailed responses. Based on these observations, we propose factuality-aware alignment (FLAME ), comprised of factuality-aware SFT and factuality-aware RL through direct preference optimization. Experiments show that our proposed factuality-aware alignment guides LLMs to output more factual responses while maintaining instruction-following capability | Alignment, Factuality |
| 2 May 2024 | [NeMo-Aligner: Scalable Toolkit for Efficient Model Alignment](https://arxiv.org/pdf/2405.01481) | Aligning Large Language Models (LLMs) with human values and preferences is essential for making them helpful and safe. However, building efficient tools to perform alignment can be challenging, especially for the largest and most competent LLMs which often contain tens or hundreds of billions of parameters. We create NeMo-Aligner, a toolkit for model alignment that can efficiently scale to using hundreds of GPUs for training. NeMo-Aligner comes with highly optimized and scalable implementations for major paradigms of model alignment such as: Reinforcement Learning from Human Feedback (RLHF), Direct Preference Optimization (DPO), SteerLM, and Self-Play Fine-Tuning (SPIN). Additionally, our toolkit supports running most of the alignment techniques in a Parameter Efficient Fine-Tuning (PEFT) setting. NeMo-Aligner is designed for extensibility, allowing support for other alignment techniques with minimal effort. It is open-sourced with Apache 2.0 License and we invite community contributions at https://github.com/NVIDIA/NeMo-Aligner. | Alignment, Toolkit |
| 1 May 2024 | [Is Bigger Edit Batch Size Always Better? - An Empirical Study on Model Editing with Llama-3](https://arxiv.org/pdf/2405.00664) | This study presents a targeted model editing analysis focused on the latest large language model, Llama-3. We explore the efficacy of popular model editing techniques - ROME, MEMIT, and EMMET, which are designed for precise layer interventions. We identify the most effective layers for targeted edits through an evaluation that encompasses up to 4096 edits across three distinct strategies: sequential editing, batch editing, and a hybrid approach we call as sequential-batch editing. Our findings indicate that increasing edit batch-sizes may degrade model performance more significantly than using smaller edit batches sequentially for equal number of edits. With this, we argue that sequential model editing is an important component for scaling model editing methods and future research should focus on methods that combine both batched and sequential editing. This observation suggests a potential limitation in current model editing methods which push towards bigger edit batch sizes, and we hope it paves way for future investigations into optimizing batch sizes and model editing performance. | Model Editing |
| 1 May 2024 | [LoRA Land: 310 Fine-tuned LLMs that Rival GPT-4, A Technical Report](https://arxiv.org/pdf/2405.00732) | Low Rank Adaptation (LoRA) has emerged as one of the most widely adopted methods for Parameter Efficient Fine-Tuning (PEFT) of Large Language Models (LLMs). LoRA reduces the number of trainable parameters and memory usage while achieving comparable performance to full fine-tuning. We aim to assess the viability of training and serving LLMs fine-tuned with LoRA in real-world applications. First, we measure the quality of LLMs fine-tuned with quantized low rank adapters across 10 base models and 31 tasks for a total of 310 models. We find that 4-bit LoRA fine-tuned models outperform base models by 34 points and GPT-4 by 10 points on average. Second, we investigate the most effective base models for fine-tuning and assess the correlative and predictive capacities of task complexity heuristics in forecasting the outcomes of fine-tuning. Finally, we evaluate the latency and concurrency capabilities of LoRAX, an open-source Multi-LoRA inference server that facilitates the deployment of multiple LoRA fine-tuned models on a single GPU using shared base model weights and dynamic adapter loading. LoRAX powers LoRA Land, a web application that hosts 25 LoRA fine-tuned Mistral-7B LLMs on a single NVIDIA A100 GPU with 80GB memory. LoRA Land highlights the quality and cost-effectiveness of employing multiple specialized LLMs over a single, general-purpose LLM. | PEFT Approaches, Fine-Tuning |

## :mortar_board: Courses

#### [Ongoing] Applied LLMs Mastery 2024

Join 1000+ students on this 10-week adventure as we delve into the application of LLMs across a variety of use cases

#### [Link](https://areganti.notion.site/Applied-LLMs-Mastery-2024-562ddaa27791463e9a1286199325045c) to the course website

##### [Feb 2024] Registrations are still open [click here](https://forms.gle/353sQMRvS951jDYu7) to register

🗓️\*Week 1 [Jan 15 2024]**\*: [Practical Introduction to LLMs](https://github.com/aishwaryanr/awesome-generative-ai-guide/blob/main/free_courses/Applied_LLMs_Mastery_2024/week1_part1_foundations.md)**

- Applied LLM Foundations
- Real World LLM Use Cases
- Domain and Task Adaptation Methods

🗓️\*Week 2 [Jan 22 2024]**\*: [Prompting and Prompt
Engineering](https://github.com/aishwaryanr/awesome-generative-ai-guide/blob/main/free_courses/Applied_LLMs_Mastery_2024/week2_prompting.md)**

- Basic Prompting Principles
- Types of Prompting
- Applications, Risks and Advanced Prompting

🗓️\*Week 3 [Jan 29 2024]**\*: [LLM Fine-tuning](https://github.com/aishwaryanr/awesome-generative-ai-guide/blob/main/free_courses/Applied_LLMs_Mastery_2024/week3_finetuning_llms.md)**

- Basics of Fine-Tuning
- Types of Fine-Tuning
- Fine-Tuning Challenges

🗓️\*Week 4 [Feb 5 2024]**\*: [RAG (Retrieval-Augmented Generation)](https://github.com/aishwaryanr/awesome-generative-ai-guide/blob/main/free_courses/Applied_LLMs_Mastery_2024/week4_RAG.md)**

- Understanding the concept of RAG in LLMs
- Key components of RAG
- Advanced RAG Methods

🗓️\*Week 5 [ Feb 12 2024]**\*: [Tools for building LLM Apps](https://github.com/aishwaryanr/awesome-generative-ai-guide/blob/main/free_courses/Applied_LLMs_Mastery_2024/week5_tools_for_LLM_apps.md)**

- Fine-tuning Tools
- RAG Tools
- Tools for observability, prompting, serving, vector search etc.

🗓️\*Week 6 [Feb 19 2024]**\*: [Evaluation Techniques](https://github.com/aishwaryanr/awesome-generative-ai-guide/blob/main/free_courses/Applied_LLMs_Mastery_2024/week6_llm_evaluation.md)**

- Types of Evaluation
- Common Evaluation Benchmarks
- Common Metrics

🗓️\*Week 7 [Feb 26 2024]**\*: [Building Your Own LLM Application](https://github.com/aishwaryanr/awesome-generative-ai-guide/blob/main/free_courses/Applied_LLMs_Mastery_2024/week7_build_llm_app.md)**

- Components of LLM application
- Build your own LLM App end to end

🗓️\*Week 8 [March 4 2024]**\*: [Advanced Features and Deployment](https://github.com/aishwaryanr/awesome-generative-ai-guide/blob/main/free_courses/Applied_LLMs_Mastery_2024/week8_advanced_features.md)**

- LLM lifecycle and LLMOps
- LLM Monitoring and Observability
- Deployment strategies

🗓️\*Week 9 [March 11 2024]**\*: [Challenges with LLMs](https://github.com/aishwaryanr/awesome-generative-ai-guide/blob/main/free_courses/Applied_LLMs_Mastery_2024/week9_challenges_with_llms.md)**

- Scaling Challenges
- Behavioral Challenges
- Future directions

🗓️\*Week 10 [March 18 2024]**\*: [Emerging Research Trends](https://github.com/aishwaryanr/awesome-generative-ai-guide/blob/main/free_courses/Applied_LLMs_Mastery_2024/week10_research_trends.md)**

- Smaller and more performant models
- Multimodal models
- LLM Alignment

🗓️*Week 11 *Bonus\* [March 25 2024]**\*: [Foundations](https://github.com/aishwaryanr/awesome-generative-ai-guide/blob/main/free_courses/Applied_LLMs_Mastery_2024/week11_foundations.md)**

- Generative Models Foundations
- Self-Attention and Transformers
- Neural Networks for Language

---

#### :book: List of Free GenAI Courses

##### LLM Basics and Foundations

1. [Large Language Models](https://rycolab.io/classes/llm-s23/) by ETH Zurich

2. [Understanding Large Language Models](https://www.cs.princeton.edu/courses/archive/fall22/cos597G/) by Princeton

3. [Transformers course](https://huggingface.co/learn/nlp-course/chapter1/1) by Huggingface

4. [NLP course](https://huggingface.co/learn/nlp-course/chapter1/1) by Huggingface

5. [CS324 - Large Language Models](https://stanford-cs324.github.io/winter2022/) by Stanford

6. [Generative AI with Large Language Models](https://www.coursera.org/learn/generative-ai-with-llms) by Coursera

7. [Introduction to Generative AI](https://www.coursera.org/learn/introduction-to-generative-ai) by Coursera

8. [Generative AI Fundamentals](https://www.cloudskillsboost.google/paths/118/course_templates/556) by Google Cloud

9. [Introduction to Large Language Models](https://www.cloudskillsboost.google/paths/118/course_templates/539) by Google Cloud
10. [Introduction to Generative AI](https://www.cloudskillsboost.google/paths/118/course_templates/536) by Google Cloud
11. [Generative AI Concepts](https://www.datacamp.com/courses/generative-ai-concepts) by DataCamp (Daniel Tedesco Data Lead @ Google)
12. [1 Hour Introduction to LLM (Large Language Models)](https://www.youtube.com/watch?v=xu5_kka-suc) by WeCloudData
13. [LLM Foundation Models from the Ground Up | Primer](https://www.youtube.com/watch?v=W0c7jQezTDw&list=PLTPXxbhUt-YWjMCDahwdVye8HW69p5NYS) by Databricks
14. [Generative AI Explained](https://courses.nvidia.com/courses/course-v1:DLI+S-FX-07+V1/) by Nvidia
15. [Transformer Models and BERT Model](https://www.cloudskillsboost.google/course_templates/538) by Google Cloud
16. [Generative AI Learning Plan for Decision Makers](https://explore.skillbuilder.aws/learn/public/learning_plan/view/1909/generative-ai-learning-plan-for-decision-makers) by AWS
17. [Introduction to Responsible AI](https://www.cloudskillsboost.google/course_templates/554) by Google Cloud
18. [Fundamentals of Generative AI](https://learn.microsoft.com/en-us/training/modules/fundamentals-generative-ai/) by Microsoft Azure
19. [Generative AI for Beginners](https://github.com/microsoft/generative-ai-for-beginners?WT.mc_id=academic-122979-leestott) by Microsoft
20. [ChatGPT for Beginners: The Ultimate Use Cases for Everyone](https://www.udemy.com/course/chatgpt-for-beginners-the-ultimate-use-cases-for-everyone/) by Udemy
21. [[1hr Talk] Intro to Large Language Models](https://www.youtube.com/watch?v=zjkBMFhNj_g) by Andrej Karpathy
22. [ChatGPT for Everyone](https://learnprompting.org/courses/chatgpt-for-everyone) by Learn Prompting
23. [Large Language Models (LLMs) (In English)](https://www.youtube.com/playlist?list=PLxlkzujLkmQ9vMaqfvqyfvZV_o8EqjAk7) by Kshitiz Verma (JK Lakshmipat University, Jaipur, India)

##### Building LLM Applications

1. [LLMOps: Building Real-World Applications With Large Language Models](https://www.udacity.com/course/building-real-world-applications-with-large-language-models--cd13455) by Udacity

2. [Full Stack LLM Bootcamp](https://fullstackdeeplearning.com/llm-bootcamp/) by FSDL

3. [Generative AI for beginners](https://github.com/microsoft/generative-ai-for-beginners/tree/main) by Microsoft

4. [Large Language Models: Application through Production](https://www.edx.org/learn/computer-science/databricks-large-language-models-application-through-production) by Databricks

5. [Generative AI Foundations](https://www.youtube.com/watch?v=oYm66fHqHUM&list=PLhr1KZpdzukf-xb0lmiU3G89GJXaDbAIF) by AWS

6. [Introduction to Generative AI Community Course](https://www.youtube.com/watch?v=ajWheP8ZD70&list=PLmQAMKHKeLZ-iTT-E2kK9uePrJ1Xua9VL) by ineuron

7. [LLM University](https://docs.cohere.com/docs/llmu) by Cohere
8. [LLM Learning Lab](https://lightning.ai/pages/llm-learning-lab/) by Lightning AI

9. [Functions, Tools and Agents with LangChain](https://learn.deeplearning.ai/functions-tools-agents-langchain) by Deeplearning.AI

10. [LangChain for LLM Application Development](https://learn.deeplearning.ai/login?redirect_course=langchain&callbackUrl=https%3A%2F%2Flearn.deeplearning.ai%2Fcourses%2Flangchain) by Deeplearning.AI

11. [LLMOps](https://learn.deeplearning.ai/llmops) by DeepLearning.AI

12. [Automated Testing for LLMOps](https://learn.deeplearning.ai/automated-testing-llmops) by DeepLearning.AI
13. [Building RAG Agents with LLMs](https://courses.nvidia.com/courses/course-v1:DLI+S-FX-15+V1/) by Nvidia
14. [Building Generative AI Applications Using Amazon Bedrock](https://explore.skillbuilder.aws/learn/course/external/view/elearning/17904/building-generative-ai-applications-using-amazon-bedrock-aws-digital-training) by AWS
15. [Efficiently Serving LLMs](https://learn.deeplearning.ai/courses/efficiently-serving-llms/lesson/1/introduction) by DeepLearning.AI
16. [Building Systems with the ChatGPT API](https://www.deeplearning.ai/short-courses/building-systems-with-chatgpt/) by DeepLearning.AI
17. [Serverless LLM apps with Amazon Bedrock](https://www.deeplearning.ai/short-courses/serverless-llm-apps-amazon-bedrock/) by DeepLearning.AI
18. [Building Applications with Vector Databases](https://www.deeplearning.ai/short-courses/building-applications-vector-databases/) by DeepLearning.AI
19. [Automated Testing for LLMOps](https://www.deeplearning.ai/short-courses/automated-testing-llmops/) by DeepLearning.AI
20. [LLMOps](https://www.deeplearning.ai/short-courses/llmops/) by DeepLearning.AI
21. [Build LLM Apps with LangChain.js](https://www.deeplearning.ai/short-courses/build-llm-apps-with-langchain-js/) by DeepLearning.AI
22. [Advanced Retrieval for AI with Chroma](https://www.deeplearning.ai/short-courses/advanced-retrieval-for-ai/) by DeepLearning.AI
23. [Operationalizing LLMs on Azure](https://www.coursera.org/learn/llmops-azure) by Coursera
24. [Generative AI Full Course – Gemini Pro, OpenAI, Llama, Langchain, Pinecone, Vector Databases & More](https://www.youtube.com/watch?v=mEsleV16qdo) by freeCodeCamp.org
25. [Training & Fine-Tuning LLMs for Production](https://learn.activeloop.ai/courses/llms) by Activeloop

##### Prompt Engineering, RAG and Fine-Tuning

1. [LangChain & Vector Databases in Production](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbVhnQW8xNDdhSU9IUDVLXzFhV2N0UkNRMkZrQXxBQ3Jtc0traUxHMzZJcGJQYjlyckYxaGxYVWlsOFNGUFlFVEdhNzdjTWpPUlQ2TF9XczRqNkxMVGpJTnd5YmYzV0prQ0IwZURNcHhIZ3h1Z051VTl5MXBBLUN0dkM0NHRkQTFua1Jpc0VCRFJUb0ZQZG95b0JqMA&q=https%3A%2F%2Flearn.activeloop.ai%2Fcourses%2Flangchain&v=gKUTDC13jys) by Activeloop

2. [Reinforcement Learning from Human Feedback](https://learn.deeplearning.ai/reinforcement-learning-from-human-feedback) by DeepLearning.AI

3. [Building Applications with Vector Databases](https://learn.deeplearning.ai/building-applications-vector-databases) by DeepLearning.AI

4. [Finetuning Large Language Models](https://learn.deeplearning.ai/finetuning-large-language-models) by Deeplearning.AI
5. [LangChain: Chat with Your Data](http://learn.deeplearning.ai/langchain-chat-with-your-data/) by Deeplearning.AI

6. [Building Systems with the ChatGPT API](https://learn.deeplearning.ai/chatgpt-building-system) by Deeplearning.AI
7. [Prompt Engineering with Llama 2](https://www.deeplearning.ai/short-courses/prompt-engineering-with-llama-2/) by Deeplearning.AI
8. [Building Applications with Vector Databases](https://learn.deeplearning.ai/building-applications-vector-databases) by Deeplearning.AI
9. [ChatGPT Prompt Engineering for Developers](https://learn.deeplearning.ai/chatgpt-prompt-eng/lesson/1/introduction) by Deeplearning.AI
10. [Advanced RAG Orchestration series](https://www.youtube.com/watch?v=CeDS1yvw9E4) by LlamaIndex
11. [Prompt Engineering Specialization](https://www.coursera.org/specializations/prompt-engineering) by Coursera
12. [Augment your LLM Using Retrieval Augmented Generation](https://courses.nvidia.com/courses/course-v1:NVIDIA+S-FX-16+v1/) by Nvidia
13. [Knowledge Graphs for RAG](https://www.deeplearning.ai/short-courses/knowledge-graphs-rag/) by Deeplearning.AI
14. [Open Source Models with Hugging Face](https://www.deeplearning.ai/short-courses/open-source-models-hugging-face/) by Deeplearning.AI
15. [Vector Databases: from Embeddings to Applications](https://www.deeplearning.ai/short-courses/vector-databases-embeddings-applications/) by Deeplearning.AI
16. [Understanding and Applying Text Embeddings](https://www.deeplearning.ai/short-courses/google-cloud-vertex-ai/) by Deeplearning.AI
17. [JavaScript RAG Web Apps with LlamaIndex](https://www.deeplearning.ai/short-courses/javascript-rag-web-apps-with-llamaindex/) by Deeplearning.AI
18. [Quantization Fundamentals with Hugging Face](https://www.deeplearning.ai/short-courses/quantization-fundamentals-with-hugging-face/) by Deeplearning.AI
19. [Preprocessing Unstructured Data for LLM Applications](https://www.deeplearning.ai/short-courses/preprocessing-unstructured-data-for-llm-applications/) by Deeplearning.AI
20. [Retrieval Augmented Generation for Production with LangChain & LlamaIndex](https://learn.activeloop.ai/courses/rag) by Activeloop
21. [Quantization in Depth](https://www.deeplearning.ai/short-courses/quantization-in-depth/) by Deeplearning.AI

##### Evaluation

1. [Building and Evaluating Advanced RAG Applications](https://learn.deeplearning.ai/building-evaluating-advanced-rag) by DeepLearning.AI
2. [Evaluating and Debugging Generative AI Models Using Weights and Biases](https://learn.deeplearning.ai/evaluating-debugging-generative-ai) by Deeplearning.AI
3. [Quality and Safety for LLM Applications](https://www.deeplearning.ai/short-courses/quality-safety-llm-applications/) by Deeplearning.AI
4. [Red Teaming LLM Applications](https://www.deeplearning.ai/short-courses/red-teaming-llm-applications/?utm_campaign=giskard-launch&utm_medium=headband&utm_source=dlai-homepage) by Deeplearning.AI

##### Multimodal

1. [How Diffusion Models Work](https://www.deeplearning.ai/short-courses/how-diffusion-models-work/) by DeepLearning.AI
2. [How to Use Midjourney, AI Art and ChatGPT to Create an Amazing Website](https://www.youtube.com/watch?v=5wdCev86RYE) by Brad Hussey
3. [Build AI Apps with ChatGPT, DALL-E and GPT-4](https://scrimba.com/learn/buildaiapps) by Scrimba
4. [11-777: Multimodal Machine Learning](https://www.youtube.com/playlist?list=PL-Fhd_vrvisNM7pbbevXKAbT_Xmub37fA) by Carnegie Mellon University

#### Miscellaneous

1. [Avoiding AI Harm](https://www.coursera.org/learn/avoiding-ai-harm) by Coursera
2. [Developing AI Policy](https://www.coursera.org/learn/developing-ai-policy) by Coursera

---

## :paperclip: Resources

- [ICLR 2024 Paper Summaries](https://areganti.notion.site/06f0d4fe46a94d62bff2ae001cfec22c?v=d501ca62e4b745768385d698f173ae14)

---

## :computer: Interview Prep

#### Topic wise Questions:

1. [Common GenAI Interview Questions](https://github.com/aishwaryanr/awesome-generative-ai-guide/blob/main/interview_prep/60_gen_ai_questions.md)
2. Prompting and Prompt Engineering
3. Model Fine-Tuning
4. Model Evaluation
5. MLOps for GenAI
6. Generative Models Foundations
7. Latest Research Trends

#### GenAI System Design (Coming Soon):

1. Designing an LLM-Powered Search Engine
2. Building a Customer Support Chatbot
3. Building a system for natural language interaction with your data.
4. Building an AI Co-pilot
5. Designing a Custom Chatbot for Q/A on Multimodal Data (Text, Images, Tables, CSV Files)
6. Building an Automated Product Description and Image Generation System for E-commerce

---

## :notebook: Code Notebooks

#### RAG Tutorials

- [AWS Bedrock Workshop Tutorials](https://github.com/aws-samples/amazon-bedrock-workshop) by Amazon Web Services
- [Langchain Tutorials](https://github.com/gkamradt/langchain-tutorials) by gkamradt
- [LLM Applications for production](https://github.com/ray-project/llm-applications/tree/main) by ray-project
- [LLM tutorials](https://github.com/ollama/ollama/tree/main/examples) by Ollama
- [LLM Hub](https://github.com/mallahyari/llm-hub) by mallahyari

#### Fine-Tuning Tutorials

- [LLM Fine-tuning tutorials](https://github.com/ashishpatel26/LLM-Finetuning) by ashishpatel26
- [PEFT](https://github.com/huggingface/peft/tree/main/examples) example notebooks by Huggingface
- [Free LLM Fine-Tuning Notebooks](https://levelup.gitconnected.com/14-free-large-language-models-fine-tuning-notebooks-532055717cb7) by Youssef Hosni


#### Comprehensive LLM Code Repositories 
- [LLM-PlayLab](https://github.com/Sakil786/LLM-PlayLab) This playlab encompasses a multitude of projects crafted through the utilization of Transformer Models


---

## :black_nib: Contributing

If you want to add to the repository or find any issues, please feel free to raise a PR and ensure correct placement within the relevant section or category.

---

## :pushpin: Cite Us

To cite this guide, use the below format:

```
@article{areganti_generative_ai_guide,
author = {Reganti, Aishwarya Naresh},
journal = {https://github.com/aishwaryanr/awesome-generative-ai-resources},
month = {01},
title = {{Generative AI Guide}},
year = {2024}
}
```

## License

[MIT License]
