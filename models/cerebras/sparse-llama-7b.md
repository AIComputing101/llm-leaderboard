# Sparse Llama 7B

> Large Language Model

**Organization:** [Cerebras](../../labs/cerebras.md)
**Released:** May/2024
**Access:** 🟢 Public

---

## 📊 Overview

Sparse Llama 7B is a large language model developed by Cerebras.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Hybrid
- **Parameters:** 7.0B
- **Training Tokens:** 145.0B
- **Token:Param Ratio:** 21:1 ✅ Compute-optimal

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

https://www.cerebras.net/blog/introducing-sparse-llama-70-smaller-3x-faster-full-accuracy "For the 50% sparse model, we utilized 45 billion tokens of pretraining data, while an additional 100 billion tokens were used for the 70% model. This represents approximately 2% to 8% of the original 2 trillion tokens used to train the base Llama-2 model."

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/spaces/neuralmagic/llama-2-sparse-transfer-chat-deepsparse)
- 📄 [Technical Documentation](https://arxiv.org/abs/2405.03594)

## 🔍 Related Models

**From Cerebras:**
- See all models in [Cerebras profile](../../labs/cerebras.md)

**Similar Architecture:**
- See all [Hybrid models](../../architectures/hybrid.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Cerebras Models](../../labs/cerebras.md)
