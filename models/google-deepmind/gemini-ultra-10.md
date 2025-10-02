# Gemini Ultra 1.0

> SOTA

**Organization:** [Google DeepMind](../../labs/google-deepmind.md)
**Released:** Dec/2023
**Access:** 🟢 Public

---

## 📊 Overview

Gemini Ultra 1.0 represents state-of-the-art performance in its category.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 1500.0B
- **Training Tokens:** 30000.0B
- **Token:Param Ratio:** 20:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 22.4 (Extremely powerful)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 83.7 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | 35.7 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

## 🏷️ Model Tags

`SOTA`

## 📝 Additional Notes

Original MMLU=83.7. MMLU=90.04 with prompting. Chinchilla (20:1), dense, maybe 600B-2000T. Note: Gemini outputs are watermarked. I do not use GDM models.

## 🔗 Resources

- 🎮 [Try the Model](https://deepmind.google/technologies/gemini/)
- 📄 [Technical Documentation](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf)

## 🔍 Related Models

**From Google DeepMind:**
- See all models in [Google DeepMind profile](../../labs/google-deepmind.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Google DeepMind Models](../../labs/google-deepmind.md)
