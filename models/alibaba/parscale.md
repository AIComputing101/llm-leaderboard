# ParScale

> Large Language Model

**Organization:** [Alibaba](../../labs/alibaba.md)
**Released:** May/2025
**Access:** 🟢 Public

---

## 📊 Overview

ParScale is a large language model developed by Alibaba.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 4.7B
- **Training Tokens:** 1000.0B
- **Token:Param Ratio:** 213:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.2 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 35.1 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

"We introduce the third scaling paradigm for scaling LLMs: leverages parallel computation during both training and inference time (Parallel Scaling, or ParScale)... ParScale can use up to 22× less memory increase and 6× less latency increase compared to parameter scaling that achieves the same performance improvement. It can also recycle an off-the-shelf pre-trained model into a parallelly scaled one by post-training on a small amount of tokens, further reducing the training budget." MMLU shows for 1.8B models, not the 4.7B models.

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/ParScale/ParScale-4.7B-P8-Python)
- 📄 [Technical Documentation](https://arxiv.org/abs/2505.10475)

## 🔍 Related Models

**From Alibaba:**
- See all models in [Alibaba profile](../../labs/alibaba.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Alibaba Models](../../labs/alibaba.md)
