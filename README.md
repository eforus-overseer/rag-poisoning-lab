# RAG Poisoning Lab

> Measure how a controlled, synthetic corpus edit changes retrieval and answers.

**Status:** open project seed · **License:** MIT · **Contributions:** welcome

An educational local lab for testing retrieval poisoning, provenance checks, and citation stability.

## The question

When a small number of documents are manipulated or made misleading, how do retrieval rank, cited sources, and answer claims change?

## Why build this

This extends your literary LLM knowledge-poisoning and RAG QA work into a reusable, non-domain-specific experiment harness. All fixtures stay local and synthetic.

## First milestone

A fully synthetic corpus; baseline and modified snapshots; one sparse and one embedding retriever; a notebook and JSON report comparing top-k sources and claims.

## A first contribution

**Create paired clean/modified documents and a format for marking provenance, expected retrieval, and safe answer behavior.**

See [`CONTRIBUTING.md`](CONTRIBUTING.md) for the small, reviewable contribution flow. You can also open an issue with the **good first issue** template, propose a test fixture, review a design choice, improve documentation, or help keep the scope honest. No model API key is needed for the initial milestone.

## Working principles

- Treat model output and retrieved content as untrusted input.
- Prefer deterministic controls, explicit assumptions, and reproducible fixtures.
- Use synthetic or public-domain examples; do not commit credentials, private prompts, personal data, or customer logs.
- Report limits and false positives. A benchmark score or static rule is not a security guarantee.
- Keep security tests inside local fixtures or systems you own and have permission to test.

## Research map

This seed is informed by the [OWASP GenAI Security Project](https://genai.owasp.org/), including its LLM and Agentic Application guidance, and by active open-source work such as [garak](https://github.com/NVIDIA/garak), [promptfoo](https://github.com/promptfoo/promptfoo), [LLM Guard](https://github.com/protectai/llm-guard), and [PyRIT](https://github.com/microsoft/PyRIT). Each project aims for a narrow, inspectable contribution rather than a replacement for those broader tools.

[Compare star histories for garak, promptfoo, LLM Guard, and OWASP's LLM Top 10](https://star-history.com/#NVIDIA/garak&promptfoo/promptfoo&protectai/llm-guard&OWASP/www-project-top-10-for-large-language-model-applications). GitHub stars are an attention signal, not evidence of security quality.

## Join in

If this problem interests you, start with the first milestone above. Open an issue to discuss scope before building a large feature, or send a small pull request with a test and a clear explanation. Contributors from security, engineering, research, design, and documentation are all welcome.


<!-- codex-pixel-art -->
## Project visual

![Pixel-art cover for rag-poisoning-lab](assets/project-cover.png)

<sub>Pixel-art adaptation of [OpenMoji test tube](https://github.com/hfg-gmuend/openmoji/blob/master/color/618x618/1F9EA.png) by OpenMoji contributors, licensed [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Source: OpenMoji.</sub>
