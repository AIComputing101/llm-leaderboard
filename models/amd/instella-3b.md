# Instella-3B

> Large Language Model

**Organization:** [AMD](../../labs/amd.md)
**Released:** Mar/2025
**Access:** 🟢 Public

---

## 📊 Overview

Instella-3B is a large language model developed by AMD.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 3.0B
- **Training Tokens:** 4160.0B
- **Token:Param Ratio:** 1,387:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.4 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 58.31 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | 30.13 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

"trained from scratch on AMD Instinct™ MI300X GPUs. Instella models outperform existing fully open models of similar sizes and achieve competitive performance compared to state-of-the-art open-weight models such as Llama-3.2-3B, Gemma-2-2B, and Qwen-2.5-3B, including their instruction-tuned counterparts."

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/amd/Instella-3B)
- 📄 [Technical Documentation](https://rocm.blogs.amd.com/artificial-intelligence/introducing-instella-3B/README.html)

## 🔍 Related Models

**From AMD:**
- See all models in [AMD profile](../../labs/amd.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All AMD Models](../../labs/amd.md)
