# Step 3

> Large Language Model

**Organization:** [StepFun](../../labs/stepfun.md)
**Released:** Jul/2025
**Access:** 🟢 Public

---

## 📊 Overview

Step 3 is a large language model developed by StepFun.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 321.0B
- **Training Tokens:** 18000.0B
- **Token:Param Ratio:** 57:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 8.0 (Powerful)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | 72.9 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Good reasoning capabilities on GPQA (60-80%).

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

321B-A38B. https://x.com/CyouSakura/status/1948767450751009227

## 🔗 Resources

- 🎮 [Try the Model](https://www.stepfun.com/)
- 📄 [Technical Documentation](https://github.com/stepfun-ai/Step3/blob/main/Step3-Sys-Tech-Report.pdf)

## 🔍 Related Models

**From StepFun:**
- See all models in [StepFun profile](../../labs/stepfun.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All StepFun Models](../../labs/stepfun.md)
