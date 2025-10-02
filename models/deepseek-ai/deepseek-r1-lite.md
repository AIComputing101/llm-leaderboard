# DeepSeek-R1-Lite

> Reasoning

**Organization:** [DeepSeek-AI](../../labs/deepseek-ai.md)
**Released:** Nov/2024
**Access:** 🟢 Public

---

## 📊 Overview

DeepSeek-R1-Lite is designed for advanced reasoning and multi-step problem solving.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 67.0B
- **Training Tokens:** 2000.0B
- **Token:Param Ratio:** 30:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 1.2 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | 58.5 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

`Reasoning`

## 📝 Additional Notes

Scores 0/5 on latest ALPrompt 2024 H2 "DeepSeek-R1-Lite is currently still in the iterative development stage. It currently only supports web usage and does not support API calls. The base model used by DeepSeek-R1-Lite is also a relatively small model, unable to fully unleash the potential of long reasoning chains. At present, we are continuously iterating on the inference series models. In the future, the official DeepSeek-R1 model will be fully open-sourced. We will publicly release the technical report and deploy API services." https://mp-weixin-qq-com.translate.goog/s/e1YnTxZlzFvjcmrLLTA8fw?_x_tr_sl=zh-CN&_x_tr_tl=en&_x_tr_hl=zh-TW

## 🔗 Resources

- 🎮 [Try the Model](https://chat.deepseek.com/)
- 📄 [Technical Documentation](https://x.com/deepseek_ai/status/1859200141355536422)

## 🔍 Related Models

**From DeepSeek-AI:**
- See all models in [DeepSeek-AI profile](../../labs/deepseek-ai.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All DeepSeek-AI Models](../../labs/deepseek-ai.md)
