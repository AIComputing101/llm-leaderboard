# Qwen2.5-Coder

> Large Language Model

**Organization:** [Alibaba](../../labs/alibaba.md)
**Released:** Nov/2024
**Access:** 🟢 Public

---

## 📊 Overview

Qwen2.5-Coder is a large language model developed by Alibaba.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 32.5B
- **Training Tokens:** 5500.0B
- **Token:Param Ratio:** 170:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 1.4 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 79.1 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

https://qwenlm.github.io/blog/qwen2.5-coder-family/ Jack Clark from Anthropic is saying it’s actually 18T tokens from Qwen2.5 + 5.5T tokens for a total of 23.5T tokens. That doesn’t seem right from my interpretation of the technical report.

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/Qwen/Qwen2.5-72B-Instruct)
- 📄 [Technical Documentation](https://arxiv.org/abs/2412.15115)

## 🔍 Related Models

**From Alibaba:**
- See all models in [Alibaba profile](../../labs/alibaba.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Alibaba Models](../../labs/alibaba.md)
