# FLOR-6.3B

> Large Language Model

**Organization:** [Cerebras](../../labs/cerebras.md)
**Released:** Jan/2024
**Access:** 🟢 Public

---

## 📊 Overview

FLOR-6.3B is a large language model developed by Cerebras.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 6.3B
- **Training Tokens:** 481.0B
- **Token:Param Ratio:** 77:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.2 (Lightweight)
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

Spanish, Catalan. Bloom-7.1B (341B tok) + continued pre-training on 140B tok. Trained on Cerebras hardware.

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/projecte-aina/FLOR-6.3B)
- 📄 [Technical Documentation](https://www.cerebras.net/press-release/cerebras-systems-and-barcelona-supercomputing-center-train-industry-leading-multilingual-spanish-catalan-english-llm)

## 🔍 Related Models

**From Cerebras:**
- See all models in [Cerebras profile](../../labs/cerebras.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Cerebras Models](../../labs/cerebras.md)
