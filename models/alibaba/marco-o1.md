# Marco-o1

> Reasoning

**Organization:** [Alibaba](../../labs/alibaba.md)
**Released:** Nov/2024
**Access:** 🟢 Public

---

## 📊 Overview

Marco-o1 is designed for advanced reasoning and multi-step problem solving.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 7.0B
- **Training Tokens:** 7000.0B
- **Token:Param Ratio:** 1,000:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.7 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

`Reasoning`

## 📝 Additional Notes

No evals. Qwen2-7B-Instruct with a combination of the filtered Open-O1 CoT dataset, Marco-o1 CoT dataset, and Marco-o1 Instruction dataset.

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/AIDC-AI/Marco-o1)
- 📄 [Technical Documentation](https://arxiv.org/abs/2411.14405)

## 🔍 Related Models

**From Alibaba:**
- See all models in [Alibaba profile](../../labs/alibaba.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Alibaba Models](../../labs/alibaba.md)
