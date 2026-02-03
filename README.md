# ml-cop-survey-resources
A curated collection of references and comparative tables for the survey on Machine Learning for Combinatorial Optimization Problems


# Machine Learning for Combinatorial Optimization: Survey Resources

## 📚 Overview
This repository contains curated resources supporting the survey paper:
**"Machine Learning-Driven Combinatorial Optimization: A Systematic Review"** (currently under review).


## 📊 Main Comparative Table (Preview)

| Method Type | Key Models | Strengths | Limitations | Applications |
|-------------|------------|-----------|-------------|--------------|
| Supervised Learning | PtrNet, GNN, Transformer | Fast inference, good convergence | Requires labeled data | TSP, VRP, JSSP |
| Reinforcement Learning | DQN, PPO, SAC | No labels needed, adaptive | Sample inefficient | Dynamic scheduling |
| Unsupervised Learning | GAN, VAE, Diffusion | Diverse solutions, no labels | Training instability | Routing, layout |
| LLM-based | GPT, Llama, Gemini | Natural language interface | Computationally expensive | Code generation |
| Supervised Learning | PtrNet, GNN, Transformer | Fast inference, good convergence | Requires labeled data | TSP, VRP, JSSP |
| Reinforcement Learning | DQN, PPO, SAC | No labels needed, adaptive | Sample inefficient | Dynamic scheduling |
| Unsupervised Learning | GAN, VAE, Diffusion | Diverse solutions, no labels | Training instability | Routing, layout |
| LLM-based | GPT, Llama, Gemini | Natural language interface | Computationally expensive | Code generation |



## LLM4COP
# LLM for Combinatorial Optimization Problem - Literature Comparison Table

