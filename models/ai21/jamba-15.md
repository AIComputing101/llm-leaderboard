# Jamba 1.5

> Large Language Model

**Organization:** [AI21](../../labs/ai21.md)
**Released:** Aug/2024
**Access:** 🟢 Public

---

## 📊 Overview

Jamba 1.5 is a large language model developed by AI21.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 398.0B
- **Training Tokens:** 8000.0B
- **Token:Param Ratio:** 21:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 5.9 (Powerful)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 81.2 | General knowledge across 57 subjects |
| **MMLU-Pro** | 53.5 | Advanced MMLU variant |
| **GPQA** | 36.9 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Jamba 1.5 Mini (12B active/52B total) and Jamba 1.5 Large (94B active/398B total) are also optimized for business use cases and capabilities such as function calling, structured output (JSON), and grounded generation.

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/collections/ai21labs/jamba-15-66c44befa474a917fcf55251)
- 📄 [Technical Documentation](https://arxiv.org/abs/2408.12570)

## 🔍 Related Models

**From AI21:**
- See all models in [AI21 profile](../../labs/ai21.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All AI21 Models](../../labs/ai21.md)
