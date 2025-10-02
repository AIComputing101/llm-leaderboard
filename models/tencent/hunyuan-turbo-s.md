# Hunyuan Turbo S

> Large Language Model

**Organization:** [Tencent](../../labs/tencent.md)
**Released:** Feb/2025
**Access:** 🟢 Public

---

## 📊 Overview

Hunyuan Turbo S is a large language model developed by Tencent.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 389.0B
- **Training Tokens:** 7000.0B
- **Token:Param Ratio:** 18:1 ⚠️ Under-trained

### Training Efficiency
- **ALScore:** 5.5 (Powerful)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 89.5 | General knowledge across 57 subjects |
| **MMLU-Pro** | 79.0 | Advanced MMLU variant |
| **GPQA** | 57.5 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Fast thinking ("Instant reply"). "This is also the first time in the industry that the Mamba architecture has been successfully applied losslessly to a very large MoE model."

## 🔗 Resources

- 🎮 [Try the Model](https://cloud.tencent.com/apply/p/i2zophus2x8)
- 📄 [Technical Documentation](https://mp.weixin.qq.com/s/BwQkXpEitOm1Piz60SE-4A)

## 🔍 Related Models

**From Tencent:**
- See all models in [Tencent profile](../../labs/tencent.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Tencent Models](../../labs/tencent.md)
