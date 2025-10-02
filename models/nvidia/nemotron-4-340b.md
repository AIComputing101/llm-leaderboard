# Nemotron-4-340B

> SOTA

**Organization:** [NVIDIA](../../labs/nvidia.md)
**Released:** Jun/2024
**Access:** 🟢 Public

---

## 📊 Overview

Nemotron-4-340B represents state-of-the-art performance in its category.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 340.0B
- **Training Tokens:** 9000.0B
- **Token:Param Ratio:** 27:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 5.8 (Powerful)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 81.1 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

## 🏷️ Model Tags

`SOTA`

## 📝 Additional Notes

Open-source equiv of Mar/2023 GPT-4 (1760MoE≈340B, 13T), same param count but 2x the tokens of May/2023 PaLM 2 (340B, 3.6T), competitor to Nov/2023 Grok-1 (314B, 6T). Trained on 6,144 H100s. ~1.3TB for inference. 50+ natural and 40+ coding languages. Trained between December 2023 and May 2024. MMLU 0-shot for instruct=78.7, 5-shot for base=81.1. Permalink for paper: https://research.nvidia.com/publication/2024-06_nemotron-4-340b

## 🔗 Resources

- 🎮 [Try the Model](https://build.nvidia.com/nvidia/nemotron-4-340b-instruct)
- 📄 [Technical Documentation](https://d1qx31qr3h6wln.cloudfront.net/publications/Nemotron_4_340B_8T.pdf)

## 🔍 Related Models

**From NVIDIA:**
- See all models in [NVIDIA profile](../../labs/nvidia.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All NVIDIA Models](../../labs/nvidia.md)
