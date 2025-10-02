# Arctic

> Large Language Model

**Organization:** [Snowflake AI Research](../../labs/snowflake-ai-research.md)
**Released:** Apr/2024
**Access:** 🟢 Public

---

## 📊 Overview

Arctic is a large language model developed by Snowflake AI Research.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Hybrid
- **Parameters:** 480.0B
- **Training Tokens:** 3500.0B
- **Token:Param Ratio:** 8:1 ⚠️ Under-trained

### Training Efficiency
- **ALScore:** 4.3 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 67.3 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

"Arctic uses a unique Dense-MoE Hybrid transformer architecture. It combines a 10B dense transformer model with a residual 128×3.66B MoE MLP resulting in 480B total and 17B active parameters chosen using a top-2 gating."

## 🔗 Resources

- 🎮 [Try the Model](https://arctic.streamlit.app/)
- 📄 [Technical Documentation](https://www.snowflake.com/blog/arctic-open-efficient-foundation-language-models-snowflake/)

## 🔍 Related Models

**From Snowflake AI Research:**
- See all models in [Snowflake AI Research profile](../../labs/snowflake-ai-research.md)

**Similar Architecture:**
- See all [Hybrid models](../../architectures/hybrid.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Snowflake AI Research Models](../../labs/snowflake-ai-research.md)
