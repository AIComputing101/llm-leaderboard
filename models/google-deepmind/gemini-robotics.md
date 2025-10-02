# Gemini Robotics

> Large Language Model

**Organization:** [Google DeepMind](../../labs/google-deepmind.md)
**Released:** Mar/2025
**Access:** 🔴 Private

---

## 📊 Overview

Gemini Robotics is a large language model developed by Google DeepMind.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 200.0B
- **Training Tokens:** 20000.0B
- **Token:Param Ratio:** 100:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 6.7 (Powerful)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | 79.1 | Advanced MMLU variant |
| **GPQA** | 64.7 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Good reasoning capabilities on GPQA (60-80%).

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Gemini 2.0 Pro (cloud). "The second model is Gemini Robotics, a state-of-theart Vision-Language-Action (VLA) model that connects strong embodied reasoning priors to dexterous low-level control of real-world robots to solve challenging manipulation tasks. As a generalist VLA, Gemini Robotics can perform a wide array of diverse and complicated tasks, while also closely following language guidance and generalizing to distribution shifts in instructions, visuals, and motions. To emphasize the flexibility and generality of the Gemini Robotics models, we also introduce an optional specialization stage, which demonstrates how Gemini Robotics can be adapted for extreme dexterity, for advanced reasoning in difficult generalization settings, and for controlling completely new robot embodiments."

## 🔗 Resources

- 📄 [Technical Documentation](https://storage.googleapis.com/deepmind-media/gemini-robotics/gemini_robotics_report.pdf)

## 🔍 Related Models

**From Google DeepMind:**
- See all models in [Google DeepMind profile](../../labs/google-deepmind.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Google DeepMind Models](../../labs/google-deepmind.md)
