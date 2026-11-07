## Hi, I'm Midya

I'm a Toronto-based technologist with 12+ years across technology, financial
services and telecommunications. Lately I'm building with large language models,
agentic systems and workflow automation.

### Projects

**[HamiltonLab](https://github.com/midya8/hamiltonlab)**

Hamiltonian Monte Carlo from scratch with full rejection histories, leapfrog energy/reversibility and quadratic resonance audits. High acceptance can hide zero mode switches or almost-identity trajectories; optional state-independent random lengths retain every choice and work count. Rank-normalized split/folded R-hat exposes deterministic scale and half-chain failures missed by classical ratios; undefined components remain null. 75 tests, dependency-free Python, offline sample/demo/quadratic/diagnose/harmonic/window/window-mixture CLI and SVG. No speed ranking, adaptive NUTS, ESS/MCSE or convergence certificate. Synthetic chains and analytic truths, not fitted posterior results. Analytic Gaussian flow separates mass/phase effects from integration error, with exact sign-flip and identity counterexamples. Fixed and IID random-duration q/q² covariance audits expose frozen magnitude even with zero position correlation; no sampled-chain ESS/MCSE claim.

**[TransportLab](https://github.com/midya8/transportlab)**

Log-domain entropic optimal transport with full mass plans, explicit nonconvergence and weighted interpolation atoms. Full pushforward preserves actual endpoint marginals; barycentric means do not. Separate rounded primal/dual audits retain raw failed solves and report signed numerical gaps, marginal residuals and L1 changes. Analytic fixed-iteration plan tangents expose a nonconverged envelope-shortcut error0.007670872, checked against central differences. Zero support, covariance decomposition and exact tiny assignment remain visible. 46 tests, offline solve/assignment/push/audit/sensitivity CLI and SVGs. Not a metric, sampled trajectory, implicit-optimum gradient or certified OT bound.

**[FlowLab](https://github.com/midya8/flowlab)**

Affine-coupling flow from scratch: exact fitted-model density, inverse sampling, analytic input scores and bounded conditional CDF/quantile slices. Aligned window audits reuse one scored grid and expose renormalization effects: narrowing[-4,4] to[-1,1] removes24.35%-31.94% of interpolated mass inside the finite outer window. An analytic narrow-peak counterexample shows two agreeing grids can both be wrong. 45 tests, strict artifacts, offline CLI/SVGs and actual call budgets. No whole-line tail, exact-conditional, calibrated-coverage, OOD or causal claim.

**[GraphLab](https://github.com/midya8/graphlab)**

Two-layer GCN from scratch with exact input-margin gradients and budgeted single-edge deletion sensitivity. Input locality differs from graph normalization: node 3 has zero feature gradient for node 0, yet deleting edge 2-3 changes its margin by +0.016852 after degree renormalization. Full signed contributions, every edge effect, preflight call budgets and zero-gradient/large-change counterexample. Original transductive development results remain: selected GCN0.96875, MLP0.34375, scrambled GCN0.515625; final/centroid controls visible. Synthetic graph carries class signal; no causal, probability-attribution, unseen-graph or general ranking claim. 42 tests, strict artifacts and offline CLI/SVGs.

**[DiffuseLab](https://github.com/midya8/diffuselab)**

Learned 2-D diffusion from scratch, now with selected-grid DDIM sampling and exact denoiser-call audits. The same 482-parameter model uses 8/16/64 DDIM steps without retraining. Eight steps saves 87.5% of predictor calls but has worse symmetric reference distance here (0.210661 vs DDPM 0.037103), despite a slightly higher near-center fraction. All 8 neighborhoods reached, uneven frequencies and outliers retained. Full-grid eta=1 matches DDPM arithmetic with matched draws. 33 tests, strict artifacts and offline train/sample/DDIM CLI. Development fixture only, no walltime speedup, image-generation or general ranking claim.

**[ChainLab](https://github.com/midya8/chainlab)**

Hidden Markov models from scratch: log-space inference, Viterbi paths and multi-sequence Baum-Welch, now with prefix-only filtering and multi-step symbol/state forecasts. An exact example separates x-only filtering P(A)=2/3 from future-informed x/y smoothing P(A)=0. Forecasts are dependent horizon marginals, not a joint path. Prefix predictive log scores match full likelihood to about 5.68e-14 on the seed23 development fixture; that is an implementation audit, not a new quality gain. Existing test NLL per symbol: trained0.775631, iid control0.985993, initialization1.017638, generating reference0.771674. Exhaustive references, impossible-prefix rejection, 34 tests and offline CLI/SVG demo. No calibration or state-recovery claim.

**[KernelLab](https://github.com/midya8/kernellab)**

Gaussian-process regression and finite-grid expected-improvement suggestions from scratch. Cholesky solves, separate latent/observation covariance, explicit jitter, marginal likelihood and fixed-parameter LOO. Deterministic EI excludes known rows and returns a full candidate audit, without executing evaluations. A nine-evaluation toy optimization comparison reports grid regret 0.000163 (EI), 0.072944 (space filling) and 0.399473 (one seeded random control). Same pool/initialization/budget; development data, no general ranking or continuous optimum claim. The regression misspecification counterexample remains visible. Dependency-free Python, 36 tests, offline CLI and reproducible SVGs.

**[BoostLab](https://github.com/midya8/boostlab)**

Binary gradient boosting from scratch: mean-residual defaults plus optional capped, L2-regularized Newton leaves on residual-SSE trees. The development fixture selects 35 Newton trees/237 nodes, test accuracy 0.9004/logloss 0.3341; its unselected 80-round checkpoint is also shown (0.8984/0.3469). Mean depth-2 control: 0.8906/0.3400; full-budget stumps: 0.6367/0.7366. Different capacity and settings, no causal or external-benchmark claim. Backward-compatible v1/v2 inference, Hessian/leaf arithmetic tests, validation-only prefix selection. Dependency-free Python, 29 tests and offline CI.

**[ShapleyLab](https://github.com/midya8/shapleylab)**

Exact small-feature Shapley attribution from scratch: all empirical-background coalitions auditable, callback API and JSON CLI. Same product prediction 6 gives [3, 3, 0] or [2, 3, 0] with different backgrounds. An off-manifold hybrid counterexample passes additivity, showing why exact arithmetic is not explanation validity. Joint missing-feature dependence preserved; preflight exponential-work budget; independent factorial reference checks. No conditional/causal or trained-model quality claim. Optional atomic groups move correlated blocks together. Three-way product gives grouped [1/2, 1/2], not post-hoc [2/3, 1/3]; grouped games answer a different question. Up to 64 raw features/12 groups, no within-group credit split or cross-group dependence guarantee. Optional seeded permutation mode handles up to 64 individual features with cached coalitions and descriptive MC standard errors. A two-permutation product gives [0.5, 0.5, 0] despite exact [1/3, 1/3, 1/3], showing zero observed MC error is not an accuracy bound. No confidence guarantee or sampled groups. Dependency-free Python, 43 tests and offline CI.

**[PolicyLens](https://github.com/midya8/policylens)**

Offline contextual-bandit evaluation from scratch: IPS, SNIPS, direct and doubly robust estimates with support/weight diagnostics. On a constructed balanced design, IPS/SNIPS/DR recover target 0.78 despite a wrong reward model; clipping raises ESS but moves DR to 0.535. A separate noisy log with oracle reward predictions gives DR 0.7532, not exact truth. No causal-identification, confidence-bound or deployment-safety claim; explicit propensity, support and nuisance-prediction assumptions. Optional held-out categorical reward fitting reports fold/cell counts and prior-only predictions; row-iid splitting does not fix grouped or sequential leakage. On the same noisy log, fitted DR 0.7509088 is not better than oracle DR. Dependency-free Python, 28 tests and offline CI.

**[DriftLens](https://github.com/midya8/driftlens)**

Embedding-distribution comparison from scratch: unbiased RBF MMD, cached-kernel permutations, exact tiny-sample tests and complement-sum scoring for imbalanced groups and a JSON CLI/API with Holm-corrected prespecified bandwidth families and optional within-block permutations, plus descriptive row-index witness diagnostics (not causal attribution). Selected 30x4 development fixture: same-generator p=0.550, mean-shift p=0.002 (the 1/500 resolution floor); a tiny separated 2-vs-2 sample still has exact p=1/3. No power-benchmark, cause, downstream-accuracy or continuous-monitoring claim. Explicit exchangeability and prespecified bandwidth assumptions; non-rejection is not equivalence. Dependency-free Python, 45 tests and offline CI.

**[SetGuard](https://github.com/midya8/setguard)**

Split-conformal classification sets from scratch: JSON fit/predict artifacts, finite-sample rank correction, exact tied-score audits and per-class/size diagnostics, plus optional label-conditional classwise thresholds with explicit rare-class inclusion. On the five-class development fixture, target 0.9 gives empirical coverage 0.9235 at mean set size 3.017 versus argmax accuracy 0.4960; a deliberately adversarial label shift drops coverage to 0.0760. The standard marginal-coverage theorem needs exchangeability and a predictor fixed independently of calibration, not every realized class rate/input or shifted-data guarantees. Classwise mode targets coverage within true labels under its stated exchangeability assumptions, at a set-size cost. Dependency-free Python, 31 tests and offline CI.

**[CalibrLab](https://github.com/midya8/calibrlab)**

Confidence calibration from scratch in pure Python, with a JSON CLI/API for your own validation/test logits and unclipped logit-space NLL, plus optional conditional paired test-row bootstrap intervals: an overfit small-data MLP (train 1.0000, test 0.5563) is measured badly overconfident on the checked-in fixture (ECE 0.2765; top bin 0.9735 confidence at 0.6602 accuracy), then one temperature fit on validation NLL only cuts ECE to 0.0651 and test NLL from 2.0030 to 1.2060 at exactly zero accuracy change - the invariance asserted bit-for-bit, the oracle-T gap reported (0.0076), and gradients hand-derived and finite-difference verified. (45 tests)

**[DistillLab](https://github.com/midya8/distilllab)**

Knowledge distillation from scratch in pure Python: a 10x smaller student gains +0.0656 test accuracy over direct training on the checked-in fixture (0.7469 vs 0.6813; teacher 0.8344), measured against matched control arms - pseudo-labels on the teacher's argmax exceed direct by +0.0281 and soft-label distillation exceeds pseudo by +0.0375, with uniform smoothing adding nothing and a permuted-target arm at chance; these between-arm differences are fixture measurements, not causal attribution. Gradients hand-derived and finite-difference verified, overfit gap measured (0.3187 direct vs 0.0531 distilled). (12 tests)

**[MoeLab](https://github.com/midya8/moelab)**

Mixture-of-experts from scratch in pure Python: Switch-style sparse routing over linear experts on a regime-switching fixture, beating a measured same-budget MLP baseline 0.0303 vs 0.1853 test MSE, worst-regime routing purity 1.0000, soft-vs-sparse gap measured (0.6291 vs 0.0303), gradients hand-derived and finite-difference verified, and an honest note that the load-balancing term earns nothing on this symmetric fixture. (9 tests)

**[AlignLab](https://github.com/midya8/alignlab)**

Preference-based alignment from scratch in pure Python: train a Bradley-Terry reward model on pairwise preferences (0.7800 holdout accuracy vs 0.4333 for a noise-trained control), then align a policy by gradient ascent on expected reward minus an exact KL penalty - true latent utility rises 2.04 to 4.62 while on the checked-in fixture the label-noise control buys almost nothing (a fixture comparison, not a general proof), the beta=0 collapse ablation is gated, and every expectation and gradient is closed-form and finite-difference verified. (15 tests)

**[LoRALab](https://github.com/midya8/loralab)**

Low-rank adaptation from scratch in pure Python: freeze a trained model, learn only a rank-r delta W + B@A with hand-derived gradients, and measure all three sides of the trade-off - accuracy on the shifted distribution (0.44 recovered to 1.0000 at rank 2 on the checked-in fixture), trainable-parameter share (67.7% of full fine-tuning), and retained accuracy on the original distribution, with merge equivalence pinned to floating-point reassociation error and gates that fail in both directions. (14 tests)

**[SpecLab](https://github.com/midya8/speclab)**

Speculative decoding from scratch in pure Python: a draft model proposes token blocks, a target model verifies each block, and a greedy-construction invariant keeps output identical to target-only decoding - the implementation verified token-for-token on tested configs and gammas - while modeled verification rounds drop 74.6% on the checked-in fixture (acceptance 0.800), with actual scoring work reported alongside the modeled count. Dependency-free Python, 14 unit tests, a fully offline demo, and CI across Python 3.10-3.13.

**[StructGate](https://github.com/midya8/structgate)**

Grammar-constrained generation from scratch in pure Python: incremental JSON and closed-schema validators compute the exact legal next-token set per prefix, an exact n-gram distribution is masked to it during generation, and the trade-off is measured - 40/40 schema-conforming draws vs a 3/40 unconstrained control, with the renormalization cost reported per step in nats (mean 1.35 grammar, 0.82 schema on the checked-in fixture). Dependency-free Python, 33 unit tests, a fully offline demo, and CI across Python 3.10-3.13.

**[QuantLab](https://github.com/midya8/quantlab)**

int8 post-training quantization from scratch in pure Python: symmetric
per-tensor and per-channel scales, byte-exact size accounting, and a trained
fixture model whose int8 accuracy cost is measured exactly (0.0000 drop at
3.765x smaller storage on the checked-in fixture), plus a controlled study
locating where quantization error lives (+39.14 dB small-row SNR for
per-channel). Dependency-free Python, 28 unit tests, a fully offline demo,
and CI across Python 3.10-3.13.

**[RAGLine](https://github.com/midya8/ragline)**

Retrieval-augmented answering from scratch in pure Python: deterministic corpus,
token-hashed sparse embeddings, top-k retrieval, extractive answers that cite
their source chunk, and a lexical-overlap grounding check shown to flag a
corrupted citation in a tested negative control. Fixture evaluation pinned in CI (recall@3 1.00, MRR 0.94, grounded
1.00). Dependency-free Python, 31 unit tests, a fully offline demo, and CI
across Python 3.10-3.13.

**[KVLens](https://github.com/midya8/kvlens)**

KV-cached incremental decoding from scratch in pure Python: batched prefill plus
one incremental step per token, verified bitwise-identical to full recompute
(max logit difference exactly 0.0 across configs), with measured matmul FLOP
savings (90.8% at 32 generated tokens on the default fixture) and CI gates.
Dependency-free Python, 28 unit tests, a fully offline demo, and CI across
Python 3.10-3.13.

**[AttnLens](https://github.com/midya8/attnlens)**

Causal multi-head self-attention trained from scratch in pure Python: hand-derived
backpropagation finite-difference-checked for every parameter group on the test
fixture, and a marker-recall task where the trained model's query position
concentrates attention on the recalled key (~0.9 weight, measured on the
checked-in seed), with per-head pattern analysis wired into CI gates.
Dependency-free Python, 46 unit tests, a fully offline demo, and CI across
Python 3.10-3.13.

**[EmbedKit](https://github.com/midya8/embedkit)**

Word embeddings trained from scratch with pure-Python SGNS: sigmoid-gradient
SGD with unigram^0.75 negative sampling, one seeded RNG for reproducible
vectors, and a topic-coherence evaluator (neighbor purity plus an
intra/inter separation margin) wired into CI gates. Dependency-free Python,
40 unit tests, a fully offline demo, and CI across Python 3.10-3.13.

**[PlanBench](https://github.com/midya8/planbench)**

Validation and deterministic simulation of agent task plans before they run:
semantic DAG checks (unknown tools, cyclic dependencies, unproduced inputs),
a seeded parallel simulator with flaky tools, retries and skip cascades, and
makespan/cost/critical-path/parallelism metrics with CI gates. Dependency-free
Python, 29 unit tests, a fully offline demo, and CI across Python 3.10-3.13.

**[DecodeLab](https://github.com/midya8/decodelab)**

Decoding strategies for language models from scratch: greedy decoding, seeded
temperature/top-k/top-p sampling, and beam search over an exact n-gram
distribution, with generation-quality metrics (distinct-n, repetition,
entropy), JSON/Markdown reports, and CI gates. Dependency-free Python,
36 unit tests, a fully offline demo, and CI across Python 3.10-3.13.

**[VectorLite](https://github.com/midya8/vectorlite)**

Exact and approximate kNN vector search from scratch: brute-force exact kNN
(cosine and L2), a seeded random-hyperplane LSH index for approximate cosine
search, and recall@k of the approximate index measured against the exact
baseline and enforced with a CI gate. Dependency-free Python, 31 unit tests,
a fully offline demo, and CI across Python 3.10-3.13.

**[GroundCheck](https://github.com/midya8/groundcheck)**

Offline lexical grounding checks for answers against their sources: citation
validation, per-sentence lexical support scoring against source documents,
numeric consistency checks, terminal/JSON/Markdown reports, and CI gates
that fail on lexically ungrounded output. Dependency-free Python, 43 unit tests, a
fully offline demo, and CI across Python 3.10-3.13.

**[TokenForge](https://github.com/midya8/tokenforge)**

Byte-level BPE tokenizers trained from scratch: deterministic merge training
with exact pair counts over GPT-2-style pre-tokenization boundaries,
rank-ordered encoding with exact round trips, JSON vocab persistence, and
compression statistics with JSON/Markdown reports and a CI quality gate.
Dependency-free Python, 40 unit tests, a fully offline demo, and CI across
Python 3.10-3.13.

**[RetrievalBench](https://github.com/midya8/retrievalbench)**

Offline retrieval evaluation for RAG and search pipelines: an exact Okapi
BM25 index over local JSONL corpora, token-window chunking with overlap and
parent-document collapsing, graded qrels, per-query and macro-averaged
recall@k/precision@k/MRR/nDCG@k, JSON and Markdown reports, and quality
gates that fail CI on retrieval regressions. Dependency-free Python, 42
unit tests, a fully offline demo, and CI across Python 3.10-3.13.

**[EvalForge](https://github.com/midya8/evalforge)**

Local-first evaluation for LLM and agent outputs: versioned JSONL task
suites, deterministic exact/contains/regex/JSON/similarity/numeric/length
checks, a stdin/stdout adapter contract, retries, timeouts, bounded
parallel execution, JSON run artifacts, baseline regression gates, and
self-contained escaped HTML, JUnit XML, Markdown and SARIF run/comparison
reports. Dependency-free Python, 68 unit tests, a fully offline demo that
validates JUnit, Markdown and SARIF run/regression output, and CI across
Python 3.10-3.13.

**[AgentTrace](https://github.com/midya8/agenttrace)**

Local-first validation, analysis and reporting for AI agent execution
traces: JSONL structure checks, run summaries, tool/LLM call counts, latency
and cost rollups, graph depth, repeated-step loop detection, baseline/candidate
regression comparison, CI-friendly quality gates, a standalone escaped HTML
timeline, deterministic JUnit XML output for CI test viewers, Markdown
job summaries, and SARIF 2.1.0 output for code-scanning integrations.
Dependency-free Python, 33 unit tests, a fully offline
fixed-trace baseline/candidate demo that validates JUnit, Markdown and SARIF
output, and CI across Python 3.10-3.13.

**[PromptGuard](https://github.com/midya8/promptguard)**

Local-first prompt, secret and prompt-injection linting for AI systems:
OpenAI/AWS-style key, GitHub/Slack/Google token and JWT checks, assigned-secret
and private-key detection, email/phone/Luhn-validated card detection,
injection-language rules, prompt metadata frontmatter checks, redacted
terminal, JSON, SARIF, JUnit XML, Markdown and escaped HTML reports, severity
or finding-count CI gates, and fingerprint-based baseline suppression so CI
only gates on new findings.
Dependency-free Python, 68 unit tests, a fully offline fixture demo that
validates SARIF, JUnit and Markdown output and the baseline suppression flow
against safe, risky and runtime-generated token fixtures, and CI across Python
3.10-3.13.

**[ScratchGPT](https://github.com/midya8/scratchgpt)**

A GPT built and trained from scratch in pure NumPy: a ~400-line reverse-mode
autograd engine with hand-written backward rules, a pre-LN causal transformer,
Adam training, resumable checkpoints, and a temperature/top-k sampling CLI. The
shipped TinyShakespeare config trains a 419,328-parameter 2-layer/4-head model
to 1.83 nats/char validation loss on CPU; 11 unit tests check gradients
against finite differences and prove no causal attention leak. CI on Python 3.12.

**[sre-toolkit](https://github.com/midya8/sre-toolkit)**

Dependency-free Python utilities for day-to-day SRE work: error-budget and
burn-rate math with exhaustion projection, multi-window burn-rate alerting
with custom rules, alert triage with fire counts, noisiest-first noise
ranking and critical-driven inhibition with custom rule files, SLO definitions (Markdown or JSON), status
reports with budget-exhaustion projections, and postmortems with automatic
response
metrics and per-severity MTTR aggregation with p90 percentiles, plus
fleet-wide roll-ups across incident sets (report summaries, triage by
severity, metrics by service), bounded, reasoned alert silences, and
burn-rate policy suggestion (--suggest emits the standard multi-window
table for any SLO window), postmortem action-item follow-through
(open items per incident, stale-flagged and gate-able via exit codes), and
burn-rule time-series replay (firing intervals per rule over a timestamped
series, for alert-policy tuning), and alert ownership routing
(services mapped to owning teams with an explicit default; per-team
roll-ups, worst severity first). CLI and
importable
library, 254 unit tests,
CI across Python 3.10-3.13.

**[loglens](https://github.com/midya8/loglens)**

Access-log analysis for the first five minutes of an incident: error rate,
status distribution, hottest failing paths, and the source IPs behind 5xxs,
plus incident timelines, p50/p95/p99 latency, time-window filtering, per-path
breakdowns, a 2xx/3xx/4xx/5xx status-class roll-up, method, user-agent and
referer
triage behind 5xxs, a listing of the individual requests behind
the 5xxs, hour-of-day pattern breakdowns, consecutive-bucket spike
windows, throughput and fixed-bucket latency-distribution reports,
response-size (bandwidth) analysis, baseline-log comparison, Apdex
user-satisfaction scoring (overall and per-path, with a --min-apdex
pipeline gate), a failing-path status pivot (per-endpoint status-code
counts), and
Markdown incident
reports with spike windows and before/after deploy comparisons. Status and
time-window filters scope every statistic. Parses nginx/Apache combined and
JSON logs with per-line auto-detection, standard library only,
241 unit tests.

**[flowkit](https://github.com/midya8/flowkit)**

Dependency-free workflow runner: JSON-defined DAGs of shell commands with
retries and exponential backoff, per-attempt timeouts, fail-fast or
continue-on-error semantics, parallel execution of independent steps,
conditional steps and subset runs, end-phase hook steps
(trigger: on_failure, on_success or finally) for outcome-pinned
cleanup/notify work, and a
dry-run plan mode. Layered flow/step environment variables interpolate into
commands with a strict pre-run check, and run reports show captured output
tails (text or JSON, optionally written to a report file, with full
per-step logs on disk). Definitions are
validated up front (duplicates, dangling dependencies, cycles) and run in
deterministic topological order. Standard
library only, 123 unit tests, CI across Python 3.10-3.13.

**[uptimekit](https://github.com/midya8/uptimekit)**

Synthetic uptime monitoring and availability reporting in pure Python:
HTTP, TCP and TLS certificate-expiry probes with latency, keyword and
latency assertions, an append-only JSONL history with atomic retention,
availability roll-ups with p50/p95 latency, per-day trends and
window-over-window comparison, incident detection with a flap guard and a
sustained-outage gate, a watch mode for cron-less hosts, and a
self-contained HTML status-page renderer. SLO targets report error budget consumed and met-or-breached status, with a `--fail-slo` gate that exits 1 on breach. `check` exits 1 on any failure
so cron doubles as alerting. Standard library only,
98 unit tests running fully offline.

**[KISA website](https://github.com/midya8/kurdistansociology-website)** · [kurdistansociology.com](https://kurdistansociology.com)

Website for the Kurdistan International Sociological Association in English,
Sorani Kurdish (right-to-left) and Kurmanji Kurdish. Built with Next.js,
TypeScript and Tailwind, exported as static HTML and hosted on Cloudflare.

**[Personal site](https://github.com/midya8/midya.ca)** · [midya.ca](https://midya.ca)

My personal site, set against a procedural Three.js galaxy that adapts its
rendering quality to the device and respects reduced-motion settings. Built with
React, TypeScript and Vite.

### Find me

[midya.ca](https://midya.ca) · [LinkedIn](https://www.linkedin.com/in/midyarahmani/)
