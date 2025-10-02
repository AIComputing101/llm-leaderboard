# SEA-LION v3.5 70B R

> Reasoning

**Organization:** [AI Singapore](../../labs/ai-singapore.md)
**Released:** Apr/2025
**Access:** 🟢 Public

---

## 📊 Overview

SEA-LION v3.5 70B R is designed for advanced reasoning and multi-step problem solving.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 70.0B
- **Training Tokens:** 15000.0B
- **Token:Param Ratio:** 215:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 3.4 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | 72.04 | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

`Reasoning`

## 📝 Additional Notes

"Based on Llama 3.1 70B. SEA-LION v3.5, our first set of hybrid reasoning models trained on Southeast Asian data. Mode selection is managed through the tokenizer’s chat template and offers versatile functionality, handling both complex reasoning tasks and general text generation."

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/aisingapore/Llama-SEA-LION-v3.5-70B-R)
- 📄 [Technical Documentation](https://sea-lion.ai/sea-lion-v3-5-and-updated-v3-enhanced-language-models-for-southeast-asia/)

## 🔍 Related Models

**From AI Singapore:**
- See all models in [AI Singapore profile](../../labs/ai-singapore.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All AI Singapore Models](../../labs/ai-singapore.md)
