# Gemini 2.0 Flash exp

> SOTA

**Organization:** [Google DeepMind](../../labs/google-deepmind.md)
**Released:** Dec/2024
**Access:** 🟢 Public

---

## 📊 Overview

Gemini 2.0 Flash exp represents state-of-the-art performance in its category.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 30.0B
- **Training Tokens:** 30000.0B
- **Token:Param Ratio:** 1,000:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 3.2 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 87.0 | General knowledge across 57 subjects |
| **MMLU-Pro** | 76.4 | Advanced MMLU variant |
| **GPQA** | 62.1 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

**Analysis:** Good reasoning capabilities on GPQA (60-80%).

## 🏷️ Model Tags

`SOTA`

## 📝 Additional Notes

Gemini 2.0 Flash was first model released, 11/Dec/2024. "New Modalities: Gemini 2.0 introduces native image generation and controllable text-to-speech capabilities" Announce: https://blog.google/technology/google-deepmind/google-gemini-ai-update-december-2024/ Note: Gemini outputs are watermarked. I do not use GDM models.

## 🔗 Resources

- 🎮 [Try the Model](https://console.cloud.google.com/vertex-ai/generative/multimodal/create/text?model=gemini-2.0-flash-exp)
- 📄 [Technical Documentation](https://cloud.google.com/vertex-ai/generative-ai/docs/gemini-v2)

## 🔍 Related Models

**From Google DeepMind:**
- See all models in [Google DeepMind profile](../../labs/google-deepmind.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Google DeepMind Models](../../labs/google-deepmind.md)
