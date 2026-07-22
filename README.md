# Hi, I'm Pengfei He 👋

I am an M.S. student at the University of Electronic Science and Technology of China (UESTC). My background spans systems programming and applied AI, with hands-on experience in C/C++, Python, Linux, deep learning, and LLM inference. I am currently focusing on LLM inference runtimes, model serving and scheduling, GPU kernels, and edge deployment.

## Research Focus

My current research focuses on **collaborative inference and scheduling optimization for small language models of different scales in resource-constrained edge environments**. I am particularly interested in system-level trade-offs among inference latency, resource utilization, and service quality.

## Selected Projects

| Project | Description |
| --- | --- |
| [LLM-Serve](https://github.com/HGinkgo/LLM-Serve) | A single-GPU LLM inference runtime exploring Paged KV Cache, continuous batching, chunked prefill, serving benchmarks, and EAGLE-style speculative decoding. |
| [HunyuanOCR-ncnn](https://github.com/HGinkgo/HunyuanOCR-ncnn) | A pure C++17 runtime for deploying HunyuanOCR 1.5 with pnnx and ncnn, with optional Vulkan acceleration for the vision encoder. |
| [llm-infer-kernels](https://github.com/HGinkgo/llm-infer-kernels) | CUDA and Triton implementations of common LLM inference operators with correctness tests, benchmarks, and optimization notes. |
| [riscv-memcpy-memset-opt](https://github.com/HGinkgo/riscv-memcpy-memset-opt) | RV64GC `memcpy` and `memset` optimizations using scalar unrolling, RVV 1.0, and Zicboz. |

## Open Source Contributions

| Community | Contributions |
| --- | --- |
| <img src="https://github.com/kvcache-ai.png?size=40" width="20" alt="Mooncake logo"> **[Mooncake](https://github.com/kvcache-ai/Mooncake)** | Contributed allocator benchmarking and optimization work, including a [merged size-class allocator fragmentation benchmark](https://github.com/kvcache-ai/Mooncake/pull/2340) and an [ongoing size-class-aware allocation strategy](https://github.com/kvcache-ai/Mooncake/pull/2445). |
| <img src="https://github.com/Tencent.png?size=40" width="20" alt="Tencent logo"> **[ncnn](https://github.com/Tencent/ncnn)** | Develop and maintain [HunyuanOCR-ncnn](https://github.com/HGinkgo/HunyuanOCR-ncnn), a community implementation for deploying Tencent HunyuanOCR 1.5 through the pnnx/ncnn toolchain. |
