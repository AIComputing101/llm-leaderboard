# Phi-4-mini-flash-reasoning

> Large Language Model

**Organization:** [Microsoft](../../labs/microsoft.md)
**Released:** Jul/2025
**Access:** 🟢 Public

---

## 📊 Overview

Phi-4-mini-flash-reasoning is a large language model developed by Microsoft.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 3.8B
- **Training Tokens:** 5150.0B
- **Token:Param Ratio:** 1,356:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.5 (Lightweight)
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

"Pre-training: 5T tokens; Reasoning training: 150B tokens" "At the core of Phi-4-mini-flash-reasoning is the newly introduced decoder-hybrid-decoder architecture, SambaY, whose central innovation is the Gated Memory Unit (GMU), a simple yet effective mechanism for sharing representations between layers. The architecture includes a self-decoder that combines Mamba (a State Space Model) and Sliding Window Attention (SWA), along with a single layer of full attention. The architecture also involves a cross-decoder that interleaves expensive cross-attention layers with the new, efficient GMUs. This new architecture with GMU modules drastically improves decoding efficiency, boosts long-context retrieval performance and enables the architecture to deliver exceptional performance across a wide range of tasks. "

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/microsoft/Phi-4-mini-flash-reasoning)
- 📄 [Technical Documentation](https://azure.microsoft.com/en-us/blog/reasoning-reimagined-introducing-phi-4-mini-flash-reasoning/)

## 🔍 Related Models

**From Microsoft:**
- See all models in [Microsoft profile](../../labs/microsoft.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Microsoft Models](../../labs/microsoft.md)
