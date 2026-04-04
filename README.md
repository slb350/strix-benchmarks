# Strix Benchmarks

**[slb350.github.io/strix-benchmarks](https://slb350.github.io/strix-benchmarks/)**

Local LLM benchmark results on AMD Strix Halo (Ryzen AI MAX+ 395, Radeon 8060S, 128 GB UMA, RDNA 3.5). I test 26+ models across three Vulkan/ROCm backends (RADV, AMDVLK, ROCm) using llama.cpp, then score them on creative writing, polyglot coding, and PostgreSQL tasks.

The site includes:

- **Models** — per-model performance (prompt processing, token generation) and quality scores across all benchmark suites
- **Methodology** — how each benchmark suite works, scoring criteria, and test conditions
- **Quantization** — comparison of quantization formats and their effect on speed and quality

Built with [Astro](https://astro.build) and deployed to GitHub Pages.
