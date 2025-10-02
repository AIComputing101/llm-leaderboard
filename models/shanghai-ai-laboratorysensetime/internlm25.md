# InternLM2.5

> Large Language Model

**Organization:** [Shanghai AI Laboratory/SenseTime](../../labs/shanghai-ai-laboratorysensetime.md)
**Released:** Jul/2024
**Access:** 🟢 Public

---

## 📊 Overview

InternLM2.5 is a large language model developed by Shanghai AI Laboratory/SenseTime.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 20.0B
- **Training Tokens:** 2600.0B
- **Token:Param Ratio:** 130:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.8 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 73.5 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | 38.4 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

"The release of InternLM2.5 series contains 7B model size for now and we are going to release the 1.8B and 20B versions soon" [20B released around 1/Aug/2024]

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/internlm/internlm2_5-20b-chat)
- 📄 [Technical Documentation](https://github.com/InternLM/InternLM/blob/main/model_cards/internlm2.5_7b.md)

## 🔍 Related Models

**From Shanghai AI Laboratory/SenseTime:**
- See all models in [Shanghai AI Laboratory/SenseTime profile](../../labs/shanghai-ai-laboratorysensetime.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Shanghai AI Laboratory/SenseTime Models](../../labs/shanghai-ai-laboratorysensetime.md)
