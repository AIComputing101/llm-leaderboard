# EXAONE 4.0

> Reasoning

**Organization:** [LG](../../labs/lg.md)
**Released:** Jul/2025
**Access:** 🟢 Public

---

## 📊 Overview

EXAONE 4.0 is designed for advanced reasoning and multi-step problem solving.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 32.0B
- **Training Tokens:** 14000.0B
- **Token:Param Ratio:** 438:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 2.2 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 92.3 | General knowledge across 57 subjects |
| **MMLU-Pro** | 81.8 | Advanced MMLU variant |
| **GPQA** | 75.4 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Exceptional performance on MMLU benchmark (>90%), demonstrating strong general knowledge.

**Analysis:** Good reasoning capabilities on GPQA (60-80%).

## 🏷️ Model Tags

`Reasoning`

## 📝 Additional Notes

“EXAONE”=“EXpert AI for EveryONE”. Training tokens/ratio: EXAONE-3 7.8B=8T tokens (Aug/2024) -> EXAONE-3.5 7.8B=9T -> EXAONE-3.5 32B=6.5T tokens -> EXAONE 4.0 32B=14T tokens. MMLU score is MMLU-Redux. Interesting: "To focus [RL] training on more informative data samples, we perform accuracy-based filtering by generating eight responses from the SFT model and excluding samples where all eight responses are correct, a pre-filtering step that removes problems that are easy for the model to avoid inefficient training."

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/LGAI-EXAONE/EXAONE-4.0-32B)
- 📄 [Technical Documentation](https://www.lgresearch.ai/data/cdn/upload/EXAONE_4_0.pdf)

## 🔍 Related Models

**From LG:**
- See all models in [LG profile](../../labs/lg.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All LG Models](../../labs/lg.md)
