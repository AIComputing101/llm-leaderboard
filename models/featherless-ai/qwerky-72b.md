# Qwerky-72B

> Large Language Model

**Organization:** [Featherless AI](../../labs/featherless-ai.md)
**Released:** Apr/2025
**Access:** 🟢 Public

---

## 📊 Overview

Qwerky-72B is a large language model developed by Featherless AI.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 72.0B
- **Training Tokens:** 18000.0B
- **Token:Param Ratio:** 250:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 3.8 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 77.46 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

"As demonstrated with our Qwerky-72B-Preview and prior models such as QRWKV6-32B Instruct Preview, we have successfully converted Qwen 2.5 72B into a RWKV variant without requiring a pretrain on the base model or retraining the model from scratch. Enabling us to test and validate the more efficient RWKV Linear attention" Dataset from Qwen2.5=18,000 tokens.

## 🔗 Resources

- 🎮 [Try the Model](https://featherless.ai/models/featherless-ai/Qwerky-72B)
- 📄 [Technical Documentation](https://featherless.ai/models/featherless-ai/Qwerky-72B/readme)

## 🔍 Related Models

**From Featherless AI:**
- See all models in [Featherless AI profile](../../labs/featherless-ai.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Featherless AI Models](../../labs/featherless-ai.md)
