# WeLM

> Large Language Model

**Organization:** [Wechat](../../labs/wechat.md)
**Released:** Sep/2022
**Access:** 🟢 Public

---

## 📊 Overview

WeLM is a large language model developed by Wechat.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 10.0B
- **Training Tokens:** 300.0B
- **Token:Param Ratio:** 30:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.2 (Lightweight)
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

13% English tokens and 87% Chinese

## 🔗 Resources

- 🎮 [Try the Model](https://welm.weixin.qq.com/docs/playground/)
- 📄 [Technical Documentation](https://arxiv.org/abs/2209.10372)

## 🔍 Related Models

**From Wechat:**
- See all models in [Wechat profile](../../labs/wechat.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Wechat Models](../../labs/wechat.md)
