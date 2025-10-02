# HLAT

> Large Language Model

**Organization:** [Amazon](../../labs/amazon.md)
**Released:** Apr/2024
**Access:** 🔴 Private

---

## 📊 Overview

HLAT is a large language model developed by Amazon.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 7.0B
- **Training Tokens:** 1800.0B
- **Token:Param Ratio:** 258:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.4 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 41.318 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

HLAT=High-quality LLM pre-trained on AWS Trainium. Same arch as Llama 7B. The pre-training is performed up to 64 Amazon EC2 trn1.32xlarge instances with totalling up to 1024 AWS Trainium accelerators. Read more about Trainium: https://www.aboutamazon.com/news/aws/what-you-need-to-know-about-the-aws-ai-chips-powering-amazons-partnership-with-anthropic

## 🔗 Resources

- 📄 [Technical Documentation](https://arxiv.org/abs/2404.10630)

## 🔍 Related Models

**From Amazon:**
- See all models in [Amazon profile](../../labs/amazon.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Amazon Models](../../labs/amazon.md)
