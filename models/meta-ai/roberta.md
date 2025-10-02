# RoBERTa

> Large Language Model

**Organization:** [Meta AI](../../labs/meta-ai.md)
**Released:** Jul/2019
**Access:** 🟢 Public

---

## 📊 Overview

RoBERTa is a large language model developed by Meta AI.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 0.355B
- **Training Tokens:** 2200.0B
- **Token:Param Ratio:** 6,198:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.1 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 27.9 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

calcs: "In total, this batch size and number of steps corresponds to pre-training on 235 ≈ 34B tokens. This is considerably less than BERT (Devlin et al., 2018), which used roughly 137B tokens, or RoBERTa (Liu et al., 2019c), which used roughly 2.2T tokens. Using only 2 35 tokens results in a reasonable computational budget while still providing a sufficient amount of pre-training for acceptable performance. We consider the effect of pre-training for more steps in Sections 3.6 and 3.7. Note that 2 35 tokens only covers a fraction of the entire C4 data set, so we never repeat any data during pre-training." https://arxiv.org/pdf/1910.10683.pdf MMLU shows RoBERTa-base 125M only=27.9 (not 355M)

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/FacebookAI/roberta-large)
- 📄 [Technical Documentation](https://arxiv.org/abs/1907.11692)

## 🔍 Related Models

**From Meta AI:**
- See all models in [Meta AI profile](../../labs/meta-ai.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Meta AI Models](../../labs/meta-ai.md)
