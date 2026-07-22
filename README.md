# Hi, I'm Pengfei He

I am an M.S. student at the University of Electronic Science and Technology of China (UESTC). My background spans systems programming and applied AI, with hands-on experience in C/C++, Python, Linux, deep learning, and LLM inference. I am currently focusing on LLM inference runtimes, model serving and scheduling, GPU kernels, and edge deployment.

## Research Focus

My current research focuses on **collaborative inference and scheduling optimization for small language models of different scales in resource-constrained edge environments**. I am particularly interested in system-level trade-offs among inference latency, resource utilization, and service quality.

## Selected Projects

| Project | Description |
| --- | --- |
| [LLM-Serve](https://github.com/HGinkgo/LLM-Serve) | A single-GPU LLM inference runtime featuring Paged KV Cache, continuous batching, chunked prefill, serving benchmarks, and EAGLE-style speculative decoding. On Qwen3-8B with a 24 GB GPU, EAGLE improved output throughput by **1.20x at batch size 1** and **1.34x at batch size 4** in the published benchmark configuration. |
| [HunyuanOCR-ncnn](https://github.com/HGinkgo/HunyuanOCR-ncnn) | A pure C++17 inference runtime for HunyuanOCR 1.5 built with pnnx and ncnn. It implements model conversion, dynamic vision processing, prompt construction, KV-cache decoding, tokenizer post-processing, JSONL batch inference, and optional Vulkan acceleration for the vision encoder. |
| [llm-infer-kernels](https://github.com/HGinkgo/llm-infer-kernels) | A CUDA and Triton learning repository for LLM inference operators. Current implementations cover reductions, Softmax, matrix transpose, RMSNorm, and LayerNorm, with correctness references, benchmarks, and iterative optimization notes. |
| [riscv-memcpy-memset-opt](https://github.com/HGinkgo/riscv-memcpy-memset-opt) | Benchmark-driven `memcpy` and `memset` optimization for RV64GC using scalar unrolling, RVV 1.0, and Zicboz, evaluated with GLIBC 2.43 benchtests. |

### Additional Systems Experience

I have also participated in the hardware-software integration of an **airborne mobile ad hoc networking system** on a RISC-V embedded platform, covering embedded software development, platform adaptation, system integration, and communication-systems engineering.

## Open Source Contributions

- **[Mooncake](https://github.com/kvcache-ai/Mooncake)**: contributed allocator benchmarking and optimization work, including a [merged size-class allocator fragmentation benchmark](https://github.com/kvcache-ai/Mooncake/pull/2340) and an [ongoing size-class-aware allocation strategy](https://github.com/kvcache-ai/Mooncake/pull/2445).
- **ncnn ecosystem**: developed and maintain [HunyuanOCR-ncnn](https://github.com/HGinkgo/HunyuanOCR-ncnn) as a community implementation for deploying Tencent HunyuanOCR 1.5 through the pnnx/ncnn toolchain.
