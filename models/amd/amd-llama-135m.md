# AMD-Llama-135m

> Large Language Model

**Organization:** [AMD](../../labs/amd.md)
**Released:** Sep/2024
**Access:** 🟢 Public

---

## 📊 Overview

AMD-Llama-135m is a large language model developed by AMD.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 0.135B
- **Training Tokens:** 670.0B
- **Token:Param Ratio:** 4,963:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.0
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** books

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 23.02 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Small language model (SLM). Trained on AMD Instinct™ MI250 accelerators. "Pretrain Dataset: We employed the SlimPajama and Project Gutenberg dataset to pretrain the 135M model. Project Gutenberg is a library of over 70,000 free eBooks approximately. This sums up to 670B tokens"

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/amd/AMD-Llama-135m)
- 📄 [Technical Documentation](https://www.amd.com/en/developer/resources/technical-articles/introducing-amd-first-slm-135m-model-fuels-ai-advancements.html)

## 🔍 Related Models

**From AMD:**
- See all models in [AMD profile](../../labs/amd.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All AMD Models](../../labs/amd.md)
