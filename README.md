# Hi, I'm Pengfei He 👋

<p align="justify">I am an M.S. student at the University of Electronic Science and Technology of China (UESTC), with a background in communication systems, systems programming, and applied AI. I work with C/C++, Python, Linux, CUDA, and C++ inference runtimes. I am currently an <strong>LLM Inference Engine Intern at Enflame Technology</strong>&nbsp;<a href="https://www.enflame-tech.com/"><img src="https://www.enflame-tech.com/favicon.ico" width="24" height="24" alt="Enflame Technology logo"></a>.</p>

## Research Focus

<p align="justify">My research focuses on <strong>collaborative inference and scheduling optimization for small language models of different scales in resource-constrained edge environments</strong>. With a communication-systems background, I am particularly interested in the system-level trade-offs among inference latency, resource utilization, communication cost, and service quality.</p>

<p align="justify">In parallel, my engineering work focuses on LLM inference infrastructure: runtime adaptation, serving and scheduling, KV cache management, CUDA/Triton kernels, profiling, and C++ edge deployment. I am currently applying these skills to inference optimization on domestic AI accelerators.</p>

## Selected Projects

| Project | Description |
| --- | --- |
| [LLM-Serve](https://github.com/HGinkgo/LLM-Serve) | A single-node LLM inference runtime exploring Paged KV Cache, continuous batching, chunked prefill, admission control, CUDA Graph, speculative decoding, AWQ quantization, and experimental dual-GPU Prefill/Decode separation with shared-KV transport. |
| [HunyuanOCR-ncnn](https://github.com/HGinkgo/HunyuanOCR-ncnn) | A pure C++17 runtime for HunyuanOCR 1.5 using pnnx and ncnn, with dynamic vision input, KV-cache decoding, JSONL batching, CPU/Vulkan backends, and dimension-aware GEMM/GEMV routing. |
| [SeedVR2-ncnn](https://github.com/HGinkgo/SeedVR2-ncnn) | An in-progress C++/ncnn implementation of SeedVR2 for portable image and video super-resolution, with CPU and Vulkan build paths. |
| [LLM-Kernels](https://github.com/HGinkgo/LLM-Kernels) | CUDA and Triton implementations of LLM inference operators with correctness tests, benchmarks, profiling, and optimization notes. |
| [riscv-memcpy-memset-opt](https://github.com/HGinkgo/riscv-memcpy-memset-opt) | RV64GC `memcpy` and `memset` optimizations using scalar unrolling, RVV 1.0, and Zicboz. |

## Open Source Contributions

| Community | Contributions |
| --- | --- |
| <img src="https://github.com/kvcache-ai.png?size=40" width="20" alt="Mooncake logo"> **[Mooncake](https://github.com/kvcache-ai/Mooncake)** | Contributed Mooncake Store allocator benchmarking and size-class-aware allocation strategy work, including a [merged fragmentation benchmark](https://github.com/kvcache-ai/Mooncake/pull/2340) and a [size-class-aware strategy contribution](https://github.com/kvcache-ai/Mooncake/pull/2445). |
| <img src="https://github.com/Tencent.png?size=40" width="20" alt="Tencent logo"> **[ncnn](https://github.com/Tencent/ncnn)** | Develop and maintain [HunyuanOCR-ncnn](https://github.com/HGinkgo/HunyuanOCR-ncnn), a community implementation for deploying Tencent HunyuanOCR 1.5 through the pnnx/ncnn toolchain. See the [technical report](https://github.com/Tencent/ncnn/discussions/6808) for the migration and multi-platform deployment details. |
