# Contributing to LLM Leaderboard

Thank you for your interest in contributing to the LLM Leaderboard! This document provides guidelines and instructions for contributing.

## 🌟 Ways to Contribute

### 1. Report Issues
Found incorrect information or broken links?
- Check if the issue already exists
- Open a new issue with clear details
- Include the model name and specific problem
- Provide correct information if available

### 2. Suggest New Models
Know about an LLM we're missing?
- Provide the model name and organization
- Include links to official documentation
- Share available benchmark scores
- Note the release date if known

### 3. Update Existing Information
Help keep data accurate and current:
- Correct outdated benchmarks
- Add missing information
- Fix broken links
- Update release dates

### 4. Improve Documentation
Make this resource better:
- Fix typos and grammar
- Clarify confusing sections
- Add helpful examples
- Improve organization

## 📝 Contribution Guidelines

### Data Accuracy
- **Verify Sources**: Always cite official sources for model information
- **Benchmark Scores**: Use official benchmark results when available
- **No Speculation**: Mark uncertain information clearly or omit it
- **Current Data**: Prioritize the most recent information

### Model Information Standards

When adding or updating models, include:

#### Required Information
- Model name
- Organization/Lab
- Release date (or "TBA")
- Public availability status (🟢/🔴/❓)

#### Recommended Information
- Parameters (in billions)
- Training tokens (in billions)
- Architecture type (Dense, MoE, etc.)
- Benchmark scores (MMLU, GPQA, HLE)
- Training dataset type
- Tags (SOTA, Reasoning, etc.)

#### Optional Information
- Notes about unique features
- Links to playground/demo
- Links to paper/documentation
- Context window size
- Specialized capabilities

### Link Policy

**Acceptable Links:**
- Official model documentation
- Research papers (arXiv, official publications)
- Official demos and playgrounds
- Technical blog posts from the organization
- HuggingFace model cards

**Not Acceptable:**
- Third-party reviews or summaries
- Unofficial benchmarks
- Blog posts from unrelated sources
- Marketing materials without technical content

## 🔧 Technical Contributions

### Repository Structure

```
llm-leaderboard/
├── models/           # Individual model pages by organization
│   ├── openai/
│   ├── anthropic/
│   └── ...
├── rankings/         # Different ranking views
├── labs/            # Organization profiles
├── architectures/   # Architecture-specific pages
├── insights/        # Analysis and trends
└── README.md        # Main leaderboard
```

### Model Card Template

```markdown
# Model Name

> Tags here

**Organization:** [Lab Name](../../labs/lab-name.md)
**Released:** Month/Year
**Access:** 🟢/🔴/❓

---

## 📊 Overview

Brief description of the model and its capabilities.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense/MoE/Hybrid
- **Parameters:** XB
- **Training Tokens:** XB
- **Token:Param Ratio:** X:1

### Training Efficiency
- **ALScore:** X.X

### Training Data
- **Dataset Type:** Type here

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | XX.X | General knowledge |
| **GPQA** | XX.X | Reasoning |

## 🏷️ Model Tags

`Tag1`, `Tag2`

## 📝 Additional Notes

Key information and notes.

## 🔗 Resources

- 🎮 [Try the Model](link)
- 📄 [Technical Documentation](link)

---

**Last Updated:** YYYY-MM-DD
```

## 🚀 Submission Process

### For Issues
1. Search existing issues first
2. Use the issue template
3. Provide specific details
4. Be respectful and constructive

### For Suggestions
1. Open an issue labeled "enhancement"
2. Explain the proposed change
3. Provide rationale
4. Include any relevant data/sources

### For Direct Contributions
1. Fork the repository
2. Create a feature branch
3. Make your changes following the guidelines
4. Test links and formatting
5. Submit a pull request with clear description
6. Link to relevant issues if applicable

## ✅ Checklist Before Submitting

- [ ] Information is accurate and from reliable sources
- [ ] All links are working and go to official sources
- [ ] Markdown formatting is correct
- [ ] Model card follows the template structure
- [ ] Benchmarks are from official evaluations
- [ ] No proprietary or confidential information included
- [ ] Grammar and spelling checked
- [ ] Respectful and professional tone

## 📚 Resources

### Useful Links
- [Markdown Guide](https://www.markdownguide.org/)
- [GitHub Issues Guide](https://guides.github.com/features/issues/)
- [Pull Request Guide](https://docs.github.com/en/pull-requests)

### Benchmark Information
- [MMLU Benchmark](https://github.com/hendrycks/test)
- [GPQA Dataset](https://github.com/idavidrein/gpqa)

## 💬 Questions?

- Open a discussion in the Issues tab
- Check existing documentation first
- Be specific about what you need help with

## 🙏 Thank You!

Every contribution helps make this resource better for the entire AI community. We appreciate your time and effort!

---

**Code of Conduct**: Be respectful, constructive, and collaborative. We're all here to learn and share knowledge about LLMs.
