# OpenELM

> Large Language Model

**Organization:** [Apple](../../labs/apple.md)
**Released:** Apr/2024
**Access:** 🟢 Public

---

## 📊 Overview

OpenELM is a large language model developed by Apple.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 3.04B
- **Training Tokens:** 1500.0B
- **Token:Param Ratio:** 494:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.2 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 26.76 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

On-device model (laptop, phone). Open-source Efficient Language Models (OpenELM). https://venturebeat.com/ai/apple-releases-openelm-small-open-source-ai-models-designed-to-run-on-device/

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/apple/OpenELM-3B-Instruct)
- 📄 [Technical Documentation](https://arxiv.org/abs/2404.14619)

## 🔍 Related Models

**From Apple:**
- See all models in [Apple profile](../../labs/apple.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Apple Models](../../labs/apple.md)
