# Palmyra

> Large Language Model

**Organization:** [Writer](../../labs/writer.md)
**Released:** Feb/2023
**Access:** 🟢 Public

---

## 📊 Overview

Palmyra is a large language model developed by Writer.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 20.0B
- **Training Tokens:** 300.0B
- **Token:Param Ratio:** 15:1 ⚠️ Under-trained

### Training Efficiency
- **ALScore:** 0.3 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

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

Only up to 5B available open-source 'trained on over 300 billion tokens of text data, and the size of the resulting model is over 20 billion parameters. ' https://writer.com/product/cowrite/

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/models?search=palmyra)
- 📄 [Technical Documentation](https://writer.com/blog/palmyra/)

## 🔍 Related Models

**From Writer:**
- See all models in [Writer profile](../../labs/writer.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Writer Models](../../labs/writer.md)
