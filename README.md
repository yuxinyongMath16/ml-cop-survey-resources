# ml-cop-survey-resources
A curated collection of references and comparative tables for the survey on Machine Learning for Combinatorial Optimization Problems


# Machine Learning for Combinatorial Optimization: Survey Resources

## 📚 Overview
This repository contains curated resources supporting the survey paper:
**"[Your Paper Title]"** (currently under review).

## 📂 Repository Structure

### 1. References
- `/references/bibtex/all_references.bib`: Complete BibTeX file of all cited works
- `/references/bibtex/by_year/`: References organized by publication year
- `/references/bibtex/by_topic/`: References organized by research topic

### 2. Comparative Tables
- `/tables/methods_comparison.md`: Detailed comparison of ML methods for COPs
- `/tables/problems_overview.md`: Overview of combinatorial optimization problems covered
- `/tables/datasets_summary.md`: Summary of benchmark datasets

### 3. Datasets & Benchmarks
- `/datasets/links.md`: Links to publicly available datasets

### 4. Code Resources
- `/code_examples/`: Links to open-source implementations of discussed methods

## 📊 Main Comparative Table (Preview)

| Method Type | Key Models | Strengths | Limitations | Applications |
|-------------|------------|-----------|-------------|--------------|
| Supervised Learning | PtrNet, GNN, Transformer | Fast inference, good convergence | Requires labeled data | TSP, VRP, JSSP |
| Reinforcement Learning | DQN, PPO, SAC | No labels needed, adaptive | Sample inefficient | Dynamic scheduling |
| Unsupervised Learning | GAN, VAE, Diffusion | Diverse solutions, no labels | Training instability | Routing, layout |
| LLM-based | GPT, Llama, Gemini | Natural language interface | Computationally expensive | Code generation |

## 🔗 Quick Links

- [View Complete References](./references/bibtex/all_references.bib)
- [Download Comparative Tables](./tables/)
- [Cite This Work](#citation)

## 📝 Citation
If you use these resources, please cite:
```bibtex
@article{yourpaper2025,
  title={Your Paper Title},
  author={Your Name and Co-authors},
  journal={Target Journal},
  year={2025}
}
