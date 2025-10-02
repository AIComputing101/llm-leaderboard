# Intern-S1

> Reasoning, SOTA

**Organization:** [Shanghai AI Laboratory/SenseTime](../../labs/shanghai-ai-laboratorysensetime.md)
**Released:** Jul/2025
**Access:** 🟢 Public

---

## 📊 Overview

Intern-S1 represents state-of-the-art performance in its category, with advanced reasoning capabilities.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 235.0B
- **Training Tokens:** 41000.0B
- **Token:Param Ratio:** 175:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 10.3 (Very powerful)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | 83.5 | Advanced MMLU variant |
| **GPQA** | 77.3 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Good reasoning capabilities on GPQA (60-80%).

## 🏷️ Model Tags

`Reasoning`, `SOTA`

## 📝 Additional Notes

41T tokens assumes base model of Qwen3. "Built upon a 235B MoE language model and a 6B Vision encoder, Intern-S1 has been further pretrained on 5 trillion tokens of multimodal data"

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/internlm/Intern-S1)
- 📄 [Technical Documentation](https://huggingface.co/internlm/Intern-S1)

## 🔍 Related Models

**From Shanghai AI Laboratory/SenseTime:**
- See all models in [Shanghai AI Laboratory/SenseTime profile](../../labs/shanghai-ai-laboratorysensetime.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Shanghai AI Laboratory/SenseTime Models](../../labs/shanghai-ai-laboratorysensetime.md)
