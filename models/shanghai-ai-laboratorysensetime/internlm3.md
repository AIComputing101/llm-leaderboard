# InternLM3

> Large Language Model

**Organization:** [Shanghai AI Laboratory/SenseTime](../../labs/shanghai-ai-laboratorysensetime.md)
**Released:** Jan/2025
**Access:** 🟢 Public

---

## 📊 Overview

InternLM3 is a large language model developed by Shanghai AI Laboratory/SenseTime.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 8.0B
- **Training Tokens:** 4000.0B
- **Token:Param Ratio:** 500:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.6 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 76.6 | General knowledge across 57 subjects |
| **MMLU-Pro** | 57.6 | Advanced MMLU variant |
| **GPQA** | 37.4 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

"InternLM3 is trained on only 4 trillion high-quality tokens, saving more than 75% of the training cost compared to other LLMs of similar scale." Playground: https://internlm-chat.intern-ai.org.cn/

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/internlm/internlm3-8b-instruct)
- 📄 [Technical Documentation](https://huggingface.co/internlm/internlm3-8b-instruct)

## 🔍 Related Models

**From Shanghai AI Laboratory/SenseTime:**
- See all models in [Shanghai AI Laboratory/SenseTime profile](../../labs/shanghai-ai-laboratorysensetime.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Shanghai AI Laboratory/SenseTime Models](../../labs/shanghai-ai-laboratorysensetime.md)
