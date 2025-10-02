# Seed-Thinking-v1.5

> Reasoning

**Organization:** [ByteDance](../../labs/bytedance.md)
**Released:** Apr/2025
**Access:** 🟢 Public

---

## 📊 Overview

Seed-Thinking-v1.5 is designed for advanced reasoning and multi-step problem solving.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 200.0B
- **Training Tokens:** 15000.0B
- **Token:Param Ratio:** 75:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 5.8 (Powerful)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | 87.0 | Advanced MMLU variant |
| **GPQA** | 77.3 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Good reasoning capabilities on GPQA (60-80%).

## 🏷️ Model Tags

`Reasoning`

## 📝 Additional Notes

200B-A20B. "Seed-Thinking-v1.5, capable of reasoning through thinking before responding, resulting in improved performance on a wide range of benchmarks. Seed-Thinking-v1.5 achieves 86.7 on AIME 2024, 55.0 on Codeforces and 77.3 on GPQA, demonstrating excellent reasoning abilities in STEM and coding."

## 🔗 Resources

- 🎮 [Try the Model](https://github.com/ByteDance-Seed/Seed-Thinking-v1.5)
- 📄 [Technical Documentation](https://github.com/ByteDance-Seed/Seed-Thinking-v1.5)

## 🔍 Related Models

**From ByteDance:**
- See all models in [ByteDance profile](../../labs/bytedance.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All ByteDance Models](../../labs/bytedance.md)
