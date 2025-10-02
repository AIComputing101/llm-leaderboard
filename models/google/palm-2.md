# PaLM 2

> SOTA

**Organization:** [Google](../../labs/google.md)
**Released:** May/2023
**Access:** 🟢 Public

---

## 📊 Overview

PaLM 2 represents state-of-the-art performance in its category.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 340.0B
- **Training Tokens:** 3600.0B
- **Token:Param Ratio:** 11:1 ⚠️ Under-trained

### Training Efficiency
- **ALScore:** 3.7 (Mid-tier)
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

`SOTA`

## 📝 Additional Notes

“What we found in our work is that it’s not really the sort of size of model — that the larger is not always better,” Deepmind VP Zoubin Ghahramani said in a press briefing ahead of today’s announcement. “That’s why we’ve provided a family of models of different sizes. We think that actually parameter count is not really a useful way of thinking about the capabilities of models and capabilities are really to be judged by people using the models and finding out whether they’re useful in the tests that they try to achieve with these models.”

## 🔗 Resources

- 🎮 [Try the Model](https://console.cloud.google.com/vertex-ai/generative/language/create/chat)
- 📄 [Technical Documentation](https://ai.google/static/documents/palm2techreport.pdf)

## 🔍 Related Models

**From Google:**
- See all models in [Google profile](../../labs/google.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Google Models](../../labs/google.md)
