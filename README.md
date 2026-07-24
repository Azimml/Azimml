<div align="center">

# Hi, I'm Azimbek 👋

**Machine Learning Engineer** · Tashkent, Uzbekistan 🇺🇿

Systems-minded ML engineer working at the intersection of **LLM inference, quantization, and retrieval** — I like problems where the hard part is making a model actually *run* somewhere it wasn't supposed to.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/azimbek-olimbekov/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:azimbekolimbekov1@gmail.com)

</div>

---

## 🚀 Selected work

Each project below is original, reproducible, and CI-tested. Benchmarks are measured, not estimated.

### 🧠 [trellis-webgpu](https://github.com/Azimml/trellis-webgpu) — trellis-coded LLM quantization, outside CUDA
The first trellis-coded quantization (TCQ) decoder — the method behind QTIP/EXL3 — to run **outside CUDA**. An 8B model executes its full forward pass **in a browser tab on WebGPU**, on a 4 GB GPU, at SOTA 3-bit quality (1.15× fp16 perplexity). From-scratch quantizer (tail-biting Viterbi, LDLQ, incoherence processing) plus a same-source cross-runtime harness that runs the exact shipping WGSL through `wgpu-py` to prove the browser code correct.
`Python` · `WGSL / WebGPU` · `Triton` · `PyTorch`

### ⏱️ [adaptive-test-time-compute](https://github.com/Azimml/adaptive-test-time-compute) — per-instance compute allocation
A consensus-based controller that decides *how much* inference compute each question needs. **47% fewer samples and 46% fewer tokens than fixed-8 sampling at statistically indistinguishable accuracy** on 300 GSM8K questions — via a triple stopping gate that avoids the naive "two agree → stop" trap.
`Python` · `FastAPI` · `asyncio`

### 🧬 [mutation-effect-prediction](https://github.com/Azimml/mutation-effect-prediction) — leakage-aware genomics ML
Pathogenic-vs-benign SNV classification on official ClinVar / GRCh38 data. The headline is methodological honesty: a **deterministic, region-hashed train/test split** that closes the sequence-context leakage random splits hide — under which a mutation-centered CNN reaches **0.883 AUROC** on held-out loci.
`Python` · `PyTorch` · `scikit-learn` · `genomics`

### 🔍 [RAG-Architecture](https://github.com/Azimml/RAG-Architecture) — multi-route retrieval
A universal RAG architecture for combining and routing across multiple data sources.
`Python`

---

## 🛠️ Tech

**Languages** · Python · Rust · TypeScript · C
**ML / Infra** · PyTorch · Triton · WebGPU / WGSL · Transformers · scikit-learn
**Serving** · FastAPI · Docker · REST / WebSocket

---

## 📌 About this profile

I keep a small number of projects I can defend line-by-line rather than a large number of forks. Every repo above has a real README, a test suite, and green CI — the READMEs go all the way down if you want the deep version.

<div align="center">

📫 **[azimbekolimbekov1@gmail.com](mailto:azimbekolimbekov1@gmail.com)** · **[LinkedIn](https://www.linkedin.com/in/azimbek-olimbekov/)**

</div>
