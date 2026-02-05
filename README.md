# ml-cop-survey-resources
A curated collection of references and comparative tables for the survey on Machine Learning for Combinatorial Optimization Problems


# Machine Learning for Combinatorial Optimization: Survey Resources

## 📚 Overview
This repository contains curated resources supporting the survey paper:
**"Machine Learning-Driven Combinatorial Optimization: A Systematic Review"** (currently under review).


## 📊 Review Article
# A Comparative Review of Machine Learning Approaches for Solving COPs

| Literature | SL | UL | Q-Learning | DRL | LLM | RP | SP | Other probs. |
|------------|----|----|------------|-----|-----|----|----|--------------|
| [Talbi et al. 2021](https://doi.org/10.1145/3459664) | ✓ | ✓ | ✓ | ✓ | ✗ | ✓ | ✓ | ✓ |
| [Li et al. 2021](https://aas.net.cn/cn/article/pdf/preview/10.16383/j.aas.c200551.pdf) | ✗ | ✗ | ✗ | ✓ | ✗ | ✓ | ✓ | ✓ |
| [Karimi-Mamaghan et al. 2022](https://doi.org/10.1016/j.ejor.2021.04.032) | ✓ | ✓ | ✓ | ✗ | ✗ | ✓ | ✓ | ✓ |
| [Li et al. 2022](https://xplorestaging.ieee.org/document/9812526) | ✓ | ✗ | ✗ | ✓ | ✗ | ✓ | ✗ | ✗ |
| [Mazyavkina et al. 2022](https://doi.org/10.1016/j.cor.2021.105400) | ✗ | ✗ | ✗ | ✓ | ✗ | ✓ | ✓ | ✓ |
| [Qin et al. 2022](https://doi.org/10.1016/j.trc.2022.103852) | ✗ | ✗ | ✓ | ✓ | ✗ | ✓ | ✗ | ✓ |
| [Da Costa Oliveira et al. 2023](https://link.springer.com/content/pdf/10.1007/s00500-023-08886-3.pdf?utm_source=clarivate&getft_integrator=clarivate) | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ | ✓ | ✓ |
| [Zhang et al. 2023](https://doi.org/10.1016/j.neucom.2022.11.024) | ✓ | ✓ | ✓ | ✓ | ✗ | ✓ | ✓ | ✓ |
| [Zhang et al. 2023](https://doi.org/10.1049/cim2.12072) | ✓ | ✓ | ✓ | ✓ | ✗ | ✗ | ✓ | ✓ |
| [Szénási et al. 2024](https://doi.org/10.1016/j.eswa.2024.125192) | ✓ | ✓ | ✗ | ✗ | ✗ | ✓ | ✓ | ✓ |
| [Zhang et al. 2024](https://doi.org/10.1016/j.jmsy.2024.10.026) | ✗ | ✗ | ✗ | ✓ | ✗ | ✗ | ✓ | ✗ |
| [Yang et al. 2024](https://doi.org/10.1002/widm.1548) | ✗ | ✗ | ✓ | ✗ | ✗ | ✓ | ✓ | ✓ |
| [Modrak et al. 2024]() | ✗ | ✗ | ✓ | ✓ | ✗ | ✗ | ✓ | ✗ |
| [Jalali Khalil Abadi et al. 2024]() | ✗ | ✗ | ✗ | ✓ | ✗ | ✗ | ✓ | ✗ |
| [Erdem et al. 2024]() | ✓ | ✗ | ✓ | ✓ | ✗ | ✓ | ✗ | ✗ |
| [Fu et al. 2024]() | ✗ | ✗ | ✓ | ✓ | ✗ | ✗ | ✓ | ✗ |
| [Smit et al. 2025]() | ✗ | ✓ | ✗ | ✓ | ✗ | ✗ | ✓ | ✗ |
| [Lv et al. 2025]() | ✗ | ✗ | ✗ | ✓ | ✗ | ✗ | ✓ | ✗ |
| [Martins et al. 2025]() | ✗ | ✗ | ✓ | ✓ | ✗ | ✓ | ✓ | ✓ |
| [Chung et al. 2025]() | ✗ | ✗ | ✗ | ✓ | ✗ | ✓ | ✓ | ✓ |
| [Arishi et al. 2025]() | ✗ | ✗ | ✓ | ✓ | ✗ | ✓ | ✗ | ✗ |
| [Sui et al. 2025]() | ✓ | ✗ | ✗ | ✓ | ✓ | ✓ | ✗ | ✗ |
| [Wu et al. 2025]() | ✗ | ✗ | ✗ | ✗ | ✓ | ✓ | ✓ | ✓ |
| [Zhang et al. 2025]() | ✓ | ✓ | ✓ | ✓ | ✗ | ✓ | ✓ | ✓ |
| [Da Ros et al. 2025]() | ✗ | ✗ | ✗ | ✗ | ✓ | ✓ | ✓ | ✓ |
| [Tao et al. 2025]() | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| [Ours]() | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |

## UL4COP

# Unsupervised Learning for Combinatorial Optimization Problem - Literature Comparison Table

| # | Reference | Category | Problem | Method | Results | Code |
|---|-----------|----------|---------|--------|---------|------|
| 1 | [Sun et al. 2023]() | Diffusion Models | TSP, MIS | DIFUSCO: Graph denoising diffusion models, discrete {0,1}-vector optimization, dual Gaussian/Bernoulli noise diffusion, graph-based diffusion | State-of-the-art performance on TSP | |
| 2 | [Huang et al. 2023]() | Diffusion Models | TSP | Progressive distillation technique to compress iterative steps, predicts multi-step noise residuals for single-step updates | Significantly reduces inference latency while maintaining solution quality | |
| 3 | [Xue et al. 2024]() | Diffusion Models | 2D Irregular Bin Packing | Attention-based gradient-field learning, geometric encoding for polygon rotations, boundary-condition constraints | Surpasses RL baselines in material utilization, 10x faster inference | |
| 4 | [Sanokowski et al. 2024]() | Diffusion Models | General COPs | DiffUCO: Label-free diffusion model, Joint Variational Upper Bound for unsupervised training, discrete diffusion with temperature annealing | Enables direct sampling of high-quality solutions without labeled data | |
| 5 | [Hong et al. 2024]() | Diffusion Models | General COPs | IC/DC framework: Eliminates dependence on pretrained data, self-supervised losses, constraint-satisfaction mechanisms | Removes need for post-hoc search | |
| 6 | [Wang et al. 2025]() | Diffusion Models | TSP | DEITSP: Dual-modal graph Transformer for feature fusion, iterative strategy for enhanced exploration | Accelerated feature fusion, improved exploration capability | |
| 7 | [Wang et al. 2023]() | GANs | General COPs | GIRL framework: Integration of inverse RL with GANs, self-attention-based policy network generates 2-opt heuristic rules | Addresses sparse-reward issue, mitigates training instability | |
| 8 | [Zhang et al. 2025]() | GANs | Routing Problems | Adversarial Generative Flow Network: Replaces Transformer with generative flow network, discriminator contrasts original and optimized solutions | Breaks scalability bottleneck, produces diverse routing solutions | |
| 9 | [Guo et al. 2020]() | GANs | Multi-objective Optimization | Multi-objective combinatorial GAN: Uses non-dominated solutions as real data, adaptive parameter tuning, decimal-encoding decoding | 35% speedup over NSGA-II on group-aware participant selection | |
| 10 | [Chen et al. 2019]() | GANs | General COPs | DCG-EA/I: Negative-sample exploitation mechanism, reconstructs low-quality solutions into pseudo-positive samples, integrates 2-opt local search | Addresses mode collapse issue, enhances solution feasibility | |
| 11 | [Yu et al. 2022]() | GANs | Discrete Optimization | PGAN-CEA: Combines policy gradients with Monte Carlo simulation | Improves GANs' ability to generate high-quality discrete solutions | |
| 12 | [Zhang et al. 2024]() | GANs | 3D Bin Packing | Hybrid GAN-GA model: Generates spatial item layouts | Improves packing utilization by 4.7% | |
| 13 | [Bentley et al. 2023]() | VAEs | Robotic Scheduling | COIL: Integration of VAEs with optimizers, encodes historical schedules into latent space, GA optimization in latent space | Satisfies robot parallelism constraints through latent space encoding | |
| 14 | [Onsu et al. 2025]() | VAEs | Service Function Chain Deployment | Generative VAE-assisted DRL for 5G networks, compresses network states into latent representations, end-to-end latency penalty term | Optimizes SFC deployment with sub-10 ms delay requirement | |
| 15 | [Chen et al. 2023]() | VAEs | Active Distribution Networks | VAE-enhanced TD3 algorithm, encodes multi-site energy-storage states into latent variables capturing spatio-temporal coupling | Minimizes overall system operating costs | |
| 16 | [Bhattacharjee et al. 2019]() | VAEs | Complex Benchmark Problems (Trap-k) | VAE-EDA-Q: Embeds VAE into estimation-of-distribution algorithm, adaptive variance scaling for sampling diversity | 5x speedup in convergence over BOA algorithm on Trap-13 | |
| 17 | [Wang et al. 2024]() | VAEs | Task Offloading and Resource Allocation | CARMARL: Conditional VAE for hybrid discrete-continuous decisions, reward-constrained policy optimization | 25.2% increase in completion rate of intelligent connected vehicle tasks | |
| 18 | [Yao et al. 2019]() | VAEs | Content Pre-caching | CVAE for user mobility trajectory prediction, optimizes small-cell content pre-caching strategies | Reduces handover latency | |
| 19 | [Nouri et al. 2024]() | VAEs | O-RAN Slicing | Semi-supervised resource allocator: Combines VAEs with contrastive learning | 14% improvement in physical resource block allocation accuracy | |
| 20 | [Li et al. 2024]() | VAEs | Industrial Sensor Resource Allocation | DT-VAE evaluation mechanism based on digital twins, virtual-physical consistency analysis | Improves cooperative sensing accuracy | |
| 21 | [Shanmugham et al. 2024]() | VAEs | MANETs Routing | Self-attention-based CVAE-GAN routing paradigm, strengthens node state representations | 22% reduction in energy consumption for multipath routing | |
| 22 | [Yao et al. 2019]() | Discriminative Models | MAX-CUT | Investigation of unsupervised GNNs on random MAX-CUT, approximates SDP benchmark without label supervision | Demonstrates GNNs can approximate SDP benchmark | |
| 23 | [Karalias et al. 2020]() | Discriminative Models | Cliques, Vertex Covers, Independent Sets | Mathematically grounded unsupervised framework, parameterizes distribution over sets, derandomization strategy | Provides theoretical guarantees for solution quality and feasibility | |
| 24 | [Schuetz et al. 2022]() | Discriminative Models | QUBO Problems | Physics-inspired GNN: Hamiltonian minimization, reformulates COPs as QUBO tasks, continuous relaxation for binary variables | Lays theoretical foundation for directly solving COPs with GNNs | |
| 25 | [Toenshoff et al. 2021]() | Discriminative Models | Binary Max Constraint Satisfaction | Unsupervised recurrent GNN, constraint graph as substrate, single-LSTM unit with linear layers | Directly maximizes number of satisfied constraints | |
| 26 | [Boisvert et al. 2024]() | Discriminative Models | SAT, Graph Coloring, TSP, Knapsack | AST-based encoding framework, generic injective graph representation function, unifies expression of diverse problems | Facilitates structural knowledge sharing across tasks | |
| 27 | [Bai et al. 2025]() | Discriminative Models | Graph and Hypergraph Partitioning | Deep-Grouping framework: Unifies graph and hypergraph partitioning, Gini-index-based continuous relaxation annealing | Balances differentiable optimization and discrete convergence | |
| 28 | [Liao et al. 2025]() | Discriminative Models | Dynamic Combinatorial Optimization | DyCO-GNN: Temporally continuous structural embedding, GNN parameters shared across temporal snapshots | Enables fast updates on continuous-time graphs without offline training data | |
| 29 | [Min et al. 2025]() | Discriminative Models | Quadratic Assignment Problem | Permutation-invariant method, introduces permutation-symmetric constraints into objective | Enhances model generalization and scalability | |

## LLM4COP
# LLM for Combinatorial Optimization Problem - Literature Comparison Table

| # | Reference | Category | Problem | Method | Results | Code |
|---|-----------|----------|---------|--------|---------|------|
| 1 | [Yang et al. 2024]() | LLM as Optimizer | General Optimization | OPRO framework: Treats LLM as general-purpose optimizer, uses natural language problem descriptions, zero-shot solution generation | Performance comparable to specialized solvers | [Available](https://github.com/google-deepmind/opro) |
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
