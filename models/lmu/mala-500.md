# MaLA-500

> Large Language Model

**Organization:** [LMU](../../labs/lmu.md)
**Released:** Jan/2024
**Access:** 🟢 Public

---

## 📊 Overview

MaLA-500 is a large language model developed by LMU.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 10.0B
- **Training Tokens:** 2000.0B
- **Token:Param Ratio:** 200:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.5 (Lightweight)
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

Extends Llama 2 7B to 10B using 534 languages.

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/MaLA-LM/mala-500)
- 📄 [Technical Documentation](https://arxiv.org/abs/2401.13303)

## 🔍 Related Models

**From LMU:**
- See all models in [LMU profile](../../labs/lmu.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All LMU Models](../../labs/lmu.md)
