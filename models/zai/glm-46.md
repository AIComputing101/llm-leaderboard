# GLM-4.6

> Reasoning

**Organization:** [Z.AI](../../labs/zai.md)
**Released:** Sep/2025
**Access:** 🟢 Public

---

## 📊 Overview

GLM-4.6 is designed for advanced reasoning and multi-step problem solving.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 355.0B
- **Training Tokens:** 22000.0B
- **Token:Param Ratio:** 62:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 9.3 (Powerful)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | 82.9 | Graduate-level reasoning |
| **HLE** | 30.4 | High-level evaluation |

**Analysis:** Outstanding reasoning performance on GPQA (>80%), approaching expert-level problem solving.

## 🏷️ Model Tags

`Reasoning`

## 📝 Additional Notes

355B-A32B. "context window has been expanded from 128K to 200K tokens"

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/zai-org/GLM-4.6)
- 📄 [Technical Documentation](https://z.ai/blog/glm-4.6)

## 🔍 Related Models

**From Z.AI:**
- See all models in [Z.AI profile](../../labs/zai.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Z.AI Models](../../labs/zai.md)
