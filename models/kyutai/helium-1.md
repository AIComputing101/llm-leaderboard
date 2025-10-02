# Helium-1

> Large Language Model

**Organization:** [Kyutai](../../labs/kyutai.md)
**Released:** Jan/2025
**Access:** 🟢 Public

---

## 📊 Overview

Helium-1 is a large language model developed by Kyutai.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 2.0B
- **Training Tokens:** 2500.0B
- **Token:Param Ratio:** 1,250:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.2 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 51.2 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

"Helium-1 preview, an initial version of our new backbone language model with 2B parameters, targeting edge and mobile devices... We use token level distillation of a 7B parameters model to train Helium-1 preview."

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/kyutai/helium-1-preview-2b)
- 📄 [Technical Documentation](https://kyutai.org/2025/01/13/helium.html)

## 🔍 Related Models

**From Kyutai:**
- See all models in [Kyutai profile](../../labs/kyutai.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Kyutai Models](../../labs/kyutai.md)
