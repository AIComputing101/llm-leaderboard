# nGPT

> Large Language Model

**Organization:** [NVIDIA](../../labs/nvidia.md)
**Released:** Oct/2024
**Access:** 🟢 Public

---

## 📊 Overview

nGPT is a large language model developed by NVIDIA.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 1.0B
- **Training Tokens:** 400.0B
- **Token:Param Ratio:** 400:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.1 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

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

"a novel neural network architecture, the normalized Transformer (nGPT) with representation learning on the hypersphere. In nGPT, all vectors forming the embeddings, MLP, attention matrices and hidden states are unit norm normalized...reducing the number of training steps required to achieve the same accuracy by a factor of 4 to 20, depending on the sequence length."

## 🔗 Resources

- 🎮 [Try the Model](https://github.com/lucidrains/nGPT-pytorch)
- 📄 [Technical Documentation](https://arxiv.org/abs/2410.01131)

## 🔍 Related Models

**From NVIDIA:**
- See all models in [NVIDIA profile](../../labs/nvidia.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All NVIDIA Models](../../labs/nvidia.md)
