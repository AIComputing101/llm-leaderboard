# Falcon-H1

> Large Language Model

**Organization:** [TII](../../labs/tii.md)
**Released:** May/2025
**Access:** 🟢 Public

---

## 📊 Overview

Falcon-H1 is a large language model developed by TII.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 34.0B
- **Training Tokens:** 18000.0B
- **Token:Param Ratio:** 530:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 2.6 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 84.05 | General knowledge across 57 subjects |
| **MMLU-Pro** | 58.73 | Advanced MMLU variant |
| **GPQA** | 49.66 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

"hybrid architecture that combines the strengths of the classical Transformer-based attention mechanism with the State Space Model (SSM), known for its superior long-context memory and computational efficiency."

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/tiiuae/Falcon-H1-34B-Instruct-GGUF)
- 📄 [Technical Documentation](https://huggingface.co/papers/2507.22448)

## 🔍 Related Models

**From TII:**
- See all models in [TII profile](../../labs/tii.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All TII Models](../../labs/tii.md)
