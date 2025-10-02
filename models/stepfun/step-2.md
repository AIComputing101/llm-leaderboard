# Step-2

> Large Language Model

**Organization:** [StepFun](../../labs/stepfun.md)
**Released:** Jul/2024
**Access:** 🟢 Public

---

## 📊 Overview

Step-2 is a large language model developed by StepFun.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 1000.0B
- **Training Tokens:** 13000.0B
- **Token:Param Ratio:** 13:1 ⚠️ Under-trained

### Training Efficiency
- **ALScore:** 12.0 (Very powerful)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 82.9 | General knowledge across 57 subjects |
| **MMLU-Pro** | 63.0 | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Launched early Jul/2024: https://pandaily.com/stepfun-releases-three-large-models-of-the-step-series/ "StepFun, founded in April 2023 with the mission to “Scale-up possibilities for everyone,” unites top talent in artificial intelligence from both domestic and international backgrounds, and is dedicated to advancing toward AGI. The company has already launched the Step series of foundation models, which includes Step-2, a cutting-edge trillion-parameter Mixture of Experts (MoE) language model; Step-1.5V, a powerful multimodal large model; and Step-1V, an innovative image generation model, among others."

## 🔗 Resources

- 🎮 [Try the Model](https://platform.stepfun.com/#language-step2)
- 📄 [Technical Documentation](https://platform.stepfun.com/docs/llm/text)

## 🔍 Related Models

**From StepFun:**
- See all models in [StepFun profile](../../labs/stepfun.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All StepFun Models](../../labs/stepfun.md)
