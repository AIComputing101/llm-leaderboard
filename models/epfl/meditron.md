# MEDITRON

> Large Language Model

**Organization:** [EPFL](../../labs/epfl.md)
**Released:** Nov/2023
**Access:** 🟢 Public

---

## 📊 Overview

MEDITRON is a large language model developed by EPFL.

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

Llama 2 trained on med data using NVIDIA Megatron-LM. "outperforms Llama-2-70B, GPT-3.5 (text-davinci-003, 8-shot), and Flan-PaLM on multiple medical reasoning tasks."

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/epfl-llm/meditron-70b)
- 📄 [Technical Documentation](https://arxiv.org/abs/2311.16079)

## 🔍 Related Models

**From EPFL:**
- See all models in [EPFL profile](../../labs/epfl.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All EPFL Models](../../labs/epfl.md)
