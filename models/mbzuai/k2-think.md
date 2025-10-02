# K2-Think

> Reasoning

**Organization:** [MBZUAI](../../labs/mbzuai.md)
**Released:** Sep/2025
**Access:** 🟢 Public

---

## 📊 Overview

K2-Think is designed for advanced reasoning and multi-step problem solving.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 32.0B
- **Training Tokens:** 18000.0B
- **Token:Param Ratio:** 563:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 2.5 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | 71.08 | Graduate-level reasoning |
| **HLE** | 9.95 | High-level evaluation |

**Analysis:** Good reasoning capabilities on GPQA (60-80%).

## 🏷️ Model Tags

`Reasoning`

## 📝 Additional Notes

"Built on the Qwen2.5 base model, our system shows that smaller models can compete at the highest levels by combining advanced post-training and test-time computation techniques. The approach is based on six key technical pillars: Long Chain-of-thought Supervised Finetuning, Reinforcement Learning with Verifiable Rewards (RLVR), Agentic planning prior to reasoning, Test-time Scaling, Speculative Decoding, and Inference-optimized Hardware, all using publicly available open-source datasets."

## 🔗 Resources

- 🎮 [Try the Model](https://www.k2think.ai/)
- 📄 [Technical Documentation](https://arxiv.org/abs/2509.07604)

## 🔍 Related Models

**From MBZUAI:**
- See all models in [MBZUAI profile](../../labs/mbzuai.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All MBZUAI Models](../../labs/mbzuai.md)
