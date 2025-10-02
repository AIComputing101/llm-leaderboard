# Mu

> Large Language Model

**Organization:** [Microsoft](../../labs/microsoft.md)
**Released:** Jun/2025
**Access:** 🟢 Public

---

## 📊 Overview

Mu is a large language model developed by Microsoft.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 0.5B
- **Training Tokens:** 500.0B
- **Token:Param Ratio:** 1,000:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.1 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

"distillation from Microsoft’s Phi models...Mu is an efficient 330M encoder–decoder language model optimized for small-scale deployment, particularly on the NPUs on Copilot+ PCs. It follows a transformer encoder–decoder architecture"

## 🔗 Resources

- 🎮 [Try the Model](https://blogs.windows.com/windows-insider/2025/06/13/announcing-windows-11-insider-preview-build-26200-5651-dev-channel/)
- 📄 [Technical Documentation](https://blogs.windows.com/windowsexperience/2025/06/23/introducing-mu-language-model-and-how-it-enabled-the-agent-in-windows-settings/)

## 🔍 Related Models

**From Microsoft:**
- See all models in [Microsoft profile](../../labs/microsoft.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Microsoft Models](../../labs/microsoft.md)
