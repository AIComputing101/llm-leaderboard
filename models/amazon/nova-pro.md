# Nova Pro

> Large Language Model

**Organization:** [Amazon](../../labs/amazon.md)
**Released:** Dec/2024
**Access:** 🟢 Public

---

## 📊 Overview

Nova Pro is a large language model developed by Amazon.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 90.0B
- **Training Tokens:** 10000.0B
- **Token:Param Ratio:** 112:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 3.2 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 85.9 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | 46.9 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Multimodal, same performance as Llama 3.2 90B ∴ est 90B. Model card was hidden: https://assets.amazon.science/9f/a3/ae41627f4ab2bde091f1ebc6b830/the-amazon-nova-family-of-models-technical-report-and-model-card.pdf via https://www.amazon.science/publications/the-amazon-nova-family-of-models-technical-report-and-model-card

## 🔗 Resources

- 🎮 [Try the Model](https://aws.amazon.com/bedrock/)
- 📄 [Technical Documentation](https://www.amazon.science/publications/the-amazon-nova-family-of-models-technical-report-and-model-card)

## 🔍 Related Models

**From Amazon:**
- See all models in [Amazon profile](../../labs/amazon.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Amazon Models](../../labs/amazon.md)
