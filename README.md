<div align="center">
  <img
    src="./assets/typing-intro.svg"
    alt="Hi, I'm Guangli Liu. AI Infra and LLM Inference Optimization."
    width="100%"
  />

  <p>
    I build and optimize LLM inference systems, from GPU kernels and KV-cache-aware scheduling<br/>
    to multi-GPU serving and speculative decoding.
  </p>

  <p>
    <code>LLM Serving</code>
    <code>Triton Kernels</code>
    <code>Speculative Decoding</code>
    <code>Multi-GPU</code>
  </p>

  <sub>
    M.S. in Computer Science @ Zhejiang Normal University · Graduating 2027 · Open to opportunities
  </sub>
</div>

<br/>

## What I Work On

- **Inference Acceleration** — speculative decoding, verification-budget scheduling, CUDA Graph bucketing, and throughput / latency trade-offs.
- **GPU Kernel Optimization** — Nsight profiling and Triton development for MoE fusion, shape-specific tiling, and numerical correctness.
- **LLM Serving Systems** — vLLM scheduling, KV / prefix cache reuse, AWQ deployment, tensor-parallel topology, and observability.

## Selected Work

| Project | What I worked on |
| --- | --- |
| [**DSpark Multi-GPU Serving**](https://github.com/xuhuan51/dspark-spec-serving-benchmark) | Multi-GPU speculative decoding in vLLM, with verification-budget scheduling, CUDA Graph bucketing, and paired throughput / token-latency benchmarks. |
| [**LLM Serving Stack**](https://github.com/xuhuan51/llm-serving-stack) | Reproducible serving experiments covering tensor-parallel topology, KV / prefix cache behavior, quantized deployment, GPU profiling, and SLO analysis. |

## Open Source

- [vLLM #51381](https://github.com/vllm-project/vllm/pull/51381) · **Merged** — session identity propagation for GPU KV Events, with serialization compatibility and prefix-cache regression coverage.
- [vLLM-Omni #8279](https://github.com/vllm-project/vllm-omni/pull/8279) · **Merged** — restored Qwen3-Omni realtime routing for typed stage configs, with WebSocket and error-event regression coverage.

## Working With

`Python` · `C++` · `CUDA` · `Triton` · `PyTorch` · `vLLM` · `NCCL` · `Nsight` · `Docker` · `Kubernetes` · `Prometheus`

<details>
<summary>Earlier work: AI agents and agent platforms</summary>

- [**DBOps Enterprise Copilot**](https://github.com/xuhuan51/dbops-enterprise-copilot) — a LangGraph Text-to-SQL agent with hybrid schema retrieval, graph-based join planning, SQL verification, and Kubernetes delivery.
- **Argus & Alice** — AIOps workflows and agent-platform engineering: evidence-based RCA, sandbox runtimes, streaming orchestration, evaluation, and reliability.

</details>

<br/>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/hazy-pixel-art-dark.gif"/>
    <source media="(prefers-color-scheme: light)" srcset="./assets/hazy-pixel-art-light.gif"/>
    <img
      src="./assets/hazy-pixel-art-light.gif"
      alt="Animated developer workspace"
      width="640"
    />
  </picture>
</div>

<div align="center">
  <sub>
    From kernel profiling to faster LLM serving.<br/>
    Pixel animation from
    <a href="https://github.com/Hazy019/hazy-readme-cards">Hazy Readme Cards</a>,
    used under the MIT License.
  </sub>
</div>
