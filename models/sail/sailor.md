# Sailor

> Large Language Model

**Organization:** [Sail](../../labs/sail.md)
**Released:** Apr/2024
**Access:** 🟢 Public

---

## 📊 Overview

Sailor is a large language model developed by Sail.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 7.0B
- **Training Tokens:** 200.0B
- **Token:Param Ratio:** 29:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.1 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

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

SEA languages. Based on Qwen-1.5. https://github.com/sail-sg/sailor-llm "Generally Sailor models consume around 200B tokens, completing a full pass through the SailCraft corpus once. However, the Sailor-0.5B model undergoes training with 400B tokens, equivalent to 2 epochs."

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/sail)
- 📄 [Technical Documentation](https://arxiv.org/abs/2404.03608v1)

## 🔍 Related Models

**From Sail:**
- See all models in [Sail profile](../../labs/sail.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Sail Models](../../labs/sail.md)
