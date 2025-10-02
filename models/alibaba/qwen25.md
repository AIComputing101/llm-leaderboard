# Qwen2.5

> Large Language Model

**Organization:** [Alibaba](../../labs/alibaba.md)
**Released:** Sep/2024
**Access:** 🟢 Public

---

## 📊 Overview

Qwen2.5 is a large language model developed by Alibaba.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 72.0B
- **Training Tokens:** 18000.0B
- **Token:Param Ratio:** 250:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 3.8 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 86.1 | General knowledge across 57 subjects |
| **MMLU-Pro** | 71.1 | Advanced MMLU variant |
| **GPQA** | 49.0 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

_No additional notes available._

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
