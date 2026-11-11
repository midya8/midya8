## Hi, I'm Midya

I'm a Toronto-based technologist with 12+ years across technology, financial services and telecommunications. Lately I spend most of my build time on large language models, agentic systems and workflow automation.

Most repos here follow the same habit: implement the thing from scratch, hand-derive the math, then verify it independently (Python against browser BigInt/Fraction replays) instead of trusting that the optimizer or the library did the right thing. The "lab" repos are that habit applied across ML, game theory, causal inference and planning. A few are plain tools I actually use.

[Browse the searchable project index](https://midya8.github.io/Midya-portfolio/) | [Catalog and build contract](https://github.com/midya8/Midya-portfolio/blob/main/CATALOG.md)

### Models and training, from scratch

| Project | What it is |
| --- | --- |
| [ScratchGPT](https://github.com/midya8/scratchgpt) | GPT and a reverse-mode autograd engine written from scratch in NumPy, trained on TinyShakespeare |
| [PPOlab](https://github.com/midya8/ppolab) | PPO from scratch in NumPy: clipped surrogate, GAE, hand-derived and numerically verified gradients |
| [TagLab](https://github.com/midya8/taglab) | Linear-chain CRF implemented and trained by hand, every optimization state replayed |
| [ForestLab](https://github.com/midya8/forestlab) | Random forests from scratch with exact Gini split ordering and an OOB inspector |
| [BoostLab](https://github.com/midya8/boostlab) | Gradient boosting from scratch, optional Newton leaves on residual-SSE trees |
| [MarginLab](https://github.com/midya8/marginlab) | Linear and RBF soft-margin SVM with replayable pair updates |
| [SpectralLab](https://github.com/midya8/spectrallab) | Spectral clustering with hand-written affinity, Laplacian and k-means stages |
| [ClusterLab](https://github.com/midya8/clusterlab) | k-means++/Lloyd on real UCI digits with full restart traces |
| [MixtureLab](https://github.com/midya8/mixturelab) | Gaussian mixture EM on UCI chemistry data with full likelihood accounting |
| [PartsLab](https://github.com/midya8/partslab) | Nonnegative matrix factorization on UCI digits with browser-side decompositions |
| [RatingLab](https://github.com/midya8/ratinglab) | Rating factorization for collaborative filtering via alternating ridge solves |
| [DenoiseLab](https://github.com/midya8/denoiselab) | Denoising/retrieval maps with exact rational minimum cells |
| [DiffuseLab](https://github.com/midya8/diffuselab) | Small 2-D diffusion model from scratch, with DDIM step-count audits |
| [FlowLab](https://github.com/midya8/flowlab) | Affine-coupling normalizing flow from scratch, with density and inverse checks |
| [LatentLab](https://github.com/midya8/latentlab) | Gaussian VAE from scratch, all 150 pathwise gradients independently checked |
| [HamiltonLab](https://github.com/midya8/hamiltonlab) | Hamiltonian Monte Carlo from scratch with full rejection histories |
| [ParticleLab](https://github.com/midya8/particlelab) | Bootstrap particle filtering with complete log-weight and ancestry records |
| [ChainLab](https://github.com/midya8/chainlab) | Hidden Markov models: log-space inference, Viterbi and Baum-Welch |
| [KernelLab](https://github.com/midya8/kernellab) | Gaussian-process regression and expected-improvement search from scratch |
| [DistillLab](https://github.com/midya8/distilllab) | Knowledge distillation from scratch, compared against matched controls |
| [MoeLab](https://github.com/midya8/moelab) | Mixture-of-experts capacity dispatch with an exact rational allocator |
| [LoRALab](https://github.com/midya8/loralab) | LoRA rank auditing: exact minors versus what actually predicts |
| [AlignLab](https://github.com/midya8/alignlab) | Policy alignment inspector separating KL budget from optimizer error |
| [SpecLab](https://github.com/midya8/speclab) | Speculative decoding with stopping-law audits |
| [DecodeLab](https://github.com/midya8/decodelab) | Staged sampling and beam pruning, audited against exhaustive oracles |
| [AttnLens](https://github.com/midya8/attnlens) | Hand-differentiated attention trainer with a head-ablation workbench |
| [KVLens](https://github.com/midya8/kvlens) | KV-cache inspector for attention with and without caching |
| [TokenForge](https://github.com/midya8/tokenforge) | BPE tokenizer training with occurrence-indexed merges |

### Evaluation, reliability and safety tooling

| Project | What it is |
| --- | --- |
| [EvalForge](https://github.com/midya8/evalforge) | Clustered sign-flip audits for model comparisons |
| [PolicyLens](https://github.com/midya8/policylens) | Offline contextual-bandit evaluation: IPS, SNIPS and doubly robust |
| [DriftLens](https://github.com/midya8/driftlens) | Embedding drift detection via MMD with permutation tests |
| [SetGuard](https://github.com/midya8/setguard) | Split-conformal prediction sets with JSON fit/predict artifacts |
| [CalibrLab](https://github.com/midya8/calibrlab) | Confidence calibration with unclipped NLL and bootstrap intervals |
| [ShapleyLab](https://github.com/midya8/shapleylab) | Exact Shapley values for small feature sets, background sensitivity included |
| [GroundCheck](https://github.com/midya8/groundcheck) | Citation, number and lexical provenance checks for generated text |
| [PromptGuard](https://github.com/midya8/promptguard) | Prompt-injection scanner with explicit suppression quotas |
| [RAGLine](https://github.com/midya8/ragline) | Signed-vector postings retrieval with full ranking-stability checks |
| [RetrievalBench](https://github.com/midya8/retrievalbench) | BM25 plus weighted rank fusion, every vote traceable |
| [PlanBench](https://github.com/midya8/planbench) | Retry, completion-time and cost risk laws for agent plan DAGs |
| [AgentTrace](https://github.com/midya8/agenttrace) | Trace retention under overlap caps, solved with min-cost flow |
| [StructGate](https://github.com/midya8/structgate) | DFA conditioning of language-model outputs |

### Exact math and decision analysis

| Project | What it is |
| --- | --- |
| [QuantLab](https://github.com/midya8/quantlab) | Integer dot-product quantization with exact error decomposition |
| [VectorLite](https://github.com/midya8/vectorlite) | Block-bucket retrieval backend for binary signatures, exact Hamming verification |
| [EmbedKit](https://github.com/midya8/embedkit) | Audits the negative-sampling retry logic behind its embedding trainer |
| [GraphLab](https://github.com/midya8/graphlab) | Edge-deletion census over graph networks with per-target logit traces |
| [GameLab](https://github.com/midya8/gamelab) | Zero-sum game audits: optimal faces and minimax witnesses |
| [Correlab](https://github.com/midya8/correlab) | General-sum correlated equilibria with exact certificates |
| [SubgameLab](https://github.com/midya8/subgamelab) | Sequential games: Nash versus subgame-perfect, made concrete |
| [AuctionLab](https://github.com/midya8/auctionlab) | VCG prices, bundle menus and coalition deficits, inspectable |
| [MatchLab](https://github.com/midya8/matchlab) | Two-sided matching with the full stable family, not one matching |
| [OrderLab](https://github.com/midya8/orderlab) | Weighted Kemeny rank aggregation with all tied optima |
| [BetLab](https://github.com/midya8/betlab) | Sequential betting tests on paired model scores |
| [CredalLab](https://github.com/midya8/credallab) | Decisions under imprecise probabilities with primal/dual replays |
| [ChannelLab](https://github.com/midya8/channellab) | Binary channel comparison via constructive garblings |
| [RiskLab](https://github.com/midya8/risklab) | Scenario-tree decisions under static and nested CVaR |
| [PrivacyLab](https://github.com/midya8/privacylab) | Differential privacy audits with exact hockey-stick curves |
| [CausalLab](https://github.com/midya8/causallab) | Structural causal models: observation, intervention, counterfactual |
| [SegmentLab](https://github.com/midya8/segmentlab) | Changepoint inference with exact Gaussian partition marginals |
| [CutLab](https://github.com/midya8/cutlab) | Exact rational graph cuts for binary submodular energies |
| [FactorLab](https://github.com/midya8/factorlab) | Variable elimination with every join and fill edge visible |
| [SubmodLab](https://github.com/midya8/submodlab) | Submodular selection with greedy traces and proof-derived bounds |
| [DPPLab](https://github.com/midya8/dpplab) | Determinantal point processes with exact rational subset laws |
| [CTCLab](https://github.com/midya8/ctclab) | CTC loss from scratch: log-space forward/backward and gradients |
| [ScanLab](https://github.com/midya8/scanlab) | State-space scans with failure controls and JVP/VJP audits |
| [SparseLab](https://github.com/midya8/sparselab) | LASSO audits: KKT, duality and Gap Safe zero certificates |
| [InfluenceLab](https://github.com/midya8/influencelab) | Influence functions for logistic models, with deletion paths |
| [FisherLab](https://github.com/midya8/fisherlab) | Natural policy-gradient geometry with exact Fisher solves |
| [ScoreLab](https://github.com/midya8/scorelab) | Policy-gradient score functions with exact covariance checks |
| [BanditLab](https://github.com/midya8/banditlab) | Beta-Bernoulli bandit planning with exact posterior graphs |
| [BeliefLab](https://github.com/midya8/belieflab) | Finite-horizon POMDP planning with policy trees |
| [BellmanLab](https://github.com/midya8/bellmanlab) | Discounted and robust dynamic programming with residual certificates |
| [ErgodLab](https://github.com/midya8/ergodlab) | Stationary-distribution sensitivity for Markov decision processes |
| [VariLab](https://github.com/midya8/varilab) | Mean-field variational inference from scratch |
| [RobustLab](https://github.com/midya8/robustlab) | Exact norm-ball margins for linear adversarial robustness |
| [TransportLab](https://github.com/midya8/transportlab) | Entropic optimal transport in log domain, convergence audited |
| [RectLab](https://github.com/midya8/rectlab) | Every optimal factor set in rectangle covers, indexed exactly |
| [CompileLab](https://github.com/midya8/compilelab) | Boolean knowledge compilation into inspectable decision graphs |
| [FireLab](https://github.com/midya8/firelab) | Petri-net inspector separating token balance from executability |
| [ParetoLab](https://github.com/midya8/paretolab) | Biobjective planning that keeps all Pareto tradeoffs |
| [TreeLab](https://github.com/midya8/treelab) | Budgeted counterfactual search over tree ensembles |
| [DigitLab](https://github.com/midya8/digitlab) | Live inspector for UCI digit models with Integrated Gradients |

### Ops tooling

| Project | What it is |
| --- | --- |
| [sre-toolkit](https://github.com/midya8/sre-toolkit) | Error budgets, burn-rate alerting, alert triage and noise ranking |
| [loglens](https://github.com/midya8/loglens) | Access-log triage for the first five minutes of an incident |
| [flowkit](https://github.com/midya8/flowkit) | JSON-defined DAG workflow runner with retries and timeouts |
| [uptimekit](https://github.com/midya8/uptimekit) | Synthetic HTTP/TCP/TLS uptime monitoring and availability reports |
