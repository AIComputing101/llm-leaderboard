# Sonus-1 Reasoning

> Large Language Model

**Organization:** [Rubik's AI](../../labs/rubiks-ai.md)
**Released:** Jan/2025
**Access:** 🟢 Public

---

## 📊 Overview

Sonus-1 Reasoning is a large language model developed by Rubik's AI.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 405.0B
- **Training Tokens:** 15000.0B
- **Token:Param Ratio:** 38:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 8.2 (Powerful)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 90.15 | General knowledge across 57 subjects |
| **MMLU-Pro** | 73.1 | Advanced MMLU variant |
| **GPQA** | 67.3 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Exceptional performance on MMLU benchmark (>90%), demonstrating strong general knowledge.

**Analysis:** Good reasoning capabilities on GPQA (60-80%).

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Likely a Llama 3.1 405B wrapper. ALPrompt 2024H1=5/5. ALPrompt 2024H2=2/5. ALPrompt 2025H1=1/5. This is a strange model: slow and smart, but not as performant as o1. No arch details at all.

## 🔗 Resources

- 🎮 [Try the Model](https://chat.sonus.ai/sonus/)
- 📄 [Technical Documentation](https://sonus.ai/blog/sonus-1)

## 🔍 Related Models

**From Rubik's AI:**
- See all models in [Rubik's AI profile](../../labs/rubiks-ai.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Rubik's AI Models](../../labs/rubiks-ai.md)
