## Hi, I'm Midya

I'm a Toronto-based technologist with 12+ years across technology, financial services and telecommunications. Lately I spend most of my build time on large language models, agentic systems and workflow automation.

Most repos here follow the same habit: implement the thing from scratch, hand-derive the math, then verify it independently (Python against browser BigInt/Fraction replays) instead of trusting that the optimizer or the library did the right thing. The "lab" repos are that habit applied across ML, game theory, causal inference and planning. A few are plain tools I actually use.

[Browse the searchable project index](https://midya8.github.io/Midya-portfolio/) | [Catalog and build contract](https://github.com/midya8/Midya-portfolio/blob/main/CATALOG.md)

### Models and training, from scratch

| Project | What it is |
| --- | --- |
| [ScratchGPT](https://github.com/midya8/scratchgpt) | NumPy GPT with exact continuation, block recomputation and [cached inference](https://midya8.github.io/scratchgpt/cache.html) that rebuilds when the learned-position context moves |
| [PPOlab](https://github.com/midya8/ppo-numpy) | PPO from scratch in NumPy: clipped surrogate, GAE, hand-derived and numerically verified gradients |
| [TagLab](https://github.com/midya8/linear-chain-crf) | Linear-chain CRF implemented and trained by hand, every optimization state replayed |
| [ForestLab](https://github.com/midya8/random-forests) | Random forests from scratch with exact Gini split ordering and an OOB inspector |
| [BoostLab](https://github.com/midya8/logit-boosting) | Gradient boosting from scratch, optional Newton leaves on residual-SSE trees |
| [MarginLab](https://github.com/midya8/svm-from-scratch) | Linear and RBF soft-margin SVM with replayable pair updates |
| [SpectralLab](https://github.com/midya8/spectral-clustering) | Spectral clustering with hand-written affinity, Laplacian and k-means stages |
| [ClusterLab](https://github.com/midya8/kmeans-clustering) | k-means++/Lloyd on real UCI digits with full restart traces |
| [MixtureLab](https://github.com/midya8/gmm-em) | Gaussian mixture EM on UCI chemistry data with full likelihood accounting |
| [PartsLab](https://github.com/midya8/nonnegative-matrix) | Nonnegative matrix factorization on UCI digits with browser-side decompositions |
| [RatingLab](https://github.com/midya8/rating-factors) | Rating factorization for collaborative filtering via alternating ridge solves |
| [DenoiseLab](https://github.com/midya8/digit-denoising) | Denoising/retrieval maps with exact rational minimum cells |
| [DiffuseLab](https://github.com/midya8/diffusion-in-2d) | Small 2-D diffusion model from scratch, with DDIM step-count audits |
| [FlowLab](https://github.com/midya8/density-flows) | Affine-coupling normalizing flow from scratch, with density and inverse checks |
| [LatentLab](https://github.com/midya8/variational-autoencoder) | Gaussian VAE from scratch, all 150 pathwise gradients independently checked |
| [HamiltonLab](https://github.com/midya8/hamiltonian-monte-carlo) | Hamiltonian Monte Carlo from scratch with full rejection histories |
| [ParticleLab](https://github.com/midya8/particle-filtering) | Bootstrap particle filtering with complete log-weight and ancestry records |
| [ChainLab](https://github.com/midya8/hidden-markov) | [Path decisions and uncertainty](https://midya8.github.io/hidden-markov/paths.html): exact HMM decoding losses, supported paths and whole-path entropy; original trainer and prefix inspector retained |
| [KernelLab](https://github.com/midya8/gaussian-processes) | Gaussian-process regression and expected-improvement search from scratch |
| [DistillLab](https://github.com/midya8/knowledge-distillation) | Knowledge distillation from scratch, compared against matched controls |
| [MoeLab](https://github.com/midya8/mixture-of-experts) | Exact one-table gate regret, capacity dispatch and independent vertex checks |
| [LoRALab](https://github.com/midya8/lora-finetuning) | LoRA rank auditing: exact minors versus what actually predicts |
| [AlignLab](https://github.com/midya8/preference-optimization) | [Preference identification](https://midya8.github.io/preference-optimization/identification.html): the same observed comparisons can fit different Gibbs policies; exact cycle checks and explicit scale bounds, alongside the original optimizer inspector |
| [SpecLab](https://github.com/midya8/speculative-decoding) | Speculative decoding with stopping-law audits |
| [DecodeLab](https://github.com/midya8/lm-decoding) | Staged sampling and beam pruning, audited against exhaustive oracles |
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
| [CalibrLab](https://github.com/midya8/confidence-calibration) | Confidence calibration with unclipped NLL and bootstrap intervals |
| [ShapleyLab](https://github.com/midya8/shapley-values) | Exact Shapley values for small feature sets, background sensitivity included |
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
| [QuantLab](https://github.com/midya8/int8-quantization) | Integer dot-product quantization with exact error decomposition |
| [VectorLite](https://github.com/midya8/vectorlite) | Block-bucket retrieval backend for binary signatures, exact Hamming verification |
| [EmbedKit](https://github.com/midya8/embedkit) | Audits the negative-sampling retry logic behind its embedding trainer |
| [GraphLab](https://github.com/midya8/graph-convnets) | Edge-deletion census over graph networks with per-target logit traces |
| [GameLab](https://github.com/midya8/minimax) | Zero-sum game audits: optimal faces and minimax witnesses |
| [Correlab](https://github.com/midya8/joint-play) | General-sum correlated equilibria with exact certificates |
| [SubgameLab](https://github.com/midya8/subgame-perfection) | Sequential games: Nash versus subgame-perfect, made concrete |
| [AuctionLab](https://github.com/midya8/vcg-auctions) | VCG prices, bundle menus and coalition deficits, inspectable |
| [MatchLab](https://github.com/midya8/stable-matching) | Two-sided matching with the full stable family, not one matching |
| [OrderLab](https://github.com/midya8/kemeny-ranking) | Weighted Kemeny rank aggregation with all tied optima |
| [BetLab](https://github.com/midya8/sequential-betting) | Sequential betting tests on paired model scores |
| [CredalLab](https://github.com/midya8/credal-reasoning) | Decisions under imprecise probabilities with primal/dual replays |
| [ChannelLab](https://github.com/midya8/channel-comparison) | Binary channel comparison via constructive garblings |
| [RiskLab](https://github.com/midya8/scenario-risk) | Scenario-tree decisions under static and nested CVaR |
| [PrivacyLab](https://github.com/midya8/privacy-channels) | Differential privacy audits with exact hockey-stick curves |
| [CausalLab](https://github.com/midya8/counterfactuals) | Structural causal models: observation, intervention, counterfactual |
| [SegmentLab](https://github.com/midya8/change-points) | Changepoint inference with exact Gaussian partition marginals |
| [CutLab](https://github.com/midya8/graph-cuts) | Exact rational graph cuts for binary submodular energies |
| [FactorLab](https://github.com/midya8/variable-elimination) | Variable elimination with every join and fill edge visible |
| [SubmodLab](https://github.com/midya8/submodular-greedy) | Submodular selection with greedy traces and proof-derived bounds |
| [DPPLab](https://github.com/midya8/dpp-subsets) | Determinantal point processes with exact rational subset laws |
| [CTCLab](https://github.com/midya8/ctc-alignment) | CTC loss from scratch: log-space forward/backward and gradients |
| [ScanLab](https://github.com/midya8/prefix-scans) | State-space scans with failure controls and JVP/VJP audits |
| [SparseLab](https://github.com/midya8/lasso-solver) | LASSO audits: KKT, duality and Gap Safe zero certificates |
| [InfluenceLab](https://github.com/midya8/influence-functions) | Influence functions for logistic models, with deletion paths |
| [FisherLab](https://github.com/midya8/policy-geometry) | Natural policy-gradient geometry with exact Fisher solves |
| [ScoreLab](https://github.com/midya8/policy-gradient-variance) | Policy-gradient score functions with exact covariance checks |
| [BanditLab](https://github.com/midya8/bayesian-bandits) | Beta-Bernoulli bandit planning with exact posterior graphs |
| [BeliefLab](https://github.com/midya8/belief-planning) | Finite-horizon POMDP planning with policy trees |
| [BellmanLab](https://github.com/midya8/mdp-planning) | Discounted and robust dynamic programming with residual certificates |
| [ErgodLab](https://github.com/midya8/stationary-gradients) | Stationary-distribution sensitivity for Markov decision processes |
| [VariLab](https://github.com/midya8/variational-inference) | Mean-field variational inference from scratch |
| [RobustLab](https://github.com/midya8/adversarial-margins) | Exact norm-ball margins for linear adversarial robustness |
| [TransportLab](https://github.com/midya8/optimal-transport) | [Normalized-marginal tangent workbench](https://midya8.github.io/optimal-transport/): every fixed update, actual/requested mass tangents and complete JSON; finite computation, not an optimum certificate |
| [RectLab](https://github.com/midya8/rectangle-cover) | Every optimal factor set in rectangle covers, indexed exactly |
| [CompileLab](https://github.com/midya8/bdd-compilation) | Boolean knowledge compilation into inspectable decision graphs |
| [FireLab](https://github.com/midya8/petri-nets) | Petri-net inspector separating token balance from executability |
| [ParetoLab](https://github.com/midya8/pareto-paths) | Biobjective planning that keeps all Pareto tradeoffs |
| [TreeLab](https://github.com/midya8/decision-trees) | Budgeted counterfactual search over tree ensembles |
| [DigitLab](https://github.com/midya8/adversarial-digits) | Live inspector for UCI digit models with Integrated Gradients |

### Ops tooling

| Project | What it is |
| --- | --- |
| [sre-toolkit](https://github.com/midya8/sre-toolkit) | Error budgets, burn-rate alerting, alert triage and noise ranking |
| [loglens](https://github.com/midya8/loglens) | Access-log triage for the first five minutes of an incident |
| [flowkit](https://github.com/midya8/flowkit) | JSON-defined DAG workflow runner with retries and timeouts |
| [uptimekit](https://github.com/midya8/uptimekit) | Synthetic HTTP/TCP/TLS uptime monitoring and availability reports |
