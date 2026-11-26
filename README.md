![Header](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,14,20&height=220&section=header&text=Ya%20Mone%20Zin&fontSize=45&fontColor=ffffff&desc=AI%20Researcher%20%7C%20Doctoral%20Student&descAlignY=65)

## 👩🏻‍💻 About Me

I am a PhD student in Computer Science at the University of Tsukuba, Japan, working at the intersection of artificial intelligence, numerical computing, and software engineering.

- 🎓 Doctoral Student at University of Tsukuba | CVLAB
- 🔬 Researching LLM inference reproducibility and AI reliability
- 💻 Software developer with a background in programming language design
- 📚 Published researcher
- 🌏 Based in Japan
- 🤝 Open to research collaborations and remote AI engineering opportunities

## 🔬 Current Research

- Large Language Models (LLMs)
- AI Inference Reproducibility
- Floating-Point Numerical Errors
- GPU Computing and High-Performance Computing
- Low-Precision Inference (FP16 / BF16)
- Functional Programming and Metaprogramming

## ⭐ Featured Research

### LLM Numerical Reproducibility — Hadamard Error Gauges for Low-Precision GPU GEMM

Doctoral research implementation within the CVLAB Reproducibility program (direction: Pedro Valois): three staged gauges that isolate whether a fixed orthogonal Hadamard transform on the GEMM contraction axis changes fp16/bf16 numerical error when the GEMM runs on the same NVIDIA GPU kernels real inference uses — with pre-measurement invariance gates, deterministic cuBLAS configuration, and seed-stratified statistics.

- **NumPy isolation study** (`gemm_error_gauge`) — CPU fp16 rounding model with error stage decomposition
- **cuBLAS validation** (`gpu_gemm_error_gauge`) — the real inference execution path on CUDA
- **Dimension sweep** (`gpu_gemm_dim_sweep`) — resolves the fixed shape into M / N / K curves
- **Real-weight mode** — one pinned Qwen3-8B projection as operand B (campaign record stays internal to CVLAB)

[![Repository](https://img.shields.io/badge/View_Repository-1D4ED8?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yamone-zin/llm-numerical-reproducibility)

## 🛠️ Technical Skills

### Artificial Intelligence & Machine Learning

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![NVIDIA](https://img.shields.io/badge/GPU_Computing-76B900?style=for-the-badge&logo=nvidia&logoColor=white)

### Programming Languages

![OCaml](https://img.shields.io/badge/OCaml-EC6813?style=for-the-badge&logo=ocaml&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Scala](https://img.shields.io/badge/Scala-DC322F?style=for-the-badge&logo=scala&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Ruby](https://img.shields.io/badge/Ruby-CC342D?style=for-the-badge&logo=ruby&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)

### Development Tools & Frameworks

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white)

### AI-Assisted Development

![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge)
![Codex](https://img.shields.io/badge/OpenAI_Codex-212121?style=for-the-badge)
![OpenCode](https://img.shields.io/badge/OpenCode-6366F1?style=for-the-badge)
![ChatGPT](https://img.shields.io/badge/ChatGPT-10A37F?style=for-the-badge)

## 📚 Publications

### MAYUZIN: Runtime Generative and Analytical Metaprogramming

Journal of Information Processing (IPSJ), 2025.

Research on runtime code generation, code analysis, and type-safe metaprogramming using OCaml and MetaOCaml.

[![Publication](https://img.shields.io/badge/Read_Publication-2563EB?style=for-the-badge)](https://doi.org/10.2197/ipsjjip.33.461)

## 📂 Featured Projects

| Project | Description |
|---|---|
| [MAYUZIN Research](https://github.com/yamone-zin/mayuzin-research) | Runtime generative and analytical metaprogramming research |
| [MMOCaml](https://github.com/yamone-zin/MMOCaml) | Functional programming and metaprogramming research |
| [miniOCaml](https://github.com/yamone-zin/miniOCaml) | Programming language implementation |
| [Python Projects](https://github.com/yamone-zin/Python_Projects) | Python applications and programming experiments |
| [Ruby Projects](https://github.com/yamone-zin/Ruby_Projects) | Ruby software development projects |

## 🎓 Education

- **PhD in Computer Science** — University of Tsukuba, 2026–Present
- **Master's in Computer Science** — University of Tsukuba, 2023–2025
- **Bachelor's in Computer Science** — University of Computer Studies, Yangon, 2015–2020

## 🌐 Languages

- Burmese — Native
- English — Fluent
- Japanese — Conversational

---

<p align="center">
  <i>Researching reliable AI. Building meaningful software.</i>
</p>

![Footer](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,14,20&height=100&section=footer)

