# H2O-Danube3-4B

> Large Language Model

**Organization:** [H2O.ai](../../labs/h2oai.md)
**Released:** Jul/2024
**Access:** 🟢 Public

---

## 📊 Overview

H2O-Danube3-4B is a large language model developed by H2O.ai.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 4.0B
- **Training Tokens:** 6000.0B
- **Token:Param Ratio:** 1,500:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.5 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 55.18 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Runs natively and fully offline on mobile phone. "H2O-Danube3 is a family of decoder only LLM models that use the general Llama model architecture adopting core principles from Llama 2 and Mistral with custom parameters determining the shape of each layer and total parameter count. We use the Mistral tokenizer..." MMLU for chat=54.74, base=55.18 via https://huggingface.co/h2oai/h2o-danube3-4b-base

## 🔗 Resources

- 🎮 [Try the Model](https://h2o.ai/platform/danube/personal-gpt/)
- 📄 [Technical Documentation](https://arxiv.org/abs/2407.09276)

## 🔍 Related Models

**From H2O.ai:**
- See all models in [H2O.ai profile](../../labs/h2oai.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All H2O.ai Models](../../labs/h2oai.md)
