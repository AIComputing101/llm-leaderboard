# Llama-3.3-Nemotron-Super-49B-v1

> Reasoning

**Organization:** [NVIDIA](../../labs/nvidia.md)
**Released:** Mar/2025
**Access:** 🟢 Public

---

## 📊 Overview

Llama-3.3-Nemotron-Super-49B-v1 is designed for advanced reasoning and multi-step problem solving.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 49.0B
- **Training Tokens:** 15040.0B
- **Token:Param Ratio:** 307:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 2.9 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | 66.67 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Good reasoning capabilities on GPQA (60-80%).

## 🏷️ Model Tags

`Reasoning`

## 📝 Additional Notes

Meta Llama-3.3-70B-Instruct derivative "that is post trained for reasoning, human chat preferences, and tasks, such as RAG and tool calling. The model supports a context length of 128K tokens."

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/nvidia/Llama-3_3-Nemotron-Super-49B-v1)
- 📄 [Technical Documentation](https://build.nvidia.com/nvidia/llama-3_3-nemotron-super-49b-v1/modelcard)

## 🔍 Related Models

**From NVIDIA:**
- See all models in [NVIDIA profile](../../labs/nvidia.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All NVIDIA Models](../../labs/nvidia.md)
