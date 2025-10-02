# SFR-LLaMA-3.1-70B-Judge

> Large Language Model

**Organization:** [Salesforce](../../labs/salesforce.md)
**Released:** Sep/2024
**Access:** 🔴 Private

---

## 📊 Overview

SFR-LLaMA-3.1-70B-Judge is a large language model developed by Salesforce.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 70.0B
- **Training Tokens:** 15000.0B
- **Token:Param Ratio:** 215:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 3.4 (Mid-tier)
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

Code coming soon: https://github.com/SalesforceAIResearch/SFRJudge "we opt to focus on datasets that evaluate modern (2023 and beyond) LLM responses, as older datasets likely contain lower quality responses from less capable models, with correspondingly stale annotations. We supplement human-annotated data with synthetically generated data to endow our judge models with specific capabilities (e.g., following fine-grained rubrics in evaluation)"

## 🔗 Resources

- 🎮 [Try the Model](https://blog.salesforceairesearch.com/sfr-judge/)
- 📄 [Technical Documentation](https://arxiv.org/abs/2409.14664)

## 🔍 Related Models

**From Salesforce:**
- See all models in [Salesforce profile](../../labs/salesforce.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Salesforce Models](../../labs/salesforce.md)
