# o3-mini

> Reasoning

**Organization:** [OpenAI](../../labs/openai.md)
**Released:** Jan/2025
**Access:** 🟢 Public

---

## 📊 Overview

o3-mini is designed for advanced reasoning and multi-step problem solving.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 20.0B
- **Training Tokens:** 13000.0B
- **Token:Param Ratio:** 650:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 1.7 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | 77.0 | Graduate-level reasoning |
| **HLE** | 14.0 | High-level evaluation |

**Analysis:** Good reasoning capabilities on GPQA (60-80%).

## 🏷️ Model Tags

`Reasoning`

## 📝 Additional Notes

GPQA=79.7 for 'high' thinking. ALPrompt 2025H1=1/5. My analysis is that this model’s performance is very poor, with responses often becoming disordered and illogical. OpenAI compared o3-mini to OpenAI’s software engineers, and it performed very poorly (o3-mini=0%, o1=12%). "o3-mini models have the lowest performance, with scores of 0%… We suspect o3-mini’s low performance is due to poor instruction following and confusion about specifying tools in the correct format. The model often attempts to use a hallucinated bash tool rather than python despite constant, multi-shot prompting and feedback that this format is incorrect. This resulted in long conversations that likely hurt its performance." (o3-mini paper, p31)

## 🔗 Resources

- 🎮 [Try the Model](https://chatgpt.com/?model=o3-mini)
- 📄 [Technical Documentation](https://openai.com/index/o3-mini-system-card/)

## 🔍 Related Models

**From OpenAI:**
- See all models in [OpenAI profile](../../labs/openai.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All OpenAI Models](../../labs/openai.md)
