Hi, I'm Anon

I build ML training infrastructure and AI tooling from scratch. I'm self-taught, and most of what I know comes from building things and breaking them.

What I've built

[Roxxel](https://github.com/anon160/Roxxel): a memory-mapped dataloader, async checkpointer, and trainer for pre-training with JAX and Flax NNX. Supports resume by offset, dataset blending, and curriculum schedules. On PyPI.
[SLM name]: a [50M]-parameter language model trained with Roxxel on [hardware]. [One result, e.g. "val perplexity X, compared with Y".] (Coming soon: [link])
[rezjs](https://github.com/anon160/rezjs): a TypeScript library that detects third-party API schema drift, has an LLM propose a fix, verifies it in a WASM sandbox, and opens a PR for human review.
Tritan: an experimental RISC-V kernel in Rust.

Currently working on: retraining my small language model with full logging and evals, and benchmarking Roxxel's dataloader against existing tools.

Stack: Python, JAX/Flax, Rust, TypeScript. TPUs and GPUs.
