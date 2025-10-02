# Starling-7B

> Large Language Model

**Organization:** [Berkeley](../../labs/berkeley.md)
**Released:** Nov/2023
**Access:** 🟢 Public

---

## 📊 Overview

Starling-7B is a large language model developed by Berkeley.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 7.0B
- **Training Tokens:** 2000.0B
- **Token:Param Ratio:** 286:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.4 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | 37.9 | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Llama 2 7B -> OpenChat 7B -> Starling-7B (RLAIF)

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/berkeley-nest/Starling-LM-7B-alpha)
- 📄 [Technical Documentation](https://starling.cs.berkeley.edu/)

## 🔍 Related Models

**From Berkeley:**
- See all models in [Berkeley profile](../../labs/berkeley.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Berkeley Models](../../labs/berkeley.md)
