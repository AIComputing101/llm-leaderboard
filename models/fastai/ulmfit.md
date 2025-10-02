# ULMFiT

> Large Language Model

**Organization:** [Fast.ai](../../labs/fastai.md)
**Released:** Jan/2018
**Access:** 🟢 Public

---

## 📊 Overview

ULMFiT is a large language model developed by Fast.ai.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 0.034B
- **Training Tokens:** 1.44B
- **Token:Param Ratio:** 43:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.0
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** wiki

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

"ULMFiT — 103 M tokens corpus × 14 epochs → 1.44 B tokens processed" "Corpus size. WikiText-103 contains about 103 million word-level tokens. Training schedule. The reference pre-training run trains for 14 full epochs on that corpus. Total tokens seen. 103 M tokens × 14 epochs → roughly 1.44 billion token prediction steps." Aussie Prof Jeremy Howard: https://www.abc.net.au/news/science/2023-11-15/jeremy-howard-taught-ai-to-the-world-and-helped-invent-chatgpt/103092474

## 🔗 Resources

- 🎮 [Try the Model](https://docs.fast.ai/tutorial.text.html)
- 📄 [Technical Documentation](https://arxiv.org/abs/1801.06146)

## 🔍 Related Models

**From Fast.ai:**
- See all models in [Fast.ai profile](../../labs/fastai.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Fast.ai Models](../../labs/fastai.md)
