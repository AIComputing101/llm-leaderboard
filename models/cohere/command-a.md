# Command A

> Large Language Model

**Organization:** [Cohere](../../labs/cohere.md)
**Released:** Mar/2025
**Access:** 🟢 Public

---

## 📊 Overview

Command A is a large language model developed by Cohere.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 111.0B
- **Training Tokens:** 8000.0B
- **Token:Param Ratio:** 73:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 3.1 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 85.0 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Context=256k. "Command A is an open weights research release of a 111 billion parameter model optimized for demanding enterprises that require fast, secure, and high-quality AI. Compared to other leading proprietary and open-weights models Command A delivers maximum performance with minimum hardware costs, excelling on business-critical agentic and multilingual tasks while‬ being deployable on just two GPUs."

## 🔗 Resources

- 🎮 [Try the Model](https://dashboard.cohere.com/playground/chat)
- 📄 [Technical Documentation](https://huggingface.co/CohereForAI/c4ai-command-a-03-2025)

## 🔍 Related Models

**From Cohere:**
- See all models in [Cohere profile](../../labs/cohere.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Cohere Models](../../labs/cohere.md)
