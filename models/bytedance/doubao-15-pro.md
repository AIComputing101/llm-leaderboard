# Doubao-1.5-pro

> Reasoning

**Organization:** [ByteDance](../../labs/bytedance.md)
**Released:** Jan/2025
**Access:** 🟢 Public

---

## 📊 Overview

Doubao-1.5-pro is designed for advanced reasoning and multi-step problem solving.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 300.0B
- **Training Tokens:** 9000.0B
- **Token:Param Ratio:** 30:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 5.5 (Powerful)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 88.6 | General knowledge across 57 subjects |
| **MMLU-Pro** | 80.1 | Advanced MMLU variant |
| **GPQA** | 65.0 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

**Analysis:** Good reasoning capabilities on GPQA (60-80%).

## 🏷️ Model Tags

`Reasoning`

## 📝 Additional Notes

Includes 2.4B param ViT. "Doubao-1.5-pro uses a sparse MoE architecture. In the pre-training stage, the performance of the MoE model activated with only a small number of parameters can exceed that of ultra-large dense pre-trained models such as Llama3.1-405B. Through the study of the sparsity scaling law, the team determined the sparse ratio that balances performance and efficiency, and determined based on the MoE scaling law that a model activated with a small number of parameters can achieve the performance of a world-class model."

## 🔗 Resources

- 🎮 [Try the Model](https://www.volcengine.com/docs/82379/1330310#474f7dec)
- 📄 [Technical Documentation](https://team.doubao.com/en/special/doubao_1_5_pro)

## 🔍 Related Models

**From ByteDance:**
- See all models in [ByteDance profile](../../labs/bytedance.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All ByteDance Models](../../labs/bytedance.md)
