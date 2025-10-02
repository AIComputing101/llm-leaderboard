# LearnLM

> Large Language Model

**Organization:** [Google DeepMind](../../labs/google-deepmind.md)
**Released:** May/2024
**Access:** ❓ Unknown

---

## 📊 Overview

LearnLM is a large language model developed by Google DeepMind.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
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
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | 72.0 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Good reasoning capabilities on GPQA (60-80%).

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Fine-tuned + prompted Gemini (Dec/2023). "The results of LearnLM-Tutor reproduce the performance of Gemini Pro, for example an MMLU score of 0.72 and MATH score of 0.33."

## 🔗 Resources

- 🎮 [Try the Model](https://learning.google.com/experiments/learn-about/signup)
- 📄 [Technical Documentation](https://storage.googleapis.com/deepmind-media/LearnLM/LearnLM_paper.pdf)

## 🔍 Related Models

**From Google DeepMind:**
- See all models in [Google DeepMind profile](../../labs/google-deepmind.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Google DeepMind Models](../../labs/google-deepmind.md)
