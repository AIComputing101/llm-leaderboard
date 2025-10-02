# InternVL 2.5

> Reasoning

**Organization:** [Shanghai AI Laboratory/SenseTime](../../labs/shanghai-ai-laboratorysensetime.md)
**Released:** Dec/2024
**Access:** 🟢 Public

---

## 📊 Overview

InternVL 2.5 is designed for advanced reasoning and multi-step problem solving.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 78.0B
- **Training Tokens:** 18120.0B
- **Token:Param Ratio:** 233:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 4.0 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 86.1 | General knowledge across 57 subjects |
| **MMLU-Pro** | 71.1 | Advanced MMLU variant |
| **GPQA** | 49.0 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

## 🏷️ Model Tags

`Reasoning`

## 📝 Additional Notes

Benchmarks are estimates based on Qwen2.5 72B Instruct as the base LLM (InternVL 2.5=InternViT-6B-448px-V2.5 5.5B + Qwen2.5-72B-Instruct). "Notably, Qwen2-VL processed a cumulative total of 1.4T tokens, while our InternVL2.5-78B is trained on just ∼120B tokens [of vision]."Dataset... we identify repetitive generation as one of the most detrimental issues. In many open-source or synthetic datasets, a small number of repetitive samples—comprising merely thousands of examples in our Stage 2 data mixture—can cause the model to spiral into repetitive loops, particularly in long-form outputs or CoT reasoning tasks. This phenomenon undermines the effectiveness of test-time scaling strategies. To address this challenge and support future research, we designed an efficient data filtering pipeline to remove low-quality samples, thereby minimizing the risk of repetitive generation." Repo: https://github.com/OpenGVLab/InternVL

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/spaces/OpenGVLab/InternVL)
- 📄 [Technical Documentation](https://arxiv.org/abs/2412.05271)

## 🔍 Related Models

**From Shanghai AI Laboratory/SenseTime:**
- See all models in [Shanghai AI Laboratory/SenseTime profile](../../labs/shanghai-ai-laboratorysensetime.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Shanghai AI Laboratory/SenseTime Models](../../labs/shanghai-ai-laboratorysensetime.md)
