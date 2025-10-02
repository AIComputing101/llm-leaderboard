# PACT

> Large Language Model

**Organization:** [Microsoft](../../labs/microsoft.md)
**Released:** Oct/2022
**Access:** 🟢 Public

---

## 📊 Overview

PACT is a large language model developed by Microsoft.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** -B
- **Training Tokens:** 0.03B
- **Token:Param Ratio:** - -

### Training Efficiency
- **ALScore:** 0.0
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** special

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

Trained on ~5TB data, 2GB model download. 'In general we see an improvement in model performance as we increase the number of training tokens. Interestingly, larger models did not necessarily result in better performance for robot navigation. Even though larger models consistently presented better loss values for action prediction on a static dataset, (Fig. 7 b), when it comes to real-time deployment the larger network capacity introduces inference delays that become a disadvantage and lead to earlier crashes. For example, while LiDAR perception measurements arrive to the vehicle every 0.077s (13Hz), the largest model of 24 layers takes on average 0.023s for inference with a RTX3090 GPU, roughly 40% longer the 3 layer model (0.016s). These time differences can amount to even larger performance gaps in small embedded systems, and further emphasize the importance of multiple downstream task architectures sharing a common representation branch for real-time robotics applications.'

## 🔗 Resources

- 🎮 [Try the Model](https://github.com/microsoft/PACT)
- 📄 [Technical Documentation](https://arxiv.org/abs/2209.11133)

## 🔍 Related Models

**From Microsoft:**
- See all models in [Microsoft profile](../../labs/microsoft.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Microsoft Models](../../labs/microsoft.md)
