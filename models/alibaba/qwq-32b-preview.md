# QwQ-32B-Preview

> Reasoning

**Organization:** [Alibaba](../../labs/alibaba.md)
**Released:** Nov/2024
**Access:** 🟢 Public

---

## 📊 Overview

QwQ-32B-Preview is designed for advanced reasoning and multi-step problem solving.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 32.0B
- **Training Tokens:** 18000.0B
- **Token:Param Ratio:** 563:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 2.5 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | 65.2 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Good reasoning capabilities on GPQA (60-80%).

## 🏷️ Model Tags

`Reasoning`

## 📝 Additional Notes

Scores 1/5 on latest ALPrompt 2024 H2. Qwen with Question=QwQ

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/spaces/Qwen/QwQ-32B-preview)
- 📄 [Technical Documentation](https://qwenlm.github.io/blog/qwq-32b-preview/)

## 🔍 Related Models

**From Alibaba:**
- See all models in [Alibaba profile](../../labs/alibaba.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Alibaba Models](../../labs/alibaba.md)
