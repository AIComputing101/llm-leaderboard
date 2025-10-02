# Pangu Ultra

> Large Language Model

**Organization:** [Huawei](../../labs/huawei.md)
**Released:** Apr/2025
**Access:** 🟢 Public

---

## 📊 Overview

Pangu Ultra is a large language model developed by Huawei.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 135.0B
- **Training Tokens:** 13200.0B
- **Token:Param Ratio:** 98:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 4.4 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 85.4 | General knowledge across 57 subjects |
| **MMLU-Pro** | 84.4 | Advanced MMLU variant |
| **GPQA** | 74.2 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

**Analysis:** Good reasoning capabilities on GPQA (60-80%).

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Trained on 8,192 Ascend NPUs (Kunpeng 920 processors in Huawei Atlas 800T A2 servers).

## 🔗 Resources

- 🎮 [Try the Model](https://x.com/hbouammar/status/1911370093516185771)
- 📄 [Technical Documentation](https://arxiv.org/abs/2504.07866)

## 🔍 Related Models

**From Huawei:**
- See all models in [Huawei profile](../../labs/huawei.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Huawei Models](../../labs/huawei.md)
