# Phi-4-mini

> Large Language Model

**Organization:** [Microsoft](../../labs/microsoft.md)
**Released:** Feb/2025
**Access:** 🟢 Public

---

## 📊 Overview

Phi-4-mini is a large language model developed by Microsoft.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 3.8B
- **Training Tokens:** 5000.0B
- **Token:Param Ratio:** 1,316:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.5 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 67.3 | General knowledge across 57 subjects |
| **MMLU-Pro** | 52.8 | Advanced MMLU variant |
| **GPQA** | 30.4 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

"Phi-4-mini’s training data includes a wide variety of sources, totaling 5 trillion tokens, and is a combination of publicly available documents filtered for quality, selected high-quality educational data, and code newly created synthetic, “textbook-like” data for the purpose of teaching math, coding, common sense reasoning, general knowledge of the world (e.g., science, daily activities, theory of mind, etc.) high quality chat format supervised data covering various topics to reflect human preferences" Announce: https://azure.microsoft.com/en-us/blog/empowering-innovation-the-next-generation-of-the-phi-family/

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/microsoft/Phi-4-mini-instruct)
- 📄 [Technical Documentation](https://huggingface.co/microsoft/Phi-4-multimodal-instruct/blob/main/phi_4_mm.tech_report.02252025.pdf)

## 🔍 Related Models

**From Microsoft:**
- See all models in [Microsoft profile](../../labs/microsoft.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Microsoft Models](../../labs/microsoft.md)
