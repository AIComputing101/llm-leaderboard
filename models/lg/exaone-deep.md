# EXAONE Deep

> Reasoning

**Organization:** [LG](../../labs/lg.md)
**Released:** Mar/2025
**Access:** 🟢 Public

---

## 📊 Overview

EXAONE Deep is designed for advanced reasoning and multi-step problem solving.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 32.0B
- **Training Tokens:** 6500.0B
- **Token:Param Ratio:** 204:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 1.5 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 83.0 | General knowledge across 57 subjects |
| **MMLU-Pro** | 74.0 | Advanced MMLU variant |
| **GPQA** | 66.1 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

**Analysis:** Good reasoning capabilities on GPQA (60-80%).

## 🏷️ Model Tags

`Reasoning`

## 📝 Additional Notes

“EXAONE”=“EXpert AI for EveryONE”. Training tokens/ratio dropped from EXAONE-3 7.8B with 8T (Aug/2024) to 3.5 (Dec/2024) 7.8B with 9T to 32B (also Deep) with 6.5T. Announce: https://www.lgresearch.ai/news/view?seq=543

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/LGAI-EXAONE/EXAONE-Deep-32B)
- 📄 [Technical Documentation](https://arxiv.org/abs/2503.12524)

## 🔍 Related Models

**From LG:**
- See all models in [LG profile](../../labs/lg.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All LG Models](../../labs/lg.md)