| # | Reference | Category | Problem | Key Features | Performance/Results | Code |
|---|-----------------------------------------------------|----------|---------|--------------|---------------------|------|
| 1 | [Yang et al. 2024]() | LLM as Optimizer | General Optimization | OPRO framework: Treats LLM as a general-purpose optimizer, uses natural language problem descriptions, zero-shot solution generation | Performance comparable to specialized solvers | [Available](https://github.com/google-deepmind/opro) |
| 2 | [Huang et al. 2025]() | LLM as Optimizer | High-dimensional Problems | Multimodal perception mechanism: Fuses XML-structured text with node-distribution images to enhance spatial topology understanding | Enhances modeling of dependencies among decision variables | |
| 3 | [Elhenawy et al. 2024]() | LLM as Optimizer | m-TSP | Multi-agent collaborative framework: Specialized agents for fine-grained optimization | Zero-shot performance comparable to self-supervised learning methods | [Available](https://github.com/ahmed-abdulhuy/) |
| 4 | [Abgaryan et al. 2024]() | LLM as Optimizer | JSSP | Constructs large-scale natural language JSSP dataset (120k samples), LoRA-based lightweight fine-tuning | Worktime optimization performance comparable to GNNs | |
| 5 | [Romera-Paredes et al. 2024]() | LLM as Programmer | Online Bin Packing | FunSearch framework: Evaluator-generator cooperative paradigm, evolves algorithms in function space | Surpasses handcrafted heuristic algorithms | |
| 6 | [Liu et al. 2024]() | LLM as Programmer | Online Bin Packing | EoH: Dual-track evolutionary mechanism simultaneously optimizes natural language descriptions and executable code | Superior solution quality and speed compared to FunSearch | [Available](https://github.com/FeiLiu36/EoH) |
| 7 | [Shi et al. 2025]() | LLM as Programmer | TSP, Bin Packing | Self-evolving meta-optimizer: Autonomously constructs low-order mutation strategies, overcomes predefined operator limitations | Enhances cross-scale generalization | |
| 8 | [Ye et al. 2024]() | LLM as Programmer | General Optimization | ReEvo: Integrates evolutionary search with LLM self-reflection, generates language feedback convertible to semantic gradients | Surpasses traditional hyper-heuristic algorithms | [Available](https://ai4co.github.io/reevo) |
| 9 | [Zheng et al. 2025]() | LLM as Programmer | VRP | MCTS-AHD: Uses Monte Carlo Tree Search to manage heuristic evolution trees, retains promising candidates | Notable success on VRP problems | [Available](https://github.com/zz1358m/MCTS-AHD-master/tree/main) |
| 10 | [Dat et al. 2025]() | LLM as Programmer | General Optimization | HSEvo: Integrates harmonic search to maintain population diversity balance | Improves exploration efficiency | [Available](https://github.com/datphamvn/HSEvo) |
| 11 | [Huang et al. 2024]() | LLM as Programmer | Dynamic Task Scheduling | SeEvo framework: Self-evolutionary adaptation | Surpasses genetic programming methods | |
| 12 | [Jiang et al. 2025]() | LLM as Programmer | Complex VRP Instances | DRoC: Constraint-decomposition retrieval mechanism for complex VRP instances | Improves handling of complex constraints | [Available](https://github.com/Summer142857/DRoC) |
| 13 | [Chen et al. 2024]() | LLM as Programmer | General Optimization | Quality-uncertainty balance criterion enhances FunSearch exploration efficiency | Improves exploration efficiency | [Available](https://github.com/zzjchen/QUBE) |
| 14 | [Van et al. 2025]() | LLM as Programmer | General Optimization | Analyzes code evolution trajectories, reveals trade-off between code complexity and performance | Provides interpretability tools for LLM-based algorithm design | |
| 15 | [Surina et al. 2025]() | LLM as Collaborator | General Optimization | EvoTune: Integrates RL into LLM-based evolutionary search loop, forms closed feedback mechanism | Surpasses FunSearch baseline, significantly reduces optimality gap | [Available](https://claire-labo.github.io/EvoTune/) |
| 16 | [Dao et al. 2025]() | LLM as Collaborator | TSP, CVRP | Integrates LLM into evolutionary framework, transforms best strategies into attention bias signals for neural solvers | State-of-the-art performance on large-scale instances | |
| 17 | [Ramamonjison et al. 2022]() | Modeling | LP Problems | NL4Opt competition dataset and system framework: First document-level natural language LP dataset (713 problems) | Establishes benchmark for natural-language-to-optimization-model conversion | |
| 18 | [Li et al. 2023]() | Modeling | MILP Problems | Three-phase MILP synthesis framework: Constraint classification hierarchy and template library | Significantly outperforms ChatGPT in understanding and constraint generation | |
| 19 | [Obata et al. 2024]() | Modeling | Multi-robot Task Planning | LiP-LLM framework: Integrates LLM semantic parsing with traditional optimization solvers | Minimizes total execution time | |
| 20 | [Ahmed et al. 2024]() | Modeling | General Optimization | LM4OPT progressive fine-tuning framework: Noise-injected embeddings, domain-adaptive datasets | Significant accuracy improvement for Zephyr-7B on NL4Opt | |
| 21 | [Jang et al. 2022]() | Modeling | LP Problems | Entity-type-based label embedding technique enhances intermediate representation quality | Runner-up in NL4Opt subtask competitions | |
| 22 | [He et al. 2022]() | Modeling | LP Problems | Combines conditional random fields with multi-prompt T5 generators, data augmentation | Improves model generalization | |
| 23 | [Ning et al. 2023]() | Modeling | Cross-domain Optimization | Adversarial training and prompt engineering improve cross-domain adaptability | Enhances cross-domain generalization | |
| 24 | [Dhanaraj et al. 2024]() | Modeling | Human-LLM Collaboration | Translates natural language preferences into soft constraints | Advances human-LLM collaborative optimization scenarios | |
| 25 | [Chen et al. 2024]() | Explaining | Feasibility Diagnosis | OptiChat: Combines optimization solvers with expert-style chain-of-thought prompting | Significantly reduces dependence on domain experts | |
| 26 | [Xiao et al. 2023]() | Explaining | General Optimization | Chain-of-Experts (CoE) framework: Three specialized agents under coordinator control | Lower error rates, higher optimization success than single-agent approaches | |
| 27 | [Mostajabdaveh et al. 2024]() | Explaining | Optimization Verification | Multi-stage verification framework: Relation-identification agent checks variable-constraint consistency | Doubles verification efficiency without solver invocation | |
| 28 | [Huang et al. 2024]() | Explaining | VRP | Self-debugging and self-verification framework | Significantly improves feasibility, optimality, and efficiency of GPT-4 solutions | [Available](https://sites.google.com/view/words-to-routes/) |
| 29 | [Hao et al. 2024]() | Explaining | Planning Problems | LLMFP framework: Transforms planning problems into constraint optimization models | Zero-shot generation of structured representations and executable code | |
| 30 | [Li et al. 2024]() | Explaining | Combinatorial Optimization | Explores interactive dialogue for iterative problem specification refinement | Future research directions | |
| 31 | [Ahmaditeshnizi et al. 2024]() | Expert Systems | LP, IP, Routing Problems | OptiMUS: Modular multi-agent architecture, divide-and-conquer strategy, chain-of-thought prompting | Establishes foundation for LLM-based combinatorial optimization expert systems | |
| 32 | [Jiang et al. 2024]() | Expert Systems | Linear & Nonlinear Programming | LLMOPT: Five-element unified representation, multi-instruction fine-tuning, self-correction mechanism | Significant average accuracy gains across 20 domains | |
| 33 | [Peng et al. 2025]() | Expert Systems | MILP | Localized knowledge-enhanced framework: Integrates domain knowledge base | Meets industrial privacy requirements, avoids cloud data transfer | |
| 34 | [Ju et al. 2024]() | Expert Systems | MILP | Symbolic translation-solver co-framework: LLM fine-tuned to translate requests into symbolic constraints | Reduces response latency | |
| 35 | [Yang et al. 2024]() | Expert Systems | General Optimization | ReSocratic synthetic method: Generates 29,000 optimization problem instances in reverse | Enables open-source models to approach GPT-4 level performance | |
| 36 | [Huang et al. 2024]() | Expert Systems | TSP, Robotic Routing/Planning | Systematic study of robotic models, self-debugging frameworks | Self-debugging increases TSP solving success rate by 18% | |
| 37 | [Sun et al. 2025]() | Expert Systems | 36 Real-world COPs | CO-Bench benchmark: Covers 36 real-world combinatorial optimization problems | Reveals LLM-based agents lag ~23% behind traditional algorithms | [Available](https://github.com/sunnweiwei/CO-Bench) |
| 38 | [Zhang et al. 2024]() | Expert Systems | General Optimization | OptLLM framework: Natural language → mathematical formula → solver code | End-to-end optimization problem solving | [Available](https://opt.alibabacloud.com/chat) |
| 39 | [Yao et al. 2025]() | LLM as Programmer | General Optimization | MEoH framework: Multi-objective evolution + dominance-diversity mechanism | Improves exploration of heuristic algorithm space | [Available](https://github.com/Optima-CityU/LLM4AD) |
| 40 | [Iklassov et al. 2024]() | LLM as Programmer | General Optimization | Self-guided exploration (SGE): Four-stage autonomous problem solving | Autonomous problem-solving capability | [Available](https://github.com/Zangir/LLM-for-CP) |

## 📝 Citation
If you use these resources, please cite:
```bibtex
@article{yourpaper2025,
  title={Machine Learning-Driven Combinatorial Optimization: A Systematic Review},
  author={Co-authors},
  journal={Journal},
  year={2025}
}
