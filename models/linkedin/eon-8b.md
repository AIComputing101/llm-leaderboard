# EON-8B

> Large Language Model

**Organization:** [LinkedIn](../../labs/linkedin.md)
**Released:** Dec/2024
**Access:** 🔴 Private

---

## 📊 Overview

EON-8B is a large language model developed by LinkedIn.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 8.0B
- **Training Tokens:** 15000.0B
- **Token:Param Ratio:** 1,875:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 1.2 (Mid-tier)
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

"We found the EON-8B model (a domain-adapted Llama 3.1-8B variant) to be 75x and 6x cost effective in comparison to GPT-4 and GPT-4o respectively (Figure 4)... On tasks seen during training, the EON-8B model outperformed base Llama-3-8B-Instruct and its performance was comparable to SOTA GPT models."

## 🔗 Resources

- 🎮 [Try the Model](https://www.linkedin.com/blog/engineering/generative-ai/how-we-built-domain-adapted-foundation-genai-models-to-power-our-platform)
- 📄 [Technical Documentation](https://www.linkedin.com/blog/engineering/generative-ai/how-we-built-domain-adapted-foundation-genai-models-to-power-our-platform)

## 🔍 Related Models

**From LinkedIn:**
- See all models in [LinkedIn profile](../../labs/linkedin.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All LinkedIn Models](../../labs/linkedin.md)
