# GLM-4.5

> Reasoning

**Organization:** [Z.AI](../../labs/zai.md)
**Released:** Jul/2025
**Access:** 🟢 Public

---

## 📊 Overview

GLM-4.5 is designed for advanced reasoning and multi-step problem solving.

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
| **MMLU-Pro** | 84.6 | Advanced MMLU variant |
| **GPQA** | 79.1 | Graduate-level reasoning |
| **HLE** | 14.4 | High-level evaluation |

**Analysis:** Good reasoning capabilities on GPQA (60-80%).

## 🏷️ Model Tags

`Reasoning`

## 📝 Additional Notes

355B-A32B.

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/zai-org/GLM-4.5)
- 📄 [Technical Documentation](https://z.ai/blog/glm-4.5)

## 🔍 Related Models

**From Z.AI:**
- See all models in [Z.AI profile](../../labs/zai.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Z.AI Models](../../labs/zai.md)
