<div align="center">

![Aevyra](https://raw.githubusercontent.com/aevyraai/.github/main/profile/aevyra-logo.svg)

</div>

---

Building the infrastructure layer for the age of intelligent systems.

Everyone is focused on models, agents, and shiny demos. Almost no one is talking about the real bottleneck: we don't have the infrastructure around post-training inference to use models well in production. Not where it actually matters — benchmarking, tracing, failure attribution, prompt optimization, and the runtime systems that let models operate reliably in the real world. Deployment is largely solved. The rest isn't.

Open-source, across the stack.

## What we're building

**[aevyra-witness](https://github.com/aevyraai/witness)** — Agent tracing. Records every step of an agent pipeline — inputs, outputs, timing, and how steps relate to each other — in a single structured object. Zero runtime dependencies. Works with any LLM framework.

**[aevyra-verdict](https://github.com/aevyraai/verdict)** — LLM benchmarking. Before you can improve a model's behavior, you need a way to measure it. Verdict runs your prompts across any combination of models and providers, scores responses with pluggable metrics, and gives you a side-by-side comparison.

**[aevyra-origin](https://github.com/aevyraai/origin)** — Failure attribution. When an agent fails, Origin reads the trace and tells you which span caused it — with severity, confidence, and a `fix_type` that tells you whether the problem lives in a prompt, retrieval index, tool schema, or routing decision.

**[aevyra-reflex](https://github.com/aevyraai/reflex)** — Agentic prompt optimization. Reflex takes your dataset and prompt, runs evals, diagnoses why scores are falling short, and rewrites the prompt — iterating until it converges.

```
Witness  →  captures what happened
Verdict  →  judges it
Origin   →  finds where it went wrong
Reflex   →  fixes it
```

## Released

**[aevyra-witness](https://github.com/aevyraai/witness)** · [Docs](https://aevyra.mintlify.app/witness/introduction) · [PyPI](https://pypi.org/project/aevyra-witness/)

**[aevyra-verdict](https://github.com/aevyraai/verdict)** · [Docs](https://aevyra.mintlify.app/verdict/introduction) · [PyPI](https://pypi.org/project/aevyra-verdict/)

**[aevyra-origin](https://github.com/aevyraai/origin)** · [Docs](https://aevyra.mintlify.app/origin/introduction) · [PyPI](https://pypi.org/project/aevyra-origin/)

**[aevyra-reflex](https://github.com/aevyraai/reflex)** · [Docs](https://aevyra.mintlify.app/reflex/introduction) · [PyPI](https://pypi.org/project/aevyra-reflex/)

## Get involved

- 📬 [Email](mailto:ankithgunapal@gmail.com)

---

<div align="center">
<sub><i>intelligence from beyond</i></sub>
</div>
