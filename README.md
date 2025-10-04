# 🤖 LLM Leaderboard

> A comprehensive, community-driven tracking system for Large Language Models with detailed specifications, benchmarks, and analysis.

[![Models](https://img.shields.io/badge/models-679-blue)](models/)
[![Last Updated](https://img.shields.io/badge/updated-2025--10--02-green)](README.md)
[![License](https://img.shields.io/badge/license-MIT-orange)](LICENSE)

**Track. Compare. Analyze.** This repository provides an organized, searchable database of 679 LLM models from 174+ organizations, helping researchers and developers understand the rapidly evolving landscape of AI language models.

## ✨ Features

- 📊 **679 Models Tracked** - From GPT-5 to Gemini, Claude to Llama
- 🏢 **174+ Labs** - Coverage across major AI research organizations
- 📈 **Multiple Benchmarks** - MMLU, GPQA, HLE performance metrics
- 🔍 **Detailed Model Cards** - Architecture, training data, performance analysis
- 📂 **Organized Structure** - Browse by lab, architecture, capability, or release date
- 🚀 **Open Source** - MIT licensed, community contributions welcome

**Total Models:** 679

## 📊 Quick Navigation

- [Rankings](rankings/)
  - [By MMLU Score](rankings/by-mmlu.md)
  - [By Parameters](rankings/by-parameters.md)
  - [By Reasoning Capability](rankings/by-reasoning.md)
  - [By Release Date](rankings/by-date.md)
- [Labs & Organizations](labs/)
- [Architectures](architectures/)
  - [MoE Models](architectures/moe.md)
  - [Dense Models](architectures/dense.md)
- [Insights](insights/)
  - [Architecture Innovations 2025](insights/architecture-innovations-2025.md)
  - [Scaling Laws Analysis](insights/scaling-laws.md)
  - [Reasoning Models Trends](insights/reasoning-models.md)
  - [Open Source Landscape](insights/open-source.md)

## 🏆 Top Models by ALScore

ALScore is calculated as: `√(Parameters × Tokens) ÷ 300`

| Rank | Model | Lab | Params | Tokens | ALScore | MMLU | GPQA | Status |
|------|-------|-----|--------|--------|---------|------|------|--------|
| 1 | [Claude Opus 4](models/anthropic/claude-opus-4.md) | Anthropic | 6000.0B | 100000.0B | 81.6 | - | 83.3 | 🟢 |
| 2 | [GPT-4.5](models/openai/gpt-45.md) | OpenAI | 3000.0B | 114000.0B | 61.6 | 89.6 | 71.4 | 🟢 |
| 3 | [Claude Opus 4.1](models/anthropic/claude-opus-41.md) | Anthropic | 2000.0B | 100000.0B | 47.1 | - | 80.9 | 🟢 |
| 4 | [DeepSeek-R2](models/deepseek-ai/deepseek-r2.md) | DeepSeek-AI | 1200.0B | 130000.0B | 41.6 | - | - | 🟢 |
| 5 | [Claude 3 Opus](models/anthropic/claude-3-opus.md) | Anthropic | 2500.0B | 40000.0B | 33.3 | 86.8 | 59.5 | 🟢 |
| 6 | [codex-1](models/openai/codex-1.md) | OpenAI | 600.0B | 100000.0B | 25.8 | - | - | 🟢 |
| 7 | [o3](models/openai/o3.md) | OpenAI | 600.0B | 100000.0B | 25.8 | 91.2 | 83.3 | 🟢 |
| 8 | [Llama 4 Behemoth](models/meta-ai/llama-4-behemoth.md) | Meta AI | 2000.0B | 30000.0B | 25.8 | - | 73.7 | 🔴 |
| 9 | [Gemini Ultra](models/google-deepmind/gemini-ultra.md) | Google DeepMind | 2000.0B | 30000.0B | 25.8 | - | - | - |
| 10 | [o3-preview](models/openai/o3-preview.md) | OpenAI | 600.0B | 100000.0B | 25.8 | - | 87.7 | 🟢 |
| 11 | [Grok 4](models/xai/grok-4.md) | xAI | 600.0B | 80000.0B | 23.1 | - | 88.9 | 🟢 |
| 12 | [LearnLM](models/google-deepmind/learnlm.md) | Google DeepMind | 1500.0B | 30000.0B | 22.4 | - | 72.0 | 🟡 |
| 13 | [Gemini Ultra 1.0](models/google-deepmind/gemini-ultra-10.md) | Google DeepMind | 1500.0B | 30000.0B | 22.4 | 83.7 | 35.7 | 🟢 |
| 14 | [Yi-XLarge](models/01-ai/yi-xlarge.md) | 01-ai | 2000.0B | 20000.0B | 21.1 | 85.1 | 48.2 | 🟢 |
| 15 | [Qwen3-Max-Preview](models/alibaba/qwen3-max-preview.md) | Alibaba | 1000.0B | 36000.0B | 20.0 | - | 64.6 | 🟢 |
| 16 | [Qwen3-Max](models/alibaba/qwen3-max.md) | Alibaba | 1000.0B | 36000.0B | 20.0 | - | 85.4 | 🟢 |
| 17 | [GPT-5](models/openai/gpt-5.md) | OpenAI | 300.0B | 114000.0B | 19.5 | 91.0 | 89.4 | 🟢 |
| 18 | [Grok-3](models/xai/grok-3.md) | xAI | 928.0B | 36200.0B | 19.3 | - | 84.6 | 🟢 |
| 19 | [Gemini 2.5 Pro Preview](models/google-deepmind/gemini-25-pro-preview.md) | Google DeepMind | 400.0B | 80000.0B | 18.9 | - | 84.0 | 🟢 |
| 20 | [Claude Sonnet 4.5](models/anthropic/claude-sonnet-45.md) | Anthropic | 400.0B | 80000.0B | 18.9 | - | 83.4 | 🟢 |
| 21 | [Gemini 2.5 Pro 06-05](models/google-deepmind/gemini-25-pro-06-05.md) | Google DeepMind | 400.0B | 80000.0B | 18.9 | - | 86.4 | 🟢 |
| 22 | [Samba-1](models/sambanova/samba-1.md) | SambaNova | 1400.0B | 20000.0B | 17.6 | - | - | 🟡 |
| 23 | [Inflection-2](models/inflection-ai/inflection-2.md) | Inflection AI | 1200.0B | 20000.0B | 16.3 | - | - | 🟢 |
| 24 | [Inflection-3 Productivity (3.0)](models/inflection-ai/inflection-3-productivity-30.md) | Inflection AI | 1200.0B | 20000.0B | 16.3 | - | - | 🟢 |
| 25 | [Inflection-3 Pi (3.0)](models/inflection-ai/inflection-3-pi-30.md) | Inflection AI | 1200.0B | 20000.0B | 16.3 | - | - | 🟢 |
| 26 | [Inflection-2.5](models/inflection-ai/inflection-25.md) | Inflection AI | 1200.0B | 20000.0B | 16.3 | 85.5 | 38.4 | 🟢 |
| 27 | [SpreadsheetLLM](models/microsoft/spreadsheetllm.md) | Microsoft | 1760.0B | 13000.0B | 15.9 | - | - | 🔴 |
| 28 | [GPT-4 Classic (gpt-4-0314 & gpt-4-0613, non-Turbo)](models/openai/gpt-4-classic-gpt-4-0314-gpt-4-0613-non-turbo.md) | OpenAI | 1760.0B | 13000.0B | 15.9 | 86.4 | 35.7 | 🟢 |
| 29 | [GPT-4 MathMix](models/openai/gpt-4-mathmix.md) | OpenAI | 1760.0B | 13000.0B | 15.9 | - | - | 🔴 |
| 30 | [PanGu 5.0 Super](models/huawei/pangu-50-super.md) | Huawei | 1000.0B | 20000.0B | 14.9 | - | - | 🟡 |


## 📈 Dataset Statistics

- **Total Models:** 679
- **Public Models:** 551
- **Private Models:** 102
- **Labs Tracked:** 174

## 🏢 Top Labs by Model Count

- [Google DeepMind](labs/google-deepmind.md): 47 models
- [Microsoft](labs/microsoft.md): 38 models
- [Meta AI](labs/meta-ai.md): 36 models
- [OpenAI](labs/openai.md): 32 models
- [Google](labs/google.md): 28 models
- [Alibaba](labs/alibaba.md): 26 models
- [NVIDIA](labs/nvidia.md): 23 models
- [Mistral](labs/mistral.md): 21 models
- [DeepSeek-AI](labs/deepseek-ai.md): 16 models
- [Baidu](labs/baidu.md): 12 models


## 🏗️ Architecture Distribution

- Dense: 534 models
- MoE: 131 models
- MatFormer: 2 models
- Hybrid: 2 models
- Compound: 1 models
- CoE: 1 models


## 📝 About This Project

This leaderboard tracks LLM models with detailed specifications, benchmarks, and metadata. All data is organized in markdown for easy browsing and version control.

### Benchmarks Explained

- **ALScore**: Quick power rating based on parameters and training tokens
- **MMLU**: Massive Multitask Language Understanding (general knowledge)
- **MMLU-Pro**: Advanced version of MMLU
- **GPQA**: Graduate-level Q&A benchmark
- **HLE**: High-Level Evaluation score

### Tags

- **SOTA**: State-of-the-art performance
- **Reasoning**: Advanced reasoning capabilities
- **Dense**: Traditional dense architecture
- **MoE**: Mixture of Experts architecture

---

## 🚀 Getting Started

### Browse the Leaderboard

1. **Explore Top Models**: Start with the [top 30 models](#-top-models-by-alscore) ranked by ALScore
2. **Find by Lab**: Check out specific organizations in the [Labs section](#-top-labs-by-model-count)
3. **Filter by Capability**: Browse [Reasoning Models](rankings/by-reasoning.md) or [Architecture Types](architectures/)
4. **View Details**: Click any model name to see detailed specifications and benchmarks

### Search Options

- **By Performance**: [MMLU Rankings](rankings/by-mmlu.md) | [By Parameters](rankings/by-parameters.md)
- **By Time**: [Release Date](rankings/by-date.md) - See the latest releases
- **By Organization**: [All Labs](labs/) - Browse all 174+ organizations
- **By Architecture**: [MoE Models](architectures/moe.md) | [Dense Models](architectures/dense.md)

### Model Card Structure

Each model page includes:
- 📊 Overview and key capabilities
- 🔧 Technical specifications (parameters, tokens, architecture)
- 📈 Performance benchmarks with intelligent analysis
- 🏷️ Tags and categories
- 📝 Detailed notes and key information
- 🔗 Links to official resources
- 🔍 Related models and lab profiles

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. **Report Issues**: Found incorrect data? [Open an issue](../../issues)
2. **Suggest Models**: Know a model we're missing? Let us know!
3. **Improve Documentation**: Help keep information accurate and up-to-date
4. **Share Feedback**: Ideas for better organization or new features?

See [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines.

## 📊 Data & Methodology

### Data Collection

Data is aggregated from multiple sources:
- Official model releases and announcements
- Research papers and technical documentation
- Public benchmarks and evaluation leaderboards
- Community verification and contributions

### Compute Optimal Training

Models are evaluated against the **Chinchilla scaling law** (optimal ratio ≥20:1 tokens-to-parameters):
- ✅ **Compute-optimal**: Adequately trained with sufficient data (≥20:1)
- ⚠️ **Under-trained**: May benefit from additional training (<20:1)

### Benchmark Scoring

- **ALScore Formula**: `√(Parameters × Tokens) ÷ 300`
  - ≥20: Extremely powerful
  - 10-20: Very powerful
  - 5-10: Powerful
  - 1-5: Mid-tier
  - <1: Lightweight

**Note**: Benchmark scores are from publicly available sources. Some values may be estimates or unavailable (-).

## 📜 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- All AI research organizations for their contributions to open research
- The AI community for sharing benchmarks and insights
- Contributors who help keep this resource accurate and up-to-date

---

**Last Updated:** 2025-10-02 | **Maintained by:** Community Contributors

⭐ **Star this repo** to stay updated with the latest LLM developments!
