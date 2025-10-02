# Causal Axioms

> Large Language Model

**Organization:** [Microsoft](../../labs/microsoft.md)
**Released:** Jul/2024
**Access:** 🔴 Private

---

## 📊 Overview

Causal Axioms is a large language model developed by Microsoft.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 0.067B
- **Training Tokens:** 1.2B
- **Token:Param Ratio:** 18:1 ⚠️ Under-trained

### Training Efficiency
- **ALScore:** 0.0
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

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

"the training dataset follows a specific structure, we develop a custom tokenizer. Alphanumeric node names are tokenized at a character level, while special terms such as ‘causes’, ‘Does’, ‘cause’, ‘Yes’, and ‘No’ are tokenized at the word level... Our training setup consists of around 175k instances of sequential chains with size of chains ranging from 3 to 6 nodes... All models are trained for 100 epochs. [LifeArchitect.ai estimate is 12 tokens per node x 6 nodes x 175,000 instances x 100 epochs = 1.26B tokens]" Based on GPT-2 arch.

## 🔗 Resources

- 📄 [Technical Documentation](https://arxiv.org/abs/2407.07612v1)

## 🔍 Related Models

**From Microsoft:**
- See all models in [Microsoft profile](../../labs/microsoft.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Microsoft Models](../../labs/microsoft.md)
