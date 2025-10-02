# MobileLLM

> Large Language Model

**Organization:** [Meta AI](../../labs/meta-ai.md)
**Released:** Feb/2024
**Access:** 🟢 Public

---

## 📊 Overview

MobileLLM is a large language model developed by Meta AI.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 1.0B
- **Training Tokens:** 1000.0B
- **Token:Param Ratio:** 1,000:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.1 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Optimizing Sub-billion Parameter Language Models for On-Device Use Cases

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/collections/facebook/mobilellm-6722be18cb86c20ebe113e95)
- 📄 [Technical Documentation](https://arxiv.org/abs/2402.14905)

## 🔍 Related Models

**From Meta AI:**
- See all models in [Meta AI profile](../../labs/meta-ai.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Meta AI Models](../../labs/meta-ai.md)
