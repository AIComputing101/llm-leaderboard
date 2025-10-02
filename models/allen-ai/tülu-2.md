# TÜLU 2

> Large Language Model

**Organization:** [Allen AI](../../labs/allen-ai.md)
**Released:** Nov/2023
**Access:** 🟢 Public

---

## 📊 Overview

TÜLU 2 is a large language model developed by Allen AI.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 70.0B
- **Training Tokens:** 2000.0B
- **Token:Param Ratio:** 29:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 1.2 (Mid-tier)
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

Llama 2 finetune with RLHF direct preference optimization (DPO).

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/allenai/tulu-2-dpo-70b)
- 📄 [Technical Documentation](https://arxiv.org/abs/2311.10702)

## 🔍 Related Models

**From Allen AI:**
- See all models in [Allen AI profile](../../labs/allen-ai.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Allen AI Models](../../labs/allen-ai.md)
