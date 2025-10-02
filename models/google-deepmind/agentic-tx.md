# Agentic-Tx

> Large Language Model

**Organization:** [Google DeepMind](../../labs/google-deepmind.md)
**Released:** Mar/2025
**Access:** 🟢 Public

---

## 📊 Overview

Agentic-Tx is a large language model developed by Google DeepMind.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 400.0B
- **Training Tokens:** 20000.0B
- **Token:Param Ratio:** 50:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 9.4 (Powerful)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | 62.4 | Graduate-level reasoning |
| **HLE** | 14.5 | High-level evaluation |

**Analysis:** Good reasoning capabilities on GPQA (60-80%).

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

"a therapeutics-focused agentic system powered by Gemini 2.0 Pro. Agentic-Tx is equipped with 18 tools, including: TxGemma as a tool for multi-step reasoning"

## 🔗 Resources

- 🎮 [Try the Model](https://github.com/google-gemini/gemma-cookbook/blob/main/TxGemma/%5BTxGemma%5DAgentic_Demo_with_Hugging_Face.ipynb)
- 📄 [Technical Documentation](https://storage.googleapis.com/research-media/txgemma/txgemma-report.pdf)

## 🔍 Related Models

**From Google DeepMind:**
- See all models in [Google DeepMind profile](../../labs/google-deepmind.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Google DeepMind Models](../../labs/google-deepmind.md)
