# Gemma 3

> Large Language Model

**Organization:** [Google DeepMind](../../labs/google-deepmind.md)
**Released:** Mar/2025
**Access:** 🟢 Public

---

## 📊 Overview

Gemma 3 is a large language model developed by Google DeepMind.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 27.0B
- **Training Tokens:** 14000.0B
- **Token:Param Ratio:** 519:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 2.0 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 78.6 | General knowledge across 57 subjects |
| **MMLU-Pro** | 67.5 | Advanced MMLU variant |
| **GPQA** | 42.4 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Trained on 1T more tokens than Gemma 2. "introduces vision understanding abilities, a wider coverage of languages and longer context – at least 128K tokens."

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/ggml-org/gemma-3-27b-it-GGUF)
- 📄 [Technical Documentation](https://storage.googleapis.com/deepmind-media/gemma/Gemma3Report.pdf)

## 🔍 Related Models

**From Google DeepMind:**
- See all models in [Google DeepMind profile](../../labs/google-deepmind.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Google DeepMind Models](../../labs/google-deepmind.md)
