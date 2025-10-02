# Granite 3.3 8B Instruct

> Reasoning

**Organization:** [IBM](../../labs/ibm.md)
**Released:** Apr/2025
**Access:** 🟢 Public

---

## 📊 Overview

Granite 3.3 8B Instruct is designed for advanced reasoning and multi-step problem solving.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 8.0B
- **Training Tokens:** 12000.0B
- **Token:Param Ratio:** 1,500:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 1.0 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 65.54 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

`Reasoning`

## 📝 Additional Notes

"Built on top of an updated Granite 3.3 base model and fine-tuned through multi-stage reinforcement learning using TPO and Group Relative Policy Optimization (GRPO), both Granite 3.3 Instruct models demonstrated significant improvement on the highly technical benchmarks conventionally associated with “reasoning” capabilities."

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/ibm-granite/granite-3.3-8b-instruct)
- 📄 [Technical Documentation](https://www.ibm.com/new/announcements/ibm-granite-3-3-speech-recognition-refined-reasoning-rag-loras)

## 🔍 Related Models

**From IBM:**
- See all models in [IBM profile](../../labs/ibm.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All IBM Models](../../labs/ibm.md)
