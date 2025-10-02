# dots.llm1

> Large Language Model

**Organization:** [Xiaohongshu/RedNote](../../labs/xiaohongshurednote.md)
**Released:** Jun/2025
**Access:** 🟢 Public

---

## 📊 Overview

dots.llm1 is a large language model developed by Xiaohongshu/RedNote.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 142.0B
- **Training Tokens:** 11200.0B
- **Token:Param Ratio:** 79:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 4.2 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 83.2 | General knowledge across 57 subjects |
| **MMLU-Pro** | 61.9 | Advanced MMLU variant |
| **GPQA** | 52.6 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

142B-A14B. "dots.llm1, a large-scale MoE model that activates 14 billion parameters out of a total of 142 billion parameters, delivering performance on par with state-of-the-art models while reducing training and inference costs. Leveraging our meticulously crafted and efficient data processing pipeline, dots.llm1 achieves performance comparable to Qwen2.5-72B after pretraining on 11.2T high-quality tokens and post-training to fully unlock its capabilities. Notably, no synthetic data is used during pretraining. To foster further research, we open-source intermediate training checkpoints at every one trillion tokens, providing valuable insights into the learning dynamics of large language models."

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/rednote-hilab/dots.llm1.base)
- 📄 [Technical Documentation](https://github.com/rednote-hilab/dots.llm1/blob/main/dots1_tech_report.pdf)

## 🔍 Related Models

**From Xiaohongshu/RedNote:**
- See all models in [Xiaohongshu/RedNote profile](../../labs/xiaohongshurednote.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Xiaohongshu/RedNote Models](../../labs/xiaohongshurednote.md)
