# Library

A running library of resources I want to study across AI systems, LLM inference, infrastructure, and related topics.

## LLM inference & serving

### Recommended reading order

1. **NVIDIA — LLM Inference Benchmarking: Fundamental Concepts**  
   Start here for latency, throughput, TTFT, inter-token latency, batching, and benchmarking basics.  
   https://developer.nvidia.com/blog/llm-inference-benchmarking-fundamental-concepts/

2. **Kipply — Transformer Inference Arithmetic**  
   Useful for building intuition around FLOPs, memory bandwidth, KV cache, batch size, and inference bottlenecks.  
   https://kipply.github.io/blog/transformer-inference-arithmetic/

3. **NVIDIA — Mastering LLM Techniques: Inference Optimization**  
   Covers prefill vs. decode, KV caching, model parallelism, attention optimizations, and serving efficiency.  
   https://developer.nvidia.com/blog/mastering-llm-techniques-inference-optimization/

4. **avichawla — KV Cache Engineering Practices in LLM Serving**  
   Focus: KV-cache engineering and serving-system tradeoffs.  
   _Original link to add._

5. **Anyscale — Continuous Batching and LLM Inference**  
   How continuous batching can substantially improve inference throughput while reducing latency.  
   https://www.anyscale.com/blog/continuous-batching-llm-inference

   Benchmark code:  
   https://github.com/anyscale/llm-continuous-batching-benchmarks

6. **Aleksa Gordić — Inside vLLM: Anatomy of a High-Throughput LLM Inference System**  
   Deep dive into vLLM internals: scheduling, PagedAttention, batching, caching, speculative decoding, and distributed serving.  
   https://www.aleksagordic.com/blog/vllm

   vLLM version:  
   https://vllm.ai/blog/2025-09-05-anatomy-of-vllm

## AI infrastructure / industry

7. **51bodila — 赚到了钱？守住它才是关键。**  
   _Original link to add._

8. **jiewangsss — Neocloud 行业深度研究：ORCL · CRWV · NBIS · IREN**  
   _Original link to add._

## Podcast

- **狂飙的智能体：博通专用集成电路与人工智能前沿地带**  
  _Original episode link to add._

## Suggested study path

`Benchmarking fundamentals → Transformer inference arithmetic → NVIDIA inference optimization → KV cache → Continuous batching → vLLM internals`

The goal is to first build a systems-level mental model, then revisit the advanced material after actually serving a model with vLLM.
