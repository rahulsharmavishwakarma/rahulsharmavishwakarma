<h2>Hi, I'm Rahul 👋</h2>

I'm an ML engineer. At work I build document AI and agentic systems at [ZysecAI](https://zysec.ai). On my own time I build **speech recognition that runs on your own device**, and I publish the code, models and benchmarks openly.

[![Website](https://img.shields.io/badge/Website-black?style=flat-square&logo=githubpages&logoColor=white)](https://rahulsharmavishwakarma.github.io/)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/rahulsharmavishwakarma)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rahulsharmavishwakarma/)
[![X](https://img.shields.io/badge/X-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/RahulSharma_AI)

---

### Featured projects

<table>
<tr>
<td width="50%" valign="top">

#### [Vesper](https://github.com/rahulsharmavishwakarma/vesper)
**Voice to text on your Mac, fully local.**

Dictate with a shortcut or transcribe audio files, then optionally clean up the text with a local LLM. It needs no account and no cloud API.

- Rust core with a Svelte UI and Swift on the native side
- Runs speech models on **MLX**, **Core ML** (Neural Engine) and **sherpa-onnx**
- Ships with an open benchmark for comparing ASR models and text-cleanup models

[![Release](https://img.shields.io/github/v/release/rahulsharmavishwakarma/vesper?style=flat-square&label=release&color=ff6b3d)](https://github.com/rahulsharmavishwakarma/vesper/releases/latest)
[![License](https://img.shields.io/github/license/rahulsharmavishwakarma/vesper?style=flat-square)](https://github.com/rahulsharmavishwakarma/vesper/blob/main/LICENSE)
[![Site](https://img.shields.io/badge/site-vesper-555?style=flat-square)](https://rahulsharmavishwakarma.github.io/vesper/)

</td>
<td width="50%" valign="top">

#### [IndicEAR](https://github.com/rahulsharmavishwakarma/indicear)
**Speech recognition for 11 Indian languages and English.**

Turns the frozen audio encoder of EmbeddingGemma 2 into a speech recognizer that handles code-switched speech. Each word comes out in its own script, along with a language tag.

- Trains only **11.8M parameters** (adapters plus CTC and language-ID heads)
- Streams **8,356 h** of audio from the Hub, with dynamic batching and exact resume
- Includes an open benchmark scored against IndicConformer and SraVaani

[![PyPI](https://img.shields.io/pypi/v/indicear?style=flat-square&color=3775A9)](https://pypi.org/project/indicear/)
[![Model](https://img.shields.io/badge/🤗%20model-vesper--indicEAR-FFD21E?style=flat-square)](https://huggingface.co/rahulsharmavishwakarma/vesper-indicEAR)
[![License](https://img.shields.io/github/license/rahulsharmavishwakarma/indicear?style=flat-square)](https://github.com/rahulsharmavishwakarma/indicear/blob/main/LICENSE)

</td>
</tr>
</table>

See everything else in [my repositories →](https://github.com/rahulsharmavishwakarma?tab=repositories)

### 🤗 On Hugging Face

- **Speech model:** [vesper-indicEAR](https://huggingface.co/rahulsharmavishwakarma/vesper-indicEAR) (12 languages, CTC)
- **On-device ports:** Parakeet TDT 0.6B v3 for [MLX](https://huggingface.co/rahulsharmavishwakarma/vesper-parakeet-tdt-0.6b-v3-mlx-bf16), [Core ML (ANE, int8)](https://huggingface.co/rahulsharmavishwakarma/vesper-parakeet-tdt-0.6b-v3-coreml-ane) and [sherpa-onnx (4-bit)](https://huggingface.co/rahulsharmavishwakarma/vesper-parakeet-tdt-0.6b-v3-sherpa-onnx-wo4) · [Parakeet Redux (MLX)](https://huggingface.co/rahulsharmavishwakarma/vesper-parakeet-redux-mlx) · [Moonshine base (sherpa-onnx)](https://huggingface.co/rahulsharmavishwakarma/vesper-moonshine-base-en-sherpa-onnx)
- **Benchmarks:** [vesper-asr-benchmark](https://huggingface.co/datasets/rahulsharmavishwakarma/vesper-asr-benchmark) (en, hi, de, fr, es) · [vesper-indic-bench](https://huggingface.co/datasets/rahulsharmavishwakarma/vesper-indic-bench) (12 languages)

### ✍️ Writing

I write about the ML systems I build: serving, retrieval, speech and evaluation. Read the articles on **[my blog →](https://rahulsharmavishwakarma.github.io/)**

You can reach me on [LinkedIn](https://www.linkedin.com/in/rahulsharmavishwakarma/) or by [email](mailto:rahulsharmaviswakarma@gmail.com).
