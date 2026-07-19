# Awesome-DiT-Accelerations

A list of awesome dit projects and papers for dit accelerations.

## Contents
- [Open Source Projects](#section1)
  - [Video Generation Models](#section1_video_generation_models)
  - [DiT Accelerations](#section1_dit_accelerations)
- [Papers](#section2)
  - [Survey](#section2_survey)
  - [AR-Diffusion](#section2_ar_diffusion)
  - [Sparse Attention](#section2_sparse_attention)
  - [Quantization](#section2_quantization)
  - [KV-Cache](#section2_kv_cache)
- [Tutorials & Blogs](#section3)

## Open Source Projects<a id="section1"></a>

### Video Generation Models<a id="section1_video_generation_models"></a>
- [Mochi 1](https://www.genmo.ai/blog/mochi-1-a-new-sota-in-open-text-to-video) by Genmo
- [Wan](https://wan.video/) by Alibaba
- [Hunyuan](https://hunyuan.tencent.com/) by Tencent
- [CogVideoX](https://github.com/zai-org/CogVideo) by Zhipu AI
- [Open-Sora-Plan](https://github.com/PKU-YuanGroup/Open-Sora-Plan) by PKU
- [Open-Sora](https://github.com/hpcaitech/Open-Sora) by Colossal-AI
- [HY-WorldPlay](https://github.com/Tencent-Hunyuan/HY-WorldPlay) by Tencent
- [Lingbot-world](https://github.com/robbyant/lingbot-world) by Robbyant

### DiT Accelerations<a id="section1_dit_accelerations"></a>
- [xDiT: an Inference Engine for Diffusion Transformers (DiTs) with Massive Parallelism](https://github.com/xdit-project/xDiT)
- [USP: A Unified Sequence Parallelism Approach for Long Context Generative AI](https://github.com/feifeibear/long-context-attention) by Tencent

## Papers<a id="section2"></a>

### Survey<a id="section2_survey"></a>
- [Unveiling Redundancy in Diffusion Transformers (DiTs): A Systematic Study](https://arxiv.org/abs/2411.13588) by Tencent, arXiv 2024
- [A White Paper on Neural Network Quantization](https://arxiv.org/abs/2106.08295), by Nagel, Markus, et al., arXiv 2021

### AR-Diffusion<a id="section2_ar_diffusion"></a>
- [TiDAR: Think in Diffusion, Talk in Autoregression](https://arxiv.org/abs/2511.08923) by NVIDIA, arXiv 2025
- [AR-Diffusion: Asynchronous Video Generation with Auto-Regressive Diffusion](https://arxiv.org/abs/2503.07418) by Bytedance Inc., CVPR 2025
- [From Slow Bidirectional to Fast Autoregressive Video Diffusion Models](https://arxiv.org/abs/2412.07772) by MIT, CVPR 2025
- [Ca2-VDM: Efficient Autoregressive Video Diffusion Model with Causal Generation and Cache Sharing](https://arxiv.org/abs/2411.16375) by Gao, Kaifeng, et al., ICML 2025

### Sparse Attention<a id="section2_sparse_attention"></a>
- [Fast Video Generation with Sliding Tile Attention](https://arxiv.org/abs/2502.04507) by Zhang, Peiyuan, et al., ICML 2026
- [Radial Attention: $O(n \log n)$ Sparse Attention with Energy Decay for Long Video Generation](https://arxiv.org/abs/2506.19852) by Li, Xingyang, et al., NeurIPS 2025
- [XAttention: Block Sparse Attention with Antidiagonal Scoring](https://arxiv.org/abs/2503.16428) by Xu, Ruyi, et al., ICML 2025
- [SLA: Beyond Sparsity in Diffusion Transformers via Fine-Tunable Sparse-Linear Attention](https://arxiv.org/abs/2509.24006) by Zhang, Jintao, et al., arXiv 2025
- [Sparse VideoGen: Accelerating Video Diffusion Transformers with Spatial-Temporal Sparsity](https://arxiv.org/abs/2502.01776) by Xi, Haocheng, et al., ICML 2025
- [Sparse VideoGen2: Accelerate Video Generation with Sparse Attention via Semantic-Aware Permutation](https://arxiv.org/abs/2502.01776) by Yang, Shuo, et al., NeurIPS 2025

### Quantization<a id="section2_quantization"></a>
- [Q-ARVD: Quantizing Autoregressive Video Diffusion Models](https://arxiv.org/abs/2605.21072) by Tang, Siao, et al., arXiv 2026
- [RotateAttention: RoPE-Aware Rotation and Range Rectification for INT4 Quantized Attention in Video Generation](https://arxiv.org/abs/2607.02584) by Liu, Yaofu, et al., arXiv 2026
- [OrbitQuant: Data-Agnostic Quantization for Image and Video Diffusion Transformers](https://arxiv.org/pdf/2607.02461) by Lee, Donghyun, et al., arXiv 2026
- [SpecQuant: Spectral Decomposition and Adaptive Truncation for Ultra-Low-Bit LLMs Quantization](https://arxiv.org/abs/2511.11663) by Zhao, Zhixiong, et al., AAAI 2026
- [SemanticDialect: Semantic-Aware Mixed-Format Quantization for Video Diffusion Transformers](https://arxiv.org/abs/2603.02883) by Jang, Wonsuk, and Thierry Tambe., arXiv 2026
- [PAROAttention: Pattern-Aware ReOrdering for Efficient Sparse and Quantized Attention in Visual Generation Models](https://arxiv.org/abs/2506.16054) by Zhao, Tianchen, et al., arXiv 2025
- [SageAttention: Accurate 8-Bit Attention for Plug-and-play Inference Acceleration](https://arxiv.org/abs/2410.02367) by Zhang, Jintao, et al., ICLR 2025
- [SageAttention2: Efficient Attention with Thorough Outlier Smoothing and Per-thread INT4 Quantization](https://arxiv.org/abs/2411.10958) by Zhang, Jintao, et al., ICML 2025
- [SageAttention3: Microscaling FP4 Attention for Inference and An Exploration of 8-Bit Training](https://arxiv.org/abs/2505.11594) by Zhang, Jintao, et al., NeurIPS 2025
- [SVDQuant: Absorbing Outliers by Low-Rank Component for 4-Bit Diffusion Models](https://iclr.cc/virtual/2025/poster/27906) by Li, Muyang, et al., ICLR 2025
- [TurboAttention: Efficient Attention Approximation For High Throughputs LLMs](https://arxiv.org/abs/2412.08585) by Kang, Hao, et al., PMLS 2025
- [Vidit-q: Efficient and accurate quantization of diffusion transformers for image and video generation](https://iclr.cc/virtual/2025/poster/30429) by Zhao, Tianchen, et al., ICLR 2025
- [DGQ: Distribution-Aware Group Quantization for Text-to-Image Diffusion Models](https://iclr.cc/virtual/2025/poster/29192) by Ryu, Hyogon, NaHyeon Park, and Hyunjung Shim., ICLR 2025
- [DMQ: Dissecting Outliers of Diffusion Models for Post-Training Quantization](https://arxiv.org/abs/2507.12933) by Lee, Dongyeun, et al., ICCV 2025
- [PTQ4DiT: Post-training Quantization for Diffusion Transformers](https://nips.cc/virtual/2024/poster/95445) by Wu, Junyi, et al., NeurIPS 2024

### KV Cache<a id="section2_kv_cache"></a>
- [OScaR: The Occam's Razor for Extreme KV Cache Quantization in LLMs and Beyond](https://arxiv.org/abs/2605.19660) by Su, Zunhai, et al., arXiv 2026
- [TriAttention: Efficient Long Reasoning with Trigonometric KV Compression](https://arxiv.org/abs/2604.04921) by Mao, Weian, et al., arXiv 2026
- [Resonating with RoPE: Spectral Quantization for High-Fidelity Key Cache Compression](https://2026.aclweb.org/program/accepted_papers/) by Wang, Xuefeng, et al., ACL 2026
- [PolarQuant: Leveraging Polar Transformation for Efficient Key Cache Quantization and Decoding Acceleration](https://arxiv.org/abs/2502.00527) by Han, Insu, et al., arXiv 2025
- [SpinQuant: LLM quantization with learned rotations](https://arxiv.org/abs/2405.16406) by Liu, Zechun, et al., ICLR 2025
- [AKVQ-VL: Attention-Aware KV Cache Adaptive 2-Bit Quantization for Vision-Language Models](https://arxiv.org/abs/2501.15021) by Su, Zunhai, et al., arXiv 2025
- [PM-KVQ: Progressive Mixed-precision KV Cache Quantization for Long-CoT LLMs](https://arxiv.org/abs/2505.18610) by Liu, Tengxuan, et al., arXiv 2025
- [DuoAttention: Efficient Long-Context LLM Inference with Retrieval and Streaming Heads](https://arxiv.org/abs/2410.10819) by Xiao, Guangxuan, et al., ICLR 2025
- [KVQuant: Towards 10 Million Context Length LLM Inference with KV Cache Quantization](https://arxiv.org/abs/2401.18079) by Hooper, Coleman, et al., NeurIPS 2024
- [ZipCache: Accurate and Efficient KV Cache Quantization with Salient Token Identification](https://arxiv.org/abs/2405.14256) by He, Yefei, et al., NeurIPS 2024
- [No Token Left Behind: Reliable KV Cache Compression via Importance-Aware Mixed Precision Quantization](https://arxiv.org/abs/2402.18096) by Yang, June Yong, et al., arXiv 2024

## Tutorials & Blogs<a id="section3"></a>
- [TinyML and Efficient Deep Learning Computing](https://hanlab.mit.edu/courses/2023-fall-65940)
