<div align="center">

![Aevyra](https://raw.githubusercontent.com/aevyraai/.github/main/profile/aevyra-logo-final.svg)

</div>

---

Aevyra is an open-source org building infrastructure for large language models. Not wrappers around existing APIs — tooling that works at the layers below that: GPU kernels, fine-tuning pipelines, and the runtime systems that make models actually useful in production.

The projects span the full stack. Some are low-level (Triton kernels for attention and quantization). Some are higher up (agentic fine-tuning pipelines). Some are end-user systems (a personal assistant architecture that isn't just a chatbot with memory). They're connected by a shared thesis: the interesting work in AI right now is infrastructure, not prompting.

## What we're building

**GPU kernel optimizations**
Most LLM inference bottlenecks aren't in the model architecture — they're in how efficiently the underlying operations run on hardware. These projects target attention, matrix multiplication, and quantization at the Triton level, where there's still significant headroom between what PyTorch gives you out of the box and what the hardware can actually do.

**Agentic fine-tuning**
Fine-tuning a model well requires good data curation, careful eval design, and knowing when to stop — none of which scales with manual iteration. The goal here is a pipeline that closes that loop automatically: generate candidates, evaluate outputs, curate the training set, train, and repeat until the model meets a defined quality bar.

**Personal intelligence systems**
Current personal assistants are stateless by design — each conversation starts from scratch. The gap between "AI assistant" and something genuinely useful is persistent context: knowing what you're working on, how you think, and what you've already decided. This project is an attempt to build that architecture from first principles rather than bolt memory onto an existing chat interface.

## Status

Early development. No stable releases yet. If you're interested in contributing or following along, watch the org or reach out directly.

## Get involved

- 📬 [Email](mailto:ankithgunapal@gmail.com)

---

<div align="center">
<sub><i>intelligence from beyond</i></sub>
</div>
