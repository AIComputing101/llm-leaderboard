# Cogito 70B

> Large Language Model

**Organization:** [Deep Cogito](../../labs/deep-cogito.md)
**Released:** Apr/2025
**Access:** 🟢 Public

---

## 📊 Overview

Cogito 70B is a large language model developed by Deep Cogito.

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
| **MMLU** | 91.0 | General knowledge across 57 subjects |
| **MMLU-Pro** | 78.47 | Advanced MMLU variant |
| **GPQA** | 60.61 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Exceptional performance on MMLU benchmark (>90%), demonstrating strong general knowledge.

**Analysis:** Good reasoning capabilities on GPQA (60-80%).

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

"We are releasing early checkpoints of models in sizes 3B, 8B, 14B, 32B and 70B trained using this methodology, starting from pretrained Llama / Qwen base checkpoints."

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/deepcogito/cogito-v1-preview-llama-70B)
- 📄 [Technical Documentation](https://www.deepcogito.com/research/cogito-v1-preview)

## 🔍 Related Models

**From Deep Cogito:**
- See all models in [Deep Cogito profile](../../labs/deep-cogito.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Deep Cogito Models](../../labs/deep-cogito.md)
