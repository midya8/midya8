## Hi, I'm Midya

I'm a Toronto-based technologist with 12+ years across technology, financial
services and telecommunications. Lately I'm building with large language models,
agentic systems and workflow automation.

### Projects

**[CutLab](https://github.com/midya8/cutlab)**

Exact binary submodular energy graph cuts with signed rational offsets, every pair/terminal reduction, shortest augmenting paths including reverse routing, every-cut residual dual slack and the full SCC/closure optimum family. A strict single-flip control stops at energy 2 while the certified joint optimum is 0; a unary-only control has gap 2. Independent Python/BigInt agree on 24 reports / 24,624 exact leaves. 21 Python tests on 3.10-3.13, complete rendered records, SVG checks and installed reproduction. Supplied synthetic costs, at most six variables; classical methods, no learned model, image benchmark, speed or new-algorithm claim.

[Live inspector](https://midya8.github.io/cutlab/) · [Method and limits](https://github.com/midya8/cutlab/blob/main/METHOD.md)

**[FactorLab](https://github.com/midya8/factorlab)**

Exact rational finite factor elimination with every joined product, reduction/tie, fill edge and small-order census. A mixed sum/max control returns an upper bound of 11 versus true marginal-MAP mass 10, while joint MAP weight 6 projects to the wrong decision. A five-variable star gives the same partition at 62 versus 18 joined entries, width 4 versus 1. Independent Python/BigInt agree on 24 reports / 23,114 exact leaves; 24 Python tests on 3.10-3.13, dense partial-product oracles, full-record Chrome checks and installed reproduction. Supplied synthetic potentials, not learned quality, a scalable solver or a timing benchmark. [Live elimination inspector](https://midya8.github.io/factorlab/) · [Method and limits](https://github.com/midya8/factorlab/blob/main/METHOD.md).

**[SubmodLab](https://github.com/midya8/submodlab)**

Exact rational finite subset selection with every greedy marginal, optimum tie, monotonicity edge, local diminishing-return witness and proof-derived cardinality upper bound. The retained coverage counterexample gives greedy 5 versus optimum 6; a separate singleton top-k control gives 5 versus updated greedy 9. Invalid synergy/nonmonotone tables withhold theorem fields. Dependency-free Python and independent BigInt JavaScript agree on 24 complete reports / 16,426 exact leaves, with 24 Python tests on 3.10-3.13 and actual-Chrome checks of 360 subset rows/bars and 2,056 full records. Established theory on at most six items, not learned similarity, a scalable optimizer or downstream selection quality. [Live selection inspector](https://midya8.github.io/submodlab/) · [Method and limits](https://github.com/midya8/submodlab/blob/main/METHOD.md).

The separate rounding inspector now exposes the exact multilinear extension, every excluded-item gradient and excluded-pair Hessian context, independent-product count probabilities and both endpoints of every deterministic cardinality swap. A two-item half-probability control has expected count 1 yet exceeds budget 1 with probability 1/4; its duplicate-coverage expectation 3/4 rounds to a singleton worth 1. Nonmonotone submodular controls are accepted, while synergy and wrong total probability mass refuse rounding. The extension adds nine Python tests (33 total), 21 reports matching 10,682 exact native/BigInt leaves, independent product/derivative/path oracles, full-record Chrome checks and installed reproduction. This is bounded deterministic rounding, not continuous optimization, randomized marginal preservation, a general matroid method or a learned-quality claim.

[Live rounding inspector](https://midya8.github.io/submodlab/rounding.html) · [Rounding method](https://github.com/midya8/submodlab/blob/main/ROUNDING.md)

**[DPPLab](https://github.com/midya8/dpplab)**

Exact-rational finite DPP subset laws with every determinant, inclusion-kernel witness, Schur include/exclude conditioning and fixed-total-size contrast. Dependency-free Python and independent BigInt JavaScript agree on 24 complete reports / 4,050 exact leaves; 24 Python tests on 3.10-3.13 and actual-Chrome full-record/geometry checks. Duplicate-item controls separate zero co-occurrence from equal-marginal independence. Established bounded L-ensembles, not learned relevance, a scalable sampler or a downstream quality result. [Live subset inspector](https://midya8.github.io/dpplab/) · [Method and limits](https://github.com/midya8/dpplab/blob/main/METHOD.md).

**[CTCLab](https://github.com/midya8/ctclab)**

Offline CTC target marginalization with log-space forward/backward, full state/symbol posteriors and logit gradients, plus every exhaustive path and collapsed transcript. The editable independent JavaScript inspector shows why a greedy best path can lose to summed transcript mass: two uniform blank/A frames assign 0.25 to empty output and 0.75 to A. Twenty retained reports, 25 Python tests across 3.10-3.13, Decimal/state enumeration, 300 finite-difference checks and real-Chrome full-record/diagram audits. Established CTC on tiny synthetic logits, not a trained recognizer, speech/OCR benchmark or novel algorithm; numerical rank buckets and impossible-target conventions are explicit. [Live alignment inspector](https://midya8.github.io/ctclab/) · [Method and limits](https://github.com/midya8/ctclab/blob/main/METHOD.md).

**[PPOlab](https://github.com/midya8/ppolab)**

From-scratch NumPy PPO with a corrected internal-timeout collector, separate bootstrap/trace masks, full GAE credit matrices and sign-dependent clip-gradient audits. Independent scalar JavaScript evaluates all 4,675 checkpoint parameters and real CartPole physics. Fifty Python tests retain all 18 original tests; four Node/actual-Chrome tests compare 26 full reports/12,408 numbers and all 14,871 original one-step observations. New free-running paths can diverge: the reference run differs on 377 actions despite matching all 30 return lengths. Original checkpoint/results retained; no training-improvement, speed, trajectory-equivalence, KL-bound or universal-solve claim. [Live boundary and policy inspector](https://midya8.github.io/ppolab/) · [Equations, bug and limits](https://github.com/midya8/ppolab/blob/main/BOUNDARIES.md).

**[TagLab](https://github.com/midya8/taglab)**

Manual linear-chain conditional random fields with analytic gradients and all 327 optimization states replayed. The selected chain improves test NLL (0.557614 versus 0.813715) but loses on Viterbi token errors (66/164 versus the trained same-feature control's 56/164). Exact fixed-score inference covers position-wise label events, auditable joint-path sampling and nonlocal occurrence-count events. Count-augmented prefix/suffix messages expose complete count laws, conditional nodes/pairs, best paths and event derivatives. An independent-node count control shows why matching expected counts does not enforce an exact total. 43 Python and 20 Node/Chrome tests cover rational/BigInt path oracles, finite differences, cross-language witnesses and 5,895 UI states/queries; eleven-module/nine-command installed reproduction. Original synthetic sequences, not an NLP benchmark, causal experiment or calibrated confidence. Original fits and budget-exhaustion warnings stay visible; deterministic PRNG, finite-precision and near-tie limits are explicit. [Count inspector](https://midya8.github.io/taglab/counts.html) · [Label events and joint sampling](https://midya8.github.io/taglab/evidence.html) · [Training inspector](https://midya8.github.io/taglab/) · [Method and limits](https://github.com/midya8/taglab/blob/main/METHOD.md).

**[SpectralLab](https://github.com/midya8/spectrallab)**

Normalized spectral clustering with manual affinity/Laplacian/k-means code and explicitly disclosed NumPy eigensolves. All 18 fixed graphs and raw k-means controls remain visible; larger eigengaps and spectral rounding can still give worse answers. v0.2 adds full degree-response derivatives and a basis-invariant projector tangent, four smooth base graphs, 28 fixed finite states including a boundary refusal, and two refused base controls. Shared-scale heatmaps compare actual refits with first-order geometry; numerically equal tested rounding partitions remain explicit, not a label-gradient or robustness claim. Thirty-three Python and nine Node/real-Chrome tests cover independent graph/cut references, 83 derivative controls, repeated-block rotations, 1,728 original browser point states and 168 new sensitivity states. Installed six-module/nine-command reproduction checks four exact exports. Original synthetic full-data illustrations, not held-out prediction or exact discrete optimization. [Graph inspector](https://midya8.github.io/spectrallab/). [Sensitivity inspector](https://midya8.github.io/spectrallab/sensitivity.html). [Derivation and limits](https://github.com/midya8/spectrallab/blob/main/SENSITIVITY.md).

**[ForestLab](https://github.com/midya8/forestlab)**

Manual binary CART forests with exact integer Gini split ordering, complete bootstrap-count witnesses and an editable inspector that separates full-forest votes from OOB votes. Exact-copy grouping prevents identical licensed UCI feature vectors from crossing partitions. All eight forests, four single trees and seven controls stay visible: the validation-selected forest makes 3/270 test errors, versus a stronger selected 5NN control at 0/270 and a single tree at 8/270. 39 Python and 12 Node/real-Chrome tests cover 60 rational split oracles, 10,784 forest comparisons, 8,088 control scores, 6,464 OOB membership records and 992 actual browser paths. Ten-module/ten-command installed reproduction. Historical numeric classification, not banknote authentication; vote fractions are not calibrated probabilities and OOB is not independent specimen validation. [Live forest and OOB inspector](https://midya8.github.io/forestlab/). [Method and limits](https://github.com/midya8/forestlab/blob/main/METHOD.md). V0.2 adds [joint permutation diagnostics](https://midya8.github.io/forestlab/permutation.html): all 15 feature blocks, 16 shared shuffles and 129,600 model-row prediction checks, including the stronger frozen 5NN control. Donor/recipient witnesses and an exact support counterexample stay visible. Reused-validation description, not causal importance, fresh test performance or uncertainty intervals.

The v0.3 [leaf-collision inspector](https://midya8.github.io/forestlab/proximity.html) exposes all-tree similarity as an explicit Gram matrix, with exact integer/BigInt sum-of-squares witnesses. A separate jointly-OOB view keeps pair-specific tree counts and undefined comparisons. A constructed negative quadratic form (-2) and triangle failure show why OOB normalization is not a universal kernel guarantee. All 512 small partition controls, 5,760 native/scalar-JS matrix entries, 1,152 actual pair states and 13,824 heatmap colors are checked. Frozen supervised model geometry, not semantic similarity, causal influence, uncertainty or a new score. [Geometry derivation and limits](https://github.com/midya8/forestlab/blob/main/PROXIMITY.md).

**[RatingLab](https://github.com/midya8/ratinglab)**

Observed-only rating factorization with manual NumPy alternating ridge solves, per-block decrease accounting, normal-equation residuals and full gradients. All eleven fits remain inspectable. A separately validation-selected bias-only control slightly beats the selected factors on test RMSE (.656176 versus .656457); all eight factor fits exhaust their stationarity budget. 37 Python and 14 Node/real-Chrome tests include 60 independent exact rational ridge references, eleven fresh refits, test-label poisoning and 12,771 scalar/native predictions. The browser recomputes arbitrary indexed pairs and shared factor rotations, exposing why coordinate products are not causal preferences. Ten-module installed wheel with eight main CLI commands and two single-row conditional-response module commands. CC BY 4.0 historical UCI ratings, MIT code. Missing pairs are not negatives, and observed-rating RMSE is not top-N relevance, missing-pair accuracy or calibrated certainty. [Live rating inspector](https://midya8.github.io/ratinglab/). [Equations and limits](https://github.com/midya8/ratinglab/blob/main/METHOD.md).

The v0.2 conditional-response extension separates saved scores, a freshly re-solved unmodified ridge block and its finite rating edit or row deletion. It exposes leverage, the positive deletion denominator, query derivatives and all-opposite-index response curves. Sixty additional exact rational design systems, 2,784 direct deleted-block refits and 576 native/scalar-JavaScript witnesses check the formulas. Original factors and scores are unchanged. The mean and opposite factors remain frozen and retain information from the row: this is not full-model leave-one-out validation, causal influence, data unlearning or an uncertainty bound. [Conditional edit/deletion inspector](https://midya8.github.io/ratinglab/influence.html). [Derivation and limits](https://github.com/midya8/ratinglab/blob/main/INFLUENCE.md).

The v0.3 joint-batch inspector changes or removes multiple original training rows within one frozen block. Target edits add; joint deletions solve a coupled Schur system and generally differ from a sum of separate-original-baseline deletions. It shows the full source-bound problem, conservative positive-ridge bound, numerical condition/refusal checks and all-query joint/separate curves. Independent checks add 320 rational direct-system cases, 128 real augmented-least-squares cases and 320 complete native/browser Cholesky responses plus 4 controls. 37 Python and 14 Node/actual-Chrome tests, ten-module wheel and eight main CLI plus two single-row module commands. Original fits, scores and stronger bias control stay unchanged. This remains a conditional calculation, not full ALS retraining, cross-validation, causal attribution, uncertainty or data unlearning. [Joint batch inspector](https://midya8.github.io/ratinglab/batch.html). [Derivation and limits](https://github.com/midya8/ratinglab/blob/main/BATCH.md).

**[MarginLab](https://github.com/midya8/marginlab)**

Manual linear/RBF soft-margin SVM learning with replayable pair updates and editable30-feature scores. Version0.3 adds exact finite original-unit input boxes: attained affine score bounds, both corners, tie-aware labels, all30interval edits and independent Fraction/BigInt readers with separate source consistency.36Python/15Node-real-Chrome tests include120exhaustive corner cases,256direct exact dual endpoint sums,128full cross-language responses,4,552original inference checks and eight fresh fits. Installed reproduction covers11modules and9maincommands plus the box exporter. Original fits, holdout scores, split and exact training-objective proofs are unchanged. Synthetic boxes are not clinical tolerances or plausible interventions; exact affine arithmetic is not a floating-inference safety, RBF, generalization or authenticity guarantee. [Exact input-box inspector](https://midya8.github.io/marginlab/box.html). [Derivation and limits](https://github.com/midya8/marginlab/blob/main/BOX.md).

**[MixtureLab](https://github.com/midya8/mixturelab)**

Manual Gaussian-mixture EM on licensed UCI chemistry: constrained covariance M-steps, complete likelihood/Q/KL witnesses and a frozen label-free holdout across all 24 fits. Scalar-browser density, input derivatives, full Hessians and bounded sufficient-ascent traces expose the difference between local calculations and mode certificates. Original models, data, splits and scores stay unchanged. Component posteriors are not cultivar probabilities or calibrated certainty. CC BY 4.0 data, MIT code. [Density inspector](https://midya8.github.io/mixturelab/). [Input geometry](https://midya8.github.io/mixturelab/geometry.html).

The new [observed-coordinate conditional inspector](https://midya8.github.io/mixturelab/conditional.html) reweights by marginal evidence and keeps full Schur-complement, within- and between-component covariance. Synthetic controls show a mean in a density gap and variance increasing from 1.09 to 25.1. 45 Python/eleven Node tests cover 100 independent precision-block controls, 5,696 original model/row/mask factorization checks, 160 complete native/scalar-JS references and 160 actual UI cases. Twelve-module/nine-command installed reproduction retains all original refits and audits. Analytical masks on complete source data, not real missingness validation, causal inference, calibrated intervals or new accuracy. [Conditional method and limits](https://github.com/midya8/mixturelab/blob/main/CONDITIONAL.md).

**[PartsLab](https://github.com/midya8/partslab)**

Nonnegative parts learning on the original UCI digits: six manual NumPy factorization fits, fixed-basis NNLS with per-row numerical KKT stopping, and actual editable-input browser decompositions. All 3,823 training images fit without labels; training-only restart selection preserves the 1,797-row official holdout. Rank-matched signed PCA and SVD beat NMF on test MSE at every fixed rank and stay visible. All six joint fits exhaust their stationarity budget, rather than being mislabeled converged. Zero-locking, scale/permutation and duplicate-basis controls expose why additive parts are not unique semantic explanations. 38 Python and eleven Node/real-Chrome tests include independent active-set oracles, finite-difference gradients, full test-loader-prohibited refits, 120 native/browser decompositions and 2,048 contribution pixels. Ten-module/ten-CLI installed wheel; CC BY 4.0 data, MIT code. [Equations, protocol and limits](https://github.com/midya8/partslab/blob/main/METHOD.md). [Open the live parts inspector](https://midya8.github.io/partslab/).

The v0.2 fixed-basis certificate adds exact binary64 primal/dual arithmetic, outward-rounded objective intervals and portable JSON proofs with an independent Python Fraction verifier. Eighty exact rational active-set optima and all 120 cross-language witness references are checked. The live browser verifies its own candidates, including zero-sweep unfinished solves, and accepts valid pasted proofs while rejecting tampered ones. A residual-shift bound can be loose; even zero gap does not imply unique coefficients. Original fits, scores and selection remain unchanged. [Certificate proof and limits](https://github.com/midya8/partslab/blob/main/CERTIFICATE.md).

V0.3 adds an [exact fixed-face pixel inspector](https://midya8.github.io/partslab/face.html): nominate a face from the numeric NNLS result, re-solve it exactly, and intersect every affine KKT inequality with the pixel domain. All endpoint ties, singular refusals, singleton faces and duplicate-basis nonuniqueness stay explicit. 38 Python and eleven Node/Chrome tests cover 200 independently enumerated tiny face candidates, all 120 stored nominations, 54 complete native/BigInt/Worker witnesses and 10,368 endpoint pixel colors. Ten modules/ten commands with all six fresh fits reproduced. Original data, models and scores remain unchanged. One candidate interval, not a full path, unique support, robustness or joint-NMF optimum. [Math and limits](https://github.com/midya8/partslab/blob/main/FACE.md).

**[ClusterLab](https://github.com/midya8/clusterlab)**

Real-data unsupervised clustering with manual k-means++/Lloyd updates, forty complete restart witnesses and fitting-only PCA/whitening controls. All 3,823 original UCI training digits fit without labels; the 1,797-row official holdout is audited with permutation-invariant scores and all-row silhouettes. The live browser recomputes membership for editable digits, displays mixed-label centroids and exposes all restart descents. Raw uniform initialization slightly beats careful seeding on test ARI despite slightly worse fitting inertia; no general seeding advantage or cross-geometry inertia ranking is claimed. 48 Python tests plus thirteen Node/real-Chrome tests cover independent pair/entropy/distance references, a rational local-minimum counterexample, full refit with test-loader prohibition, frozen-hash evaluation, all 80 public model/example cases and keyboard/copy/download/mobile controls. Ten-module/six-CLI installed wheel. [Open the live clustering inspector](https://midya8.github.io/clusterlab/). CC BY 4.0 data, MIT code; arbitrary groups, not digit predictions or calibrated confidence.

The v0.2 restart inspector exposes all forty saved models, 180 distinct within-arm restart comparisons and forty self-pairs. A manual integer Hungarian solver supplies optimal center permutations and primal/dual witnesses, independently checked against subset-DP optima for all 220 matrices. Browser BigInt checks those exact saved rounded-cost certificates; 800 native/scalar-JavaScript inference pairs and all 400 directed pair controls are tested. Same-data initialization sensitivity is not sampling stability or useful-class discovery; matching centers need not align the actual assignment for an input. Original fits and holdout scores remain unchanged. [Open the live restart inspector](https://midya8.github.io/clusterlab/stability.html). [Restart matching method](https://github.com/midya8/clusterlab/blob/main/STABILITY.md).

The v0.3 ambiguity audit adds 2,200 exact selected-edge exclusion witnesses, best-distinct permutations and optimal-matching counts. Independent full-cost dynamic programs check all 220 gaps and counts; browser BigInt verifies all 4,000 oriented exclusions. The matching is unique in every saved real matrix, while tied and unused-tight-edge controls expose why an optimum alone proves neither uniqueness nor a large margin. A strict sufficient cost-entry perturbation bound is not a sharp radius, pixel robustness or statistical uncertainty. All original fits, scores and earlier matching witnesses remain unchanged. [Uniqueness and gap proof](https://github.com/midya8/clusterlab/blob/main/AMBIGUITY.md).

**[DenoiseLab](https://github.com/midya8/denoiselab)**

DenoiseLab's [two-pixel retrieval map](https://midya8.github.io/denoiselab/plane.html) now shows exact rational closed minimum cells over two observed values, including area, segment-only, point-only and explicitly proved empty regions. Fraction/BigInt witnesses retain all 3,062 original fitting-row coefficients. A source-matched verifier checks supporting halfplanes, maximal lower-dimensional cells and nonnegative infeasibility combinations without rerunning clipping. Shared boundaries use complete all-row exact tie queries, not an interior representative. [Geometry, proof and limits](https://github.com/midya8/denoiselab/blob/main/PLANE.md).

52 Python/fourteen Node/Chrome tests include independent boundary-pair enumeration of 238 small-source cells and 2,110 rational queries, forty complete cross-language maps, 160 browser queries and 30,720 actual canvas colors. Ten-module/nine-command installed reproduction retains full refit/evaluation. [Scalar paths](https://midya8.github.io/denoiselab/path.html), [neural/PCA response](https://midya8.github.io/denoiselab/response.html) and the [original reconstruction audit](https://midya8.github.io/denoiselab/) remain live with stronger winning controls visible. Fixed two-coordinate slice only, not general robustness, causal recourse, uncertainty, better accuracy or binary64 tie equivalence. Licensed UCI data, MIT code; original models and scores unchanged.

**[TreeLab](https://github.com/midya8/treelab)**

Budgeted whole-ensemble counterfactual search with exact weighted-L1 objective bounds, verified common-input witnesses and explicit optimal/infeasible/unfinished states. A best-first queue intersects all 32 trees, propagates forced branches and uses known one-axis witnesses as checked warm starts. The fixed 36-case audit preserves unfinished all-feature searches at 4,096 expansions instead of calling them optimal or infeasible; alcohol-only cases can finish. 101 Python tests plus five Node/real-Chrome tests include independent tiny-forest exhaustive grids, budget-gap checks, member inference and responsive inspector controls. Nine-module/nineteen-CLI wheel reproduction; original models, reports and three figures unchanged. Established constrained model search, not causal recourse, plausible chemistry, scalable optimization or new accuracy. The [ensemble search inspector](https://midya8.github.io/treelab/forest.html), [single-tree explorer](https://midya8.github.io/treelab/counterfactual.html) and [one-axis explorer](https://midya8.github.io/treelab/) remain live.

**[DigitLab](https://github.com/midya8/digitlab)**

A [live model inspector](https://midya8.github.io/digitlab/) now adds baseline-relative class-logit Integrated Gradients for the unchanged UCI digit models. Choose the class and zero or fit-only mean reference, inspect all 64 signed contributions and their logit-sum residual, and keep the attack label separate. An algebraic tanh specialization is checked against independent 128-node quadrature on 40 reference vectors; all 7,188 official model/reference/row cases are finite. 78 Python tests and six Node/real-Chrome tests include 106 attribution reference vectors plus the existing 52 inference/gradient cases. Four reproducible audit figures, ten-module/ten-CLI wheel checks, and mobile/keyboard/touch controls. Established attribution, not a new method, causal importance, explanation quality or a certificate. The stronger same-fit 1NN clean result, exact linear box/radius proofs and original data/models remain visible.

**[ScanLab](https://github.com/midya8/scanlab)**

Exact state-space scans with failure controls, not a speed benchmark.
v0.3 adds coupled full-matrix transitions, noncommuting order witnesses,
transposed reverse adjoints and every matrix/write/initial-state JVP/VJP.
The transpose identity is -440563/15120; a missing-transpose control gives gap
7831/2520. Reversing only matrix-product order changes the final state, while
both mistakes are invisible on diagonal restrictions. Six two-state steps use
108 multiplications/80 additions versus sequential 24/24, despite unit-pair
span 4 versus 6. 63 tests include 96 homogeneous-product shapes, 672 independent
polynomial VJP coordinates, 51 instrumented arithmetic cases and all preserved
diagonal/HVP/gated controls. Three full-witness SVGs, six-command/nine-module
wheel parity and five CI jobs. Serial Python, not a general AD engine,
dense HVP, trained Mamba/S4, new algorithm or GPU-throughput claim.

**[Correlab](https://github.com/midya8/correlab)**

Exact-rational general-sum joint-play obedience, finite-history and private override-signal certificates. Coarse, pairwise, full-swap and conditional gains retain every term and attaining deviation. v0.2 adds explicit hidden-baseline pass/override channels, supplied post-garbling lifts with exact slack identities, and all action partitions through size four. Developed controls give gains 4/3, 5/3, 1 for three two-signal partitions; attributed Roth reveal controls bridge 0 to 11/30. Two reproducible SVGs, seven-module/seven-CLI wheel parity and 50 tests. Supplied finite models only, not an equilibrium solver, learned information design, universal channel-order test, privacy or safety guarantee.

**[GameLab](https://github.com/midya8/gamelab)**

Exact-rational zero-sum game audits with complete optimal faces, minimax witnesses and deterministic perturbation certificates. The interval extension computes fixed-policy worst joint gap using one shared payoff table: its developed control gives gap 1, not the incompatible separate worst-regret sum 2. Signed support witnesses, attainable value extrema and separate robust-security policies stay visible. Strict offline JSON CLI, two reproducible SVGs, six-module wheel parity and 53 tests. Small supplied boxes, not statistical coverage, coupled uncertainty, worst-gap policy optimization, real-agent strength or a scalable/new solver.

**[BetLab](https://github.com/midya8/betlab)**

Exact-rational sequential evidence for bounded paired model scores, with fixed/past-only betting, full null-tree audits and prespecified start allocations with future reserve. The confidence extension inverts a separate conservative fixed-bet mean family, certifies rational crossing/noncrossing brackets and retains earlier bounds after reversal. Its 256-path coverage control excludes the true mean with probability 2187/16384 at alpha 1/4. Three reproducible SVGs, strict offline JSON CLI, seven-module wheel parity and 67 tests. Supplied-law/fixture audits, not drifting-mean estimation, optimized betting, causal effects or model-selection correction.

**[PrivacyLab](https://github.com/midya8/privacylab)**

Exact finite-channel differential privacy with rational hockey-stick events, adaptive transcript laws and clipped-mass certificates. The factor-frontier extension computes every affine piece of the worst-neighbor profile, including a developed switch at 5/4 absent from the likelihood-ratio grid. Exact inverse delta budgets retain minimality witnesses or singular-support obstructions, and distinguish huge finite factors from impossible targets. Three reproducible SVGs, strict offline JSON CLI, seven-module wheel parity and 63 tests. Small supplied-law certificates, not trained-model privacy, secure sampling or a production accountant.

**[SparseLab](https://github.com/midya8/sparselab)**

LASSO optimization audits with primal/dual/KKT witnesses, duplicate-coefficient ambiguity and exact Gap Safe zero certificates. The affine-branch extension solves rational Gram equations and every sign/inactive KKT half-line: its developed control has five exact intervals, a feature leaving at lambda = 1 and re-entering negative at 1/3. Boundary zeros are allowed; singular branches return explicit noncertificates. Strict offline JSON CLI, three reproducible SVGs, seven-module wheel parity and 62 tests. A supplied-branch verifier, not a general LARS solver, complete support recovery, causal feature selector or speedup claim.

**[InfluenceLab](https://github.com/midya8/influencelab)**

Convex logistic influence functions with converged Newton fits and full Hessian/solve witnesses. The deletion-path extension refits continuously along selected weight changes, then checks integrated local derivatives against actual endpoint loss. Deleting all seven developed rows reverses the frozen first-order sign (-0.004253 vs +0.079105); group deletion is not a sum of separate refits. Simpson16 residuals stay visible, including +0.000744 on that all-row path. Strict JSON CLI, two reproducible SVGs, five-module wheel parity and 43 tests. Small numerical reference, not causal attribution, certified quadrature or machine unlearning.

**[FisherLab](https://github.com/midya8/fisherlab)**

Exact-rational natural-policy-gradient geometry, with singular Fisher solves, full RREF/nullspace witnesses and positive pairwise PSD certificates. Four full-tangent charts agree exactly; diagonal/identity-damped approximations and nonlinear finite steps expose the limits. The shared-context extension has positive aggregate reward derivative 1/64 but context 1 derivative -1/8, with exact projection 7/16=1/64+27/64. Independent context parameters reach both targets; uniform reweighting changes the objective, and naive joint logits can move supposedly fixed context mass. Strict offline JSON CLI, two reproducible SVGs and 45 tests. Local supplied-model audits, not an MDP trainer or optimizer-superiority benchmark.

**[LatentLab](https://github.com/midya8/latentlab)**

A Gaussian VAE from scalar Python, with all 150 pathwise gradients checked independently. The importance extension separates random log-evidence estimates, expected IWAE bounds and same-sample Jensen comparisons. An exact linear-Gaussian posterior recovers its known evidence; a full-support rare-atom control has ESS 64 yet underestimates evidence by factor 999,000 on an event with probability 93.80%. Neural noise prefixes are visibly nonmonotone. The original trained fixture still shows lower no-KL reconstruction error but worse prior samples; even beta 1 leaves 51.56% outside the mode neighborhoods. 43 tests cover independent derivatives/quadrature, exact rational rare-event expectations, extreme log weights, strict checkpoints and two reproducible SVGs. Five-module wheel reproduces both demos outside checkout. Evidence auditing, not IWAE training, an ESS accuracy certificate, exact nonlinear likelihood, image generation or distribution recovery.

**[ErgodLab](https://github.com/midya8/ergodlab)**

Exact rational stationary policy sensitivity, Poisson bias and Markov reward audits. Independent directed spanning-tree derivatives match normalized stationary linear systems. The discounted extension separates the true fixed-start objective gradient from a stationary proxy: at beta 1/2 the proxy has exact curl -1/147, ruling out a local scalar potential, and differs from the true gradient [5/98,-1/98]. At beta 1 it uses the centered Poisson limit, not a singular inverse. Original fixtures retain the occupancy-only gradient 1/18 and sticky/alternating reward variances 7/4 versus 0 despite identical one-step variance 1/4. 39 tests cover independent paths, determinants, finite differences, analytic proxy/curl grids and two reproducible SVGs. Six-module wheel verified outside checkout. Supplied finite irreducible models, not GPOMDP, training, gradient-estimator variance, a CLT or a monotone-bias guarantee.

**[ScoreLab](https://github.com/midya8/scorelab)**

Exact policy-gradient distributions, complete trajectory witnesses and rational covariance certificates. Matrix-valued time/state score controls solve singular normal equations and minimize the full covariance within a fixed linear-control class. A three-action example has exact gradient [-1/9,1/3]: the best scalar baseline leaves trace variance 53/612, while a full matrix gives zero on every action. A separate 64-path sequential model has only a small change, 1.462519 to 1.460918, with singular score ranks [1,0,1,1,1,1]. Original scalar audits retain the value-baseline counterexample, increasing variance 4/625 to 36/625. 36 tests include 256 analytic Bernoulli policies, independent derivatives and Cartesian covariance references, matrix-control checks across 15 additional settings, all principal minors of gap certificates, nonunique coefficients with unique supported corrections, coordinate-transform congruence and two reproducible SVGs. Six-module wheel verified outside the checkout. Exact supplied finite models, not training results, a fitted critic or universal zero variance.

**[BanditLab](https://github.com/midya8/banditlab)**

Exact finite-budget Beta-Bernoulli planning with complete posterior-state graphs, action values/ties, a fully updating greedy control and exact clairvoyant prior bound. A prescribed three-pull example chooses the lower-mean arm first: optimal expected reward 187/108 versus greedy 46/27, gain 1/36. At two pulls both first arms tie and gain is zero. New forward audits support named or exact randomized state policies, conserve probability at every pull and expose all reward/occupancy flows. Summed occupancy-weighted optimal Bellman gaps equal policy loss: greedy loses 1/36 at its first decision; fixed loses 7/108 across three decisions. Optimal/greedy visit 14 of 35 possible states, fixed visits 10. 34 tests include 2,048 two-arm and 1,728 three-arm policy-tree references, 144 independent named-policy history audits, randomized joint-history checks, independent Bernstein/Beta integrals and two reproducible SVGs. Six-module wheel verified outside the source tree. Exact supplied-prior expectations, not empirical trials, causal attribution or frequentist guarantees.

**[BeliefLab](https://github.com/midya8/belieflab)**

Exact rational finite-horizon POMDP planning for two hidden states, with policy-tree witnesses and all-belief envelopes. An optimized open-loop baseline checks every fixed action sequence over the same model and horizon: the supplied sensing fixture gives contingent value 7/10 versus zero at the uniform belief, with exact feedback-gap area 49/400. A forward execution audit traces every history/state mass, conditional belief and discounted reward contribution, including impossible branches without fabricated posteriors. Fixed-tree regret certificates expose every zero-regret interval: a probe tree optimal at the uniform prior loses 13/10 at either certain-state prior. Discounted all-belief Bellman-residual brackets connect finite envelopes to infinite optimal value without pretending the finite tree runs forever: raw residual 1/100 can hide value error 1. A perfect-probe fixture brackets infinite value 9/10 by [113/150,9/10]. 86 tests cover exact residual cells, independent infinite-value references and 81 model settings, complete depth-two trees, fixed sequences, exact crossing cells, full joint path occupancies and independent belief recursion. Strict JSON CLI, preflight caps, four reproducible SVGs and an isolated ten-module wheel. Supplied-model calculations only, not learned information value, empirical calibration, causal sensor performance or real-world safety.

**[BellmanLab](https://github.com/midya8/bellmanlab)**

Exact rational discounted planning with residual certificates, rectangular robust control and nested controller/adversary policy iteration. A residual of 1/100 hides value error 1; a nominal winner loses 6/5 under supplied ambiguity; global uncertainty (-2/3) differs from row-wise closure (-2). Exact inner nature solves expose every policy, scenario Q-value and tie. Controller improvement waits for inner stability: independent cap examples distinguish an upper bound, an exact nonoptimal policy value and a jointly stable optimum. 70 tests audit independent 972 nominal and 3,888 controller/adversary policy references, every nested witness, monotonicity, both cap paths and three SVGs. Strict rational JSON, full histories and an isolated eight-module wheel. Supplied models only, not learned confidence, online RL, unique-policy, policy-loss or real-world safety guarantees.

**[VariLab](https://github.com/midya8/varilab)**

Mean-field inference and exact graph inference from scratch, with inspectable certificates rather than optimizer success claims. A supplied two-mode Ising target improves ELBO from 1.386294 to 3.005027 while maximum mean error worsens from 0 to 0.994902. Exact-rational Hessian congruence and signed witnesses distinguish saddles, singular boundaries and adjacent binary-float inputs without a tolerance. Evidence-aware forest sum-product and rational MAP add full message traces, exact tie counts and compatible joint decisions. Bounded cyclic elimination adds symbolic resource preflight, conditional query tables and rational MAP traceback: a 63-spin odd ring has exact score 61 and 126 optima; independent locally optimal spins can still form a wrong joint answer. A refused star order is contrasted with an accepted order on the same graph. 183 tests and six reproducible SVGs cover independent exhaustive oracles, full intermediate factors, score/count certificates and both passing and failing gates. Dependency-free Python, strict JSON CLI and an isolated-wheel demo. Supplied models only; float sum-product is separate from binary-rational scores. No learned posterior, calibrated uncertainty, causal, optimal-treewidth or runtime claim.

**[RobustLab](https://github.com/midya8/robustlab)**

Binary linear adversarial robustness from scratch: exact L1/L2/L-infinity norm-ball margins and attainable perturbation witnesses, with hand-derived robust logistic subgradients. A fixed shifted synthetic holdout exposes the clean/robust trade-off: ordinary training is 100% clean / 20% strict robust at L-infinity radius 0.30; robust training is 80% / 80%. Both robust-gate directions stay visible. Independent rational corner enumeration, finite differences and nonsmooth subgradient inequalities. Exact rational L1/L-infinity audits expose float boundary-flag disagreements while preserving the actual binary input values. Box-constrained L1/L-infinity audits return equal exact primal/dual bounds and expose a false robustness claim from clipping an L1 attack. 80 tests and three reproducible SVGs. Dependency-free Python and strict JSON CLI. Supplied linear models and explicit norm balls or box intersections only; mathematical audits, not neural-network or production security guarantees.

**[CausalLab](https://github.com/midya8/causallab)**

Exact finite structural causal models with distinct observation, intervention and shared-noise counterfactual queries. A 100-world confounding fixture reverses a +.26 association into a -.10 supplied-model intervention difference; observationally identical mechanisms still disagree on intervention and counterfactual answers. Log-space rare evidence, bounded noise-world traces and all 64 tiny Boolean mechanism pairs. Named multi-world counterfactual joints expose shared-noise response dependence missed by identical action marginals. Stable/flip mechanisms share all observations and single-action marginals but have different response-type joints. The naive-product failure stays visible. Sharp binary response bounds now return exact rational attaining joint witnesses from point action marginals, with optional explicit monotonicity and undefined zero-support conditional rates. Graphical d-separation adds ancestor/moral-edge certificates, collider-descendant checks and explicit incoming-edge surgery. A bounded backdoor-set search exposes collider bias, forbidden descendants and explicit candidate availability. 138 tests and five reproducible SVGs keep the missing coupling assumptions visible. Dependency-free Python and strict JSON CLI. Mechanisms are supplied assumptions, not causes learned from observational data.

**[ParticleLab](https://github.com/midya8/particlelab)**

Bootstrap particle filtering from scratch with complete log-weight, resampling and ancestry histories. A static-support failure ends with full weight ESS but zero particle variance while the exact posterior remains uncertain. Kalman/static-square references, terminal-weighted genealogies and bounded backward-simulation smoothing with a linear RTS reference, a no-resampling comparison, all sixteen development seeds and 114 tests keep the approximation inspectable. Early path collapse stays visible even when current states are distinct; backward draws add path diversity without claiming exact uncertainty. An optional linear observation-conditioned proposal includes all-seed predictive-weight comparisons, including worse variance RMSE on the inherited example. Dependency-free Python, strict JSON CLI and reproducible SVG. Finite scalar models, not convergence or calibrated real-data claims.

**[SegmentLab](https://github.com/midya8/segmentlab)**

Exact offline Gaussian changepoint inference that exposes confident outlier cuts, impossible joint events and the gap between MAP and minimum expected boundary loss. Normalized constrained priors, full partition marginals, direct joint draws, same-design replicate mixtures and entropy/KL audits remain inspectable. 104 tests, exhaustive tiny references, dependency-free Python, strict JSON CLI and two reproducible SVGs. Supplied model assumptions, not online event detection or real-data calibration.

**[HamiltonLab](https://github.com/midya8/hamiltonlab)**

Hamiltonian Monte Carlo from scratch with full rejection histories, leapfrog energy/reversibility and quadratic resonance audits. High acceptance can hide zero mode switches or almost-identity trajectories; optional state-independent random lengths retain every choice and work count. Rank-normalized split/folded R-hat exposes deterministic scale and half-chain failures missed by classical ratios; undefined components remain null. 82 tests, dependency-free Python, offline sample/demo/quadratic/diagnose/harmonic/window/window-mixture CLI and SVG. No speed ranking, adaptive NUTS, ESS/MCSE or convergence certificate. Synthetic chains and analytic truths, not fitted posterior results. Analytic Gaussian flow separates mass/phase effects from integration error, with exact sign-flip and identity counterexamples. Fixed and IID random-duration q/q² covariance audits and a reproducible shared-axis SVG expose frozen magnitude even with zero position correlation; no sampled-chain ESS/MCSE claim.

**[TransportLab](https://github.com/midya8/transportlab)**

Log-domain entropic optimal transport with full mass plans, explicit nonconvergence and weighted interpolation atoms. Full pushforward preserves actual endpoint marginals; barycentric means do not. Separate rounded primal/dual audits retain raw failed solves and report signed numerical gaps, marginal residuals and L1 changes. Analytic fixed-iteration plan tangents expose a nonconverged envelope-shortcut error0.007670872, checked against central differences. Zero support, covariance decomposition and exact tiny assignment remain visible. 46 tests, offline solve/assignment/push/audit/sensitivity CLI and SVGs. Not a metric, sampled trajectory, implicit-optimum gradient or certified OT bound.

**[FlowLab](https://github.com/midya8/flowlab)**

Affine-coupling flow from scratch: exact fitted-model density, inverse sampling, analytic input scores and bounded conditional CDF/quantile slices. Aligned window audits reuse one scored grid and expose renormalization effects: narrowing[-4,4] to[-1,1] removes24.35%-31.94% of interpolated mass inside the finite outer window. An analytic narrow-peak counterexample shows two agreeing grids can both be wrong. 45 tests, strict artifacts, offline CLI/SVGs and actual call budgets. No whole-line tail, exact-conditional, calibrated-coverage, OOD or causal claim.

**[GraphLab](https://github.com/midya8/graphlab)**

Two-layer GCN from scratch with exact input-margin gradients and budgeted single-edge deletion sensitivity. Input locality differs from graph normalization: node 3 has zero feature gradient for node 0, yet deleting edge 2-3 changes its margin by +0.016852 after degree renormalization. Full signed contributions, every edge effect, preflight call budgets and zero-gradient/large-change counterexample. Original transductive development results remain: selected GCN0.96875, MLP0.34375, scrambled GCN0.515625; final/centroid controls visible. Synthetic graph carries class signal; no causal, probability-attribution, unseen-graph or general ranking claim. 42 tests, strict artifacts and offline CLI/SVGs.

**[DiffuseLab](https://github.com/midya8/diffuselab)**

Learned 2-D diffusion from scratch, now with selected-grid DDIM sampling and exact denoiser-call audits. The same 482-parameter model uses 8/16/64 DDIM steps without retraining. Eight steps saves 87.5% of predictor calls but has worse symmetric reference distance here (0.210661 vs DDPM 0.037103), despite a slightly higher near-center fraction. All 8 neighborhoods reached, uneven frequencies and outliers retained. Full-grid eta=1 matches DDPM arithmetic with matched draws. 33 tests, strict artifacts and offline train/sample/DDIM CLI. Development fixture only, no walltime speedup, image-generation or general ranking claim.

**[ChainLab](https://github.com/midya8/chainlab)**

Hidden Markov models from scratch: log-space inference, Viterbi paths and multi-sequence Baum-Welch, now with prefix-only filtering and multi-step symbol/state forecasts. An exact example separates x-only filtering P(A)=2/3 from future-informed x/y smoothing P(A)=0. Forecasts are dependent horizon marginals, not a joint path. Prefix predictive log scores match full likelihood to about 5.68e-14 on the seed23 development fixture; that is an implementation audit, not a new quality gain. Existing test NLL per symbol: trained0.775631, iid control0.985993, initialization1.017638, generating reference0.771674. Exhaustive references, impossible-prefix rejection, 41 Python tests, four Node/actual-Chrome tests and offline CLI/SVG demo. No calibration or state-recovery claim.

Live v0.2 [prefix-evidence inspector](https://midya8.github.io/chainlab/) keeps all three original models and both exact counterexamples fixed. Edit a bounded observation window and compare each own-prefix filtered row, full-window smoothed row, supported Viterbi path and prefix-only future marginals. Original 40-symbol reports and scores remain unchanged; the first three displays show only the first 12 symbols. Independent scaled browser versus native log inference checks cover 114 symbol edits and 40 prefix boundaries, plus 62 exhaustive high-precision controls. Underflowed browser mass refuses instead of inventing a posterior. 41 Python tests, four Node/actual-Chrome tests and installed eight-module/nine-command reproduction. No new training, state accuracy, calibration or causal claim. [Conditioning and numerical limits](https://github.com/midya8/chainlab/blob/main/EVIDENCE.md).

**[KernelLab](https://github.com/midya8/kernellab)**

Gaussian-process regression and finite-grid expected-improvement suggestions from scratch. Cholesky solves, separate latent/observation covariance, explicit jitter, marginal likelihood and fixed-parameter LOO. Deterministic EI excludes known rows and returns a full candidate audit, without executing evaluations. A nine-evaluation toy optimization comparison reports grid regret 0.000163 (EI), 0.072944 (space filling) and 0.399473 (one seeded random control). Same pool/initialization/budget; development data, no general ranking or continuous optimum claim. The regression misspecification counterexample remains visible. Dependency-free Python, 43 Python tests, four Node/Chrome tests, offline CLI and reproducible SVGs.

Live v0.2 [target-response inspector](https://midya8.github.io/kernellab/) keeps both original GP models fixed. Edit one observed target and inspect all 15 signed response weights: the conditional mean moves, while latent/observation variances stay unchanged. Independent browser LDL versus native Cholesky checks cover 202 query witnesses and 3,030 direct edited-target predictions, plus high-precision tiny controls and shared-axis endpoint checks. Original misspecification results and optimization traces are unchanged. Signed weights are not causal attribution or calibrated confidence; refitting invalidates the fixed-kernel contrast. 43 Python tests, four Node/actual-Chrome tests and installed eight-module/seven-command reproduction. [Derivation and numerical limits](https://github.com/midya8/kernellab/blob/main/RESPONSE.md).

**[BoostLab](https://github.com/midya8/boostlab)**

Binary gradient boosting from scratch: mean-residual defaults plus optional capped, L2-regularized Newton leaves on residual-SSE trees. The development fixture selects 35 Newton trees/237 nodes, test accuracy 0.9004/logloss 0.3341; its unselected 80-round checkpoint is also shown (0.8984/0.3469). Mean depth-2 control: 0.8906/0.3400; full-budget stumps: 0.6367/0.7366. Different capacity and settings, no causal or external-benchmark claim. Backward-compatible v1/v2 inference, Hessian/leaf arithmetic tests, validation-only prefix selection. Dependency-free Python, 36 Python tests and five Node/Chrome tests and offline CI.

Live v0.2 inspector retains all 80 fitted trees and 81 prefixes for each original arm, including the selected zero-tree stump. Editable inputs expose complete additive-logit/tree-route witnesses, original selected-versus-last checkpoints and shared zero-based loss curves. No new tuning, attribution, calibration or performance claim. All original development-fixture metrics and limits above are unchanged. Independent native/browser checks cover 4,860 original and 1,458 edited prefix states, 78 complete paths and all 243 metric states. 36 Python tests, five Node/actual-Chrome tests, installed seven-module/five-command reproduction. [Try the training path](https://midya8.github.io/boostlab/) · [Derivation and numerical limits](https://github.com/midya8/boostlab/blob/main/PATH.md).


**[ShapleyLab](https://github.com/midya8/shapleylab)**

Exact small-feature Shapley attribution from scratch: all empirical-background coalitions auditable, callback API and JSON CLI. Same product prediction 6 gives [3, 3, 0] or [2, 3, 0] with different backgrounds. An off-manifold hybrid counterexample passes additivity, showing why exact arithmetic is not explanation validity. Joint missing-feature dependence preserved; preflight exponential-work budget; independent factorial reference checks. No conditional/causal or trained-model quality claim. Optional atomic groups move correlated blocks together. Three-way product gives grouped [1/2, 1/2], not post-hoc [2/3, 1/3]; grouped games answer a different question. Up to 64 raw features/12 groups, no within-group credit split or cross-group dependence guarantee. Optional seeded permutation mode handles up to 64 individual features with cached coalitions and descriptive MC standard errors. A two-permutation product gives [0.5, 0.5, 0] despite exact [1/3, 1/3, 1/3], showing zero observed MC error is not an accuracy bound. No confidence guarantee or sampled groups. Dependency-free Python, 43 tests and offline CI. v0.2 adds an independent [live coalition ledger](https://midya8.github.io/shapleylab/): actual native callback rows, all weighted predecessor terms and cached full ordering paths. 49 Python + four Node/actual-Chrome tests, 95 edits, 128 Fraction and 64 BigInt controls; installed reproduction retains all original modes. Original data, scores and adverse examples unchanged. No stronger explanation-quality claim.

**[PolicyLens](https://github.com/midya8/policylens)**

Offline contextual-bandit evaluation from scratch: IPS, SNIPS, direct and doubly robust estimates with support/weight diagnostics. On a constructed balanced design, IPS/SNIPS/DR recover target 0.78 despite a wrong reward model; clipping raises ESS but moves DR to 0.535. A separate noisy log with oracle reward predictions gives DR 0.7532, not exact truth. No causal-identification, confidence-bound or deployment-safety claim; explicit propensity, support and nuisance-prediction assumptions. Optional held-out categorical reward fitting reports fold/cell counts and prior-only predictions; row-iid splitting does not fix grouped or sequential leakage. On the same noisy log, fitted DR 0.7509088 is not better than oracle DR. Dependency-free Python, 28 tests and offline CI. v0.2 adds an independent [live row ledger](https://midya8.github.io/policylens/): all signed contributions and cap removals, five support/zero-mass/rare-action controls, bounded target/reward edits and fixed-prediction deletion reports. 36 Python + four Node/actual-Chrome tests, 95 edits, 160 Fraction and 80 integer-grid controls; original four reports unchanged. ESS, cap curves and deletion reports are descriptive, not confidence bounds or cap recommendations.

**[DriftLens](https://github.com/midya8/driftlens)**

Embedding-distribution comparison from scratch: unbiased RBF MMD, cached-kernel permutations, exact tiny-sample tests and complement-sum scoring for imbalanced groups and a JSON CLI/API with Holm-corrected prespecified bandwidth families and optional within-block permutations, plus descriptive row-index witness diagnostics (not causal attribution). Selected 30x4 development fixture: same-generator p=0.550, mean-shift p=0.002 (the 1/500 resolution floor); a tiny separated 2-vs-2 sample still has exact p=1/3. No power-benchmark, cause, downstream-accuracy or continuous-monitoring claim. Explicit exchangeability and prespecified bandwidth assumptions; non-rejection is not equivalence. Dependency-free Python, 45 tests and offline CI.

**[SetGuard](https://github.com/midya8/setguard)**

Split-conformal classification sets from scratch: JSON fit/predict artifacts, finite-sample rank correction, exact tied-score audits and per-class/size diagnostics, plus optional label-conditional classwise thresholds with explicit rare-class inclusion. On the five-class development fixture, target 0.9 gives empirical coverage 0.9235 at mean set size 3.017 versus argmax accuracy 0.4960; a deliberately adversarial label shift drops coverage to 0.0760. The standard marginal-coverage theorem needs exchangeability and a predictor fixed independently of calibration, not every realized class rate/input or shifted-data guarantees. Classwise mode targets coverage within true labels under its stated exchangeability assumptions, at a set-size cost. Dependency-free Python, 41 Python tests plus four Node/Chrome tests and offline CI.

[Live rank ledger](https://midya8.github.io/setguard/) adds five fixed synthetic controls, every boundary tie and pooled/classwise label inclusion, 19 alpha samples, full JSON and held-position rank checks. Independent native/browser arithmetic matches 95 witnesses; installed wheel reproduces the original reports. Original controls remain attached. No fixed-split, causal, uncertainty or deployment guarantee.


**[CalibrLab](https://github.com/midya8/calibrlab)**

Confidence calibration from scratch in pure Python, with a JSON CLI/API for your own validation/test logits and unclipped logit-space NLL, plus optional conditional paired test-row bootstrap intervals: an overfit small-data MLP (train 1.0000, test 0.5563) is measured badly overconfident on the checked-in fixture (ECE 0.2765; top bin 0.9735 confidence at 0.6602 accuracy), then one temperature fit on validation NLL only cuts ECE to 0.0651 and test NLL from 2.0030 to 1.2060 at exactly zero accuracy change - the invariance asserted bit-for-bit, the oracle-T gap reported (0.0076), and gradients hand-derived and finite-difference verified. (56 Python tests plus four Node/Chrome tests)

[Live score ledger](https://midya8.github.io/calibrlab/) exposes five synthetic controls, every row logit NLL/class Brier term, confidence-bin gap, migration count and fixed-temperature deletion, with19sampled temperatures and full JSON. Independent native/browser arithmetic matches95witnesses; installed wheel rebuilds original training/logits/report. Original evidence unchanged. No calibration-only, causal, uncertainty or deployment claim; full-precision oracle gap rounds to.0075 versus.0076 from rounded NLL subtraction.

**[DistillLab](https://github.com/midya8/distilllab)**

Knowledge distillation from scratch in pure Python: a 10x smaller student gains +0.0656 test accuracy over direct training on the checked-in fixture (0.7469 vs 0.6813; teacher 0.8344), measured against matched control arms - pseudo-labels on the teacher's argmax exceed direct by +0.0281 and soft-label distillation exceeds pseudo by +0.0375, with uniform smoothing adding nothing and a permuted-target arm at chance; these between-arm differences are fixture measurements, not causal attribution. Gradients hand-derived and finite-difference verified, overfit gap measured (0.3187 direct vs 0.0531 distilled). (24 Python tests plus four Node/Chrome tests)

[Live student-gradient inspector](https://midya8.github.io/distilllab/) exposes every parameter update, hard/soft class derivative, CE/entropy/KL term and all 400 original split predictions. Six original trained students and their initialization stay attached, alongside a small finite-step overshoot control. Independent native/browser witnesses and installed training/wheel reproduction preserve the original experiment. One local update does not identify a causal mechanism, calibration or deployment benefit; stable unclipped inspector losses and the original probability floor are distinguished explicitly.

**[MoeLab](https://github.com/midya8/moelab)**

Sparse mixture from scratch with an [interactive exact-route inspector](https://midya8.github.io/moelab/): Python Fraction and independent browser BigInt cells, point ties, one-sided jumps and fixed-branch derivatives. Rounded inference and exact affine geometry stay distinct; three balance statistics are not interchangeable. Original aux/no-aux/initialization, dense baseline and all 340 rows retained: aux MSE 0.0303 vs dense 0.1853, soft 0.6291, no-aux 0.0015, purity 1.0000 on the synthetic fixture. 39 Python + five Node/Chrome tests, 32 full witnesses and installed-wheel reproduction. No causal, generalization, robustness or serving-speed claim.

**[AlignLab](https://github.com/midya8/alignlab)**

[Finite-policy optimum and KL-budget inspector](https://midya8.github.io/alignlab/): independent Python/browser Gibbs audits over all 1,005 recorded states separate optimizer error from synthetic utility. The original noise-control policy is essentially reward-optimal yet loses utility; stale prose is corrected without changing original training, data, tests or gates. Reference-weighted ties, zero support, underflow and unresolved budgets stay explicit. 47 Python + four substantive Node/Chrome tests, 35 full witnesses, high-precision controls and installed-wheel reproduction. Finite synthetic diagnostics, not causal, safety or generalization guarantees.


**[LoRALab](https://github.com/midya8/loralab)**

Same model, different factor-SGD step: independent Python/browser evaluators expose full factor-coordinate gradients, finite-step identities, matrix gauges and scalar compensation without claiming a new optimizer. All 124 original epoch boundaries, 31-scale sweeps and full exports remain visible. Width 2 reaches shifted accuracy 1.0000 with 67.7% of full fine-tuning's parameters, but retains less original accuracy (0.7556 versus 0.9556). 31 Python tests plus four Node/Chrome tests audit 54 full reports and 591,615 numbers; an isolated wheel reproduces the unchanged experiment. Synthetic finite classifier only, no LLM or causal claim. [Live inspector](https://midya8.github.io/loralab/).

**[SpecLab](https://github.com/midya8/speclab)**

Speculative decoding from scratch: greedy verification, exact stochastic residual correction and a prefix-conditioned oracle lookahead planner with no-draft action 0. Complete Bellman action/transition/slack certificates and full sequence/count laws keep probability correctness separate from assigned cost. Switching fixture: `23/10` hypothetical units versus best fixed `47/20`; score-work prices choose no speculation. 47 tests include exhaustive tiny-policy enumeration and independent joint-law checks, with all previous stochastic controls preserved. Five-job CI checks seven modes from an installed 12-module wheel. Full-known-table oracle only: planning overhead is unpriced, no real-LLM benchmark, measured latency or new-algorithm claim.

**[StructGate](https://github.com/midya8/structgate)** · [Live inspector](https://midya8.github.io/structgate/)

Full-model constrained decoding with support-aware KL and exact finite-language conditioning. The independent browser evaluates every original n-gram count, all 120 historical paths/3,729 emitted characters and all 46 character probabilities at every step. Fifty-four Python tests retain all 32 originals; three Node/actual-Chrome tests compare 1,251 full prefix reports, 289 source contexts and 741,236 numeric entries. Fraction/BigInt controls expose local-versus-global distortion, stranded probability and undefined zero events. Original 3/40, 40/40, 40/40 fixture and gates retained. Prefix legality is not finite-budget completion; the historical fixed record is not JSON Schema. No LLM-quality, causal mask-cost or arbitrary-JSON conditioning claim. [Equations and limits](https://github.com/midya8/structgate/blob/main/CONDITIONING.md).

**[QuantLab](https://github.com/midya8/quantlab)** · [Live inspector](https://midya8.github.io/quantlab/)

Real QLB1 int8 files, IEEE32/64 scales and an independent editable browser inspector: every coefficient, signed logit-error contribution and exact fixed-input margin. Original 60-example fixture and magnitude controls preserved; 39 Python tests and four Node/actual-Chrome tests compare 52 full reports. Actual row files are 232/244 B, not the original 204 B analytic payload. No integer-kernel or speed claim.


**[RAGLine](https://github.com/midya8/ragline)**

Retrieval-augmented answering from scratch in pure Python: deterministic corpus,
token-hashed sparse embeddings, top-k retrieval, extractive answers that cite
their source chunk, and a lexical-overlap grounding check shown to flag a
corrupted citation in a tested negative control. Fixture evaluation pinned in CI (recall@3 1.00, MRR 0.94, grounded
1.00). Dependency-free Python, 31 unit tests, a fully offline demo, and CI
across Python 3.10-3.13.

**[KVLens](https://github.com/midya8/kvlens)**

Independent full-tensor attention/cache inspector with final-query-only no-cache and optimized-prefill controls, atomic occupied-prefill rejection and independent cache forks. Named default eight-prediction savings: 58.68% against the stronger baseline versus 73.08% for the intact historical pair. Complete Q/K/V, score/value/output/logit contributions, before/after state and full JSON/model exports. 55 Python tests retain all 28 originals; three Node/actual-Chrome tests compare 32 complete reports, 97 predictions and 66,940 numeric entries, with every displayed cell and weight table checked. Counted arithmetic and ideal packed K/V payload, not latency or actual memory.

[Live inspector](https://midya8.github.io/kvlens/) · [Case study](https://github.com/midya8/Midya-portfolio/blob/main/projects/kvlens.md)

**[AttnLens](https://github.com/midya8/attnlens)**

A real manually differentiated attention trainer with a fixed-weight intervention workbench. Independent JavaScript recomputes all downstream tensors after head-output ablations, exposes all 16 head subsets on the original 128-example held-out split, and tests matched key/filler changes. Complete trained and same-seed initialization checkpoints, all source weights and full audit exports. Repairs a clipped-loss/nonzero-gradient mismatch with stable log-sum-exp. 59 Python tests retain all 46 originals; three Node/actual-Chrome tests compare 352 full tensor reports and 22 audits, with 704 displayed head-row views. One seed and synthetic task, zero-ablation distribution shift and nonadditivity visible; no attention-as-explanation or discovered-circuit claim.

[Live workbench](https://midya8.github.io/attnlens/) · [Case study](https://github.com/midya8/Midya-portfolio/blob/main/projects/attnlens.md)

**[EmbedKit](https://github.com/midya8/embedkit)**

Independent editable SGNS objective and gradient inspector: every sampled event, 1,593 coordinate finite differences, real sequential replay versus a frozen simultaneous step, and visible clamp/order effects. Twelve original pairs capture 72 actual calls; seven labeled controls expose repetition, conflicting labels, saturation and overshoot. Full 300-sentence corpus and all 32 trained vectors retained; browser recomputes all 992 cosine neighbors. 53 Python tests and four Node/actual-Chrome tests compare 19 complete reports. Original 40 tests, trainer and gates remain unchanged.

[Live inspector](https://midya8.github.io/embedkit/) · [Math & replay contract](https://github.com/midya8/embedkit/blob/main/STEP.md)

**[PlanBench](https://github.com/midya8/planbench)**

Validation and deterministic simulation of agent task plans before they run:
semantic DAG checks (unknown tools, cyclic dependencies, unproduced inputs),
a seeded parallel simulator with flaky tools, retries and skip cascades, and
makespan/cost/critical-path/parallelism metrics with CI gates. Dependency-free
Python, 29 unit tests, a fully offline demo, and CI across Python 3.10-3.13.

**[DecodeLab](https://github.com/midya8/decodelab)**

Stable staged sampling, complete finite continuation trees and full beam-pruning witnesses. Normalized temperature/top-k/top-p, EOS versus cap mass, and exhaustive same-objective oracles expose both lost better futures and a width 2-worse-than-width 1/3 counterexample. Editable independent scalar-JavaScript inspector with every outcome and JSON export. 54 Python tests (36 original unchanged), 90-digit Decimal/rational references, 32 retained audits, 120 staged cases, 7,927 independent numerical checks, actual Chrome and installed-wheel reproduction. Original n-gram CLI/corpus/demo preserved. Synthetic arithmetic/search audits, not text-quality evidence or a new decoding algorithm.

[Live inspector](https://midya8.github.io/decodelab/)


**[VectorLite](https://github.com/midya8/vectorlite)**

Finite random-hyperplane geometry and retrieval inspector with every projection,
signature, admitted/missed exact neighbor and threshold. Stable cosine arithmetic,
full-precision gates and explicit self/excluded/external query protocols preserve
the original corpus and 1.0 self-inclusive recall@3. A same-two-vector exclusion
control changes recall from 1 to 0. Independent JS replays actual planes;
50 Python tests retain all 31 originals, with Decimal/rational references,
35 audits, 20,784 numerical checks and 5,856 actual-Chrome projection rows.
Linear signature scan, not a sublinear index; marginal iid-plane expectations
are not fixed-plane guarantees. No speed, embedding-quality, confidence-interval
or new-algorithm claim.

[Live inspector](https://midya8.github.io/vectorlite/)

**[GroundCheck](https://github.com/midya8/groundcheck)**

Complete lexical/citation/numeric provenance with independent scalar-JavaScript recomputation, editable source policies and full input offsets. 66 Python tests retain 43 originals; 50 synthetic controls expose semantic false positives. Four Node/Chrome checks and isolated-wheel reproduction. Lexical support is not entailment; audit parity is bounded ASCII.
[Live provenance inspector](https://midya8.github.io/groundcheck/)

**[TokenForge](https://github.com/midya8/tokenforge)**

Byte-level BPE tokenizers trained from scratch: deterministic merge training
with exact pair counts over GPT-2-style pre-tokenization boundaries,
rank-ordered encoding with exact round trips, JSON vocab persistence, and
compression statistics with JSON/Markdown reports and a CI quality gate.
Dependency-free Python, 40 unit tests, a fully offline demo, and CI across
Python 3.10-3.13.

**[RetrievalBench](https://github.com/midya8/retrievalbench)**

Complete BM25 arithmetic, explicit chunk parents, both parent budgets and per-rank metric gains with independent browser recomputation. 68 Python tests retain all 42 originals; 35 full reports, three Node/Chrome tests and installed-wheel reproduction. Synthetic arithmetic controls, not search-quality evidence. Complete rankings, discarded duplicates and ideal metric denominators stay visible. Default CLI budget/results preserved; no Lucene equivalence or broad quality claim. [Open inspector](https://midya8.github.io/retrievalbench/).

**[EvalForge](https://github.com/midya8/evalforge)**

[Editable paired inspector](https://midya8.github.io/evalforge/): all-task versus
matched-task means, complete gate/raw-record witnesses, exhaustive paired sign
flips and exact McNemar counts, independently recomputed in JavaScript. Original
offline command-adapter/scorer/HTML/JUnit/Markdown/SARIF harness and all 68 tests
retained. 92 Python tests, 24 full independent reports, actual Chrome and isolated
installed-wheel checks. Supplied evidence, not a model-quality verdict; equal ids
do not prove matching tasks or independent samples. Inference never changes the gate.

**[AgentTrace](https://github.com/midya8/agenttrace)**

Local-first validation, analysis and reporting for AI agent execution
traces: JSONL structure checks, run summaries, tool/LLM call counts, latency
and cost rollups, graph depth, repeated-step loop detection, baseline/candidate
regression comparison, CI-friendly quality gates, a standalone escaped HTML
timeline, deterministic JUnit XML output for CI test viewers, Markdown
job summaries, and SARIF 2.1.0 output for code-scanning integrations.
Dependency-free Python, 57 unit tests (original 33 retained), a fully offline
fixed-trace baseline/candidate demo that validates JUnit, Markdown and SARIF
output, and CI across Python 3.10-3.13.

Full-record graph/timing inspector: every endpoint, interval segment, parent path/relation, normalized record and p95 term. Independent Python/JavaScript recomputation and current JSON export. 57 Python tests retain all original 33 tests; 24 synthetic controls, 11,110 interval checks and an isolated installed-wheel reproduction. Parent links are not causal dependencies; recorded coverage/overlap is not CPU, idle, waste or utilization. No model/API call.

[Live graph/timing inspector](https://midya8.github.io/agenttrace/)

**[PromptGuard](https://github.com/midya8/promptguard)**

Local-first prompt linting with a full-stage baseline and CI-gate witness. Native fixes redact before truncation, retain all recognized sensitive matches per line and fail incomplete scans. An [independent policy inspector](https://midya8.github.io/promptguard/) recomputes every abstract finding through filter, suppression and gate stages with complete JSON export.

- 87 Python tests on 3.10-3.13 preserve all original 68 tests, fixtures and offline demo; 13,320 exhaustive small policy controls.
- 27 complete independent reports, actual Chrome checks of 50 current rows, 17 prior rows and 181 stage circles, plus isolated installed-wheel reproduction across eight module origins.
- Existing scanner/report formats remain. Fingerprint aliases and metadata-identity migration are explicit; real baselines and witnesses must stay private. No new detection patterns or security-effectiveness claim.

**[ScratchGPT](https://github.com/midya8/scratchgpt)**

NumPy GPT/autograd with validated exact continuation: both PCG64 streams, Adam
buffers/clock, data identity, options and runtime metadata. All 13 restart
boundaries match complete state in the same environment; RNG-reset and missing
moment controls expose failures. Independent scalar Adam and transformer
inference drive an [offline replay](https://midya8.github.io/scratchgpt/) with
all coordinates, editable contexts and JSON exports. 70 Python tests preserve
11 originals; three Node/Chrome tests and installed-wheel reproduction. The
historical 419,328-parameter Shakespeare checkpoint is unchanged. The replay is
a separate synthetic model; the browser does not train. No cross-machine
bitwise or new performance claim.

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


### CutLab response-path extension

[Open the exact response-path inspector](https://midya8.github.io/cutlab/path.html) · [Source and method](https://github.com/midya8/cutlab/blob/main/PATH.md)

Vary binary unary costs with a rational parameter and retain the complete optimum family on every closed region, open cell and breakpoint, including point-only optima and persistent ties. Every assignment keeps its affine line and every line comparison keeps its exact inequality. Independent graph-cut audits check all boundary and cell witnesses.

18 synthetic controls retain 214 assignment lines, 6,084 inequalities and 92 full flow/cut witnesses. Mixed-sign slopes include a label that leaves and returns: no nested-label or scalable parametric-maxflow guarantee is claimed. The inspector enumerates all 2^n assignments for at most six variables. Original flow/cut functionality and tests remain.


### Diagnoselab: all conflicts, all minimal repairs

[Exact logical consistency inspector](https://midya8.github.io/diagnoselab/) · [Source](https://github.com/midya8/diagnoselab)

Full relative MUS/MCS families, bidirectional minimal hitting-set intersections, per-member minimality/unique-hit witnesses and exact rational removal costs. Every soft subset retains its DPLL/unit trace and independent full truth-table models. The smallest repair need not be cheapest; an inconsistent fixed background has no soft repair.

18 original synthetic controls retain 827 subsets, 1,301 search nodes, 20 cores and 52 repairs. 17 Python tests on 3.10-3.13, four Node/Chrome tests, 74,292 exact cross-language scalar checks and installed-wheel reproduction. Exhaustive six-variable/eight-soft-clause bound, established SAT theory, no scalable solver, real fault diagnosis or certified proof claim. No model/API.

[Case study](https://github.com/midya8/Midya-portfolio/blob/main/projects/diagnoselab.md)


#### Diagnoselab repair-policy consequences

[Live query inspector](https://midya8.github.io/diagnoselab/consequences.html) · [Method/sources](https://github.com/midya8/diagnoselab/blob/main/CONSEQUENCES.md)

Distinguishes every/some repair from every/some surviving model, with all tied minimum-cost/cardinality policies, complete countermodels and negated-query DPLL traces. Shared-clause intersection is a separate baseline with strict counterexamples. No-repair families are inapplicable, not vacuous certainty. 26 new exact reports (16,165 scalar leaves), 67 repairs, 78 policy records and 151 full DPLL nodes including intersection baselines; 24 Python/eight Node-Chrome tests preserve all originals. Installed-wheel reproduction and mobile/table/export checks. Finite propositional reasoning, not a database/DL engine or probability claim.


## ArgumentLab: defense, not a vote

[Source](https://github.com/midya8/argumentlab) · [Live inspector](https://midya8.github.io/argumentlab/) · [Method and six sources](https://github.com/midya8/argumentlab/blob/main/METHOD.md) · [Case study](https://github.com/midya8/Midya-portfolio/blob/main/projects/argumentlab.md)

An exact bounded abstract-argumentation workbench. Compare all nine extension families, inspect every subset's attackers/defenders and unanswered attacks, all inclusion/range witnesses, complete three-valued labellings and the entire grounded fixed-point chain. Directed graph keeps opposite attacks and self loops visible. Acceptance retains witnesses and counterexamples, with a prominent classical skeptical-vacuity warning when no stable extension exists.

Original strict controls distinguish preferred from maximum cardinality, preferred intersection from grounded, a nonadmissible preferred intersection, and stage from semi-stable. Independent Python bitsets and JavaScript sets agree on all531 directed frameworks through three arguments/344,023 scalar leaves and19 retained full reports/152,884 leaves. Separate set/ternary oracles cover120 native and100 JavaScript seeded larger cases.19 native tests run on four Python versions; five Node/actual-Chrome tests check every retained UI record and graph state, export/invalid clearing and all19 controls at320/390/1280. Installed wheel reproduces19 full reports outside the checkout.

Eight arguments; exhaustive subsets; all ties retained. Established semantics, not a novel/scalable solver, probability model, benchmark win, real-world truth or debate winner. Six inspected sources and exact parser differences documented; no external solver code/data/examples copied or affiliation with existing ArguLab/ARGTEACH.


### ArgumentLab attack switches

[Live switch-cube inspector](https://midya8.github.io/argumentlab/switches.html) · [Source and method](https://github.com/midya8/argumentlab/blob/main/SWITCHES.md)

Enumerates every configuration of up to six supplied attack switches. Preserves all nearest ties, all inclusion-minimal matches, exact extension gains/losses and complete selected-framework defense witnesses. Original controls distinguish minimum cardinality from inclusion minimality and retain nonmonotone and nullable outcomes.

Verified on 21 controls, 209 configurations, 5,205 subset classifications and 423 switch transitions. Independent Python and JavaScript engines, installed CLIs, browser exports and responsive inspection. These are bounded hypothetical edits, not causal effects, persuasion advice or a scalable solver.


## ConceptLab: exact concepts and implication witnesses

[Live inspector](https://midya8.github.io/conceptlab/) | [Source](https://github.com/midya8/conceptlab) | [Method and prior work](https://github.com/midya8/conceptlab/blob/main/METHOD.md)

A bounded knowledge-representation workbench for formal concept analysis. Independent Python and JavaScript enumerate every formal concept, cover, meet/join, attribute closure and object derivation. Inspect canonical implications, pseudo-intent decisions, NextClosure pivots, forward rule traces and rule-removal countermodels. Every implication query retains supporting and counterexample rows; an empty premise extent means vacuous validity and null confidence, not evidence.

Fourteen original controls include duplicate rows, zero support, empty universes, strict joins, nonminimal pseudo-intents and multi-rule closure. The retained suite covers 194 attribute subsets, 390 object subsets, 69 concepts, 30 canonical rules, 635 ordered lattice operations and 5,762 implication queries. Independent set-based checks cover all 689 contexts with zero to three objects/attributes plus 100 seeded larger contexts per engine. Native CLI, installed wheel and actual-Chrome checks accompany the interactive inspector.

Finite exact teaching/audit tool: at most six attributes and eight objects. Not learned prediction, fuzzy concept analysis, noisy-data inference, causality or a scalable mining system. Existing FCA theory and software are attributed; no new algorithm is claimed.


### ConceptLab incomplete-context completions

[Live completion inspector](https://midya8.github.io/conceptlab/partial.html) | [Semantics and sources](https://github.com/midya8/conceptlab/blob/main/PARTIAL.md)

Unknown is not false. Enumerate every compatible binary completion of a three-valued table. Inspect certain, contingent and impossible implications, all object counterexamples, exact defined row-confidence bounds and endpoint ties, with zero-support completions kept separate. Intersect goals in one shared completion and retain every inclusion-minimal impossible goal set with deletion witnesses.

Original controls expose two traps: both extreme fill-ins can pass while an intermediate world refutes an implication, and separately possible goals can be jointly impossible. Overlapping-premise tautologies, empty universes, duplicate objects and all 64 worlds of six unknowns remain explicit. Twelve controls cover 86 completions, 438 implication queries, 4,634 query/completion witness rows and 63 goal subsets.

Independent Python and JavaScript engines, 17 native tests on four Python versions, six Node/Chrome tests and 26 installed-wheel reports preserve the complete-context workbench. Every retained UI record, export and invalid-input clearing is checked; all controls are layout-tested at 320/390/1280. Limits: four attributes, four objects, six unknown cells. Completion counts are not probabilities; confidence bounds describe supplied rows, not unseen data. No imputation, causal claim, graded possibility model, incomplete-context basis or new algorithm is claimed.


### STRIPSLab exact planning and relaxation witnesses

[Live inspector](https://midya8.github.io/stripslab/) · [Source](https://github.com/midya8/stripslab) · [Method and prior work](https://github.com/midya8/stripslab/blob/main/METHOD.md)

An original bounded classical-AI planning lab: audit every state and every blocked/applicable action, compare exact real and delete-relaxed shortest-plan families, and inspect h-max/h-add fixed-point rounds and tied fact achievers. Strict controls expose shared-effect double counting, relaxed solvability hiding real dead ends, restoration costs, all shortest-order ties and unreachable cyclic prerequisites. Python bitsets/reverse BFS and independent JavaScript sets/Bellman sweeps reproduce the same complete reports.

Six facts, eight grounded positive-precondition unit-cost actions. No PDDL parser, real-world execution, scalable-planner claim or new planning algorithm. Fourteen original synthetic tasks; eight Python tests, three Node/Chrome tests and isolated wheel reproduction of all fourteen full reports. Established STRIPS and heuristic-planning work is attributed with inspected-source limits.

[STRIPSLab case study](https://github.com/midya8/Midya-portfolio/blob/main/projects/stripslab.md)


### STRIPSLab search witnesses: an actual suboptimal h-add plan

[Inspect four complete search runs](https://midya8.github.io/stripslab/search.html) · [Search policy and reproducible evidence](https://github.com/midya8/stripslab/blob/main/SEARCH.md)

The new A*/best-first inspector exposes every selected frontier, strict cost improvement, applicable action decision and returned plan. A controlled task returns cost 3 with h-add versus exact cost 2 under the disclosed tie and goal-pop policy. Zero, h-max and exact h-plus return cost 2. Includes admissibility/consistency diagnostics, unsolvable exhaustion, strict CLI certificates, an independently implemented browser engine, and a separate synthetic reopening test. Full-state precomputation is explicit: this is a bounded audit, not a planner speedup or new algorithm claim.


### STRIPSLab availability: used does not mean necessary

[Live action-availability inspector](https://midya8.github.io/stripslab/sensitivity.html) | [Exact source and policy](https://github.com/midya8/stripslab/blob/main/SENSITIVITY.md)

Disable every static action subset. Keep every exact counterfactual distance, shortest-plan count, original action ID, representative and optimal edge. Separate an action used by one representative from one required by every optimal plan or every valid plan. Retain all inclusion-minimal sufficient sets and all solvability/optimality cuts, with independently checked minimal-hitting-set duals.

The original duplicate-shortcut control leaves a longer detour when both shortcuts are removed: optimality fails before solvability does. Eighteen controls retain 466 scenarios, 21,731 state rows and 408 optimal edges. Python BFS and independent JavaScript distance sweeps agree on 118 complete reports covering 2,515 scenarios; independent native set-transition and all-proper-subset oracles cover another 80 seeded tasks. Seventeen native tests, nine Node/Chrome tests and 47 isolated installed reports preserve all earlier modes. Browser checks every retained scenario at 320/390/1280.

Six facts/eight unit-cost grounded actions maximum. Static deterministic re-planning, not failure probabilities, timed outages, a scalable landmark extractor, real-world reliability or a new algorithm. [Implementation, boundaries and inspected sources](https://github.com/midya8/stripslab/blob/main/SENSITIVITY.md).


## UnifyLab: a binding is not a solution

[Live finite-term inspector](https://midya8.github.io/unifylab/) | [Source](https://github.com/midya8/unifylab) | [Method and inspected sources](https://github.com/midya8/unifylab/blob/main/METHOD.md)

An original bounded classical-AI unification lab. Keep every equation rewrite, composed earlier binding, exact constructor clash and zero-based occurs-check cycle path. A normalized simultaneous substitution is applied to every original equation. Alias reversal is not automatically a cycle, and a resource limit never means non-unifiability.

Independent Python and JavaScript engines reproduce 167 complete reports and 270 rewrites. A separate native certificate checker reconstructs local rules without calling the solver; a third lazy-environment oracle tests controls, 600 seeded systems and all 64 term-pool pairs. Seventeen controls retain 38 rewrites, including actual state/result expansion limits. Twelve native tests on Python 3.10-3.13, three Node/Chrome tests and seventeen isolated installed reports through two CLIs in solve/verify modes. Every retained browser step, equation, binding, witness, export and invalid edit is checked, with layouts at 320/390/1280.

Established finite-tree unification, not new theory. Six variables/eight equations, 96 input nodes, 4,096-node state/result budgets and 256 rewrites. No rational trees, higher-order/AC unification, resolution prover, linear-time or benchmark-win claim. Most-generality follows the established rewrite/solved-form theory; bounded ground-factorization tests are not a universal proof. [UnifyLab case study](https://github.com/midya8/Midya-portfolio/blob/main/projects/unifylab.md).


## UnifyLab: minimal equation conflicts and deletion repairs

[Live subset inspector](https://midya8.github.io/unifylab/cores.html) · [Source](https://github.com/midya8/unifylab) · [Method and inspected sources](https://github.com/midya8/unifylab/blob/main/SUBSETS.md)

Test every indexed subset, keep duplicate equation identities, and distinguish an inclusion-minimal conflict from a smallest conflict. Confirmed deletion repairs list indices to REMOVE and failing single restorations. The default control has independent duplicate/cycle conflicts and repairs of different sizes. A resource limit stays unresolved: no inferred status, false inconsistency, complete-frontier or minimum-size claim. Any selected subsystem opens its detailed rewrite trace.

Eight synthetic controls cover 371 subsets, including all 256 masks at the eight-equation bound, real state/result limits and a known clash beside an unknown expansion. Independent Python/JavaScript engines match 108 full audits and 1,032 subset summaries. Nineteen native tests pass on Python 3.10-3.13; six Node/Chrome tests. Native tests use a third lazy-binding oracle, all proper subsets and independent minimal hitting-set enumeration. Actual Chrome checks every control/subset/neighbor at 320/390/1280, five linked rewrite reproductions, export and invalid-state clearing. Installed wheels reproduce seventeen base reports and eight subset audits through both entry points outside the checkout.

Established finite-tree and constraint-diagnosis concepts, not a new scalable MUS/MCS algorithm. At most 256 independent bounded solves; the aggregate is not an independently verified rewrite certificate. Eight inspected sources distinguish minimal from minimum, conflict from repair, and unifiability semantics from resource limits. No model, API, paid service or private dataset.


## UnifyLab: repeated differences, shared variables

[Ground generalization inspector](https://midya8.github.io/unifylab/generalize.html) · [Method and inspected sources](https://github.com/midya8/unifylab/blob/main/GENERALIZATION.md) · [Source](https://github.com/midya8/unifylab)

Finite ground-term anti-unification: keep common constructors and give the same ordered disagreement pair the same variable. Inspect fresh/reuse records, two substitution maps and exact reconstructions. The independent native checker rejects coherent overgeneralization even when both inputs reconstruct. Python and independently written JavaScript agree on 209 reports; nine synthetic controls expose 43 node records. Original solver and subset inspectors retained.

27 native tests, nine Node/Chrome tests, installed wheel checks through both CLI entry points and responsive 320/390/1280 inspection. Established syntactic anti-unification, not a new algorithm, semantic clone detector or code repair model. Ground finite trees only; the checker validates the canonical trace, not arbitrary renamed certificates or a formal proof.


## HornLab: a circle is not a proof

[Live inspector](https://midya8.github.io/hornlab/) · [Source and tests](https://github.com/midya8/hornlab) · [Method and sources](https://github.com/midya8/hornlab/blob/main/METHOD.md)

Bounded positive propositional Horn inference with synchronous derivation rounds and every indexed rule decision. Compare the least model with every classical and supported model: a supported circular assignment need not have a derivation. Inspect an atomic countermodel for each non-entailed query and every inclusion-minimal initial-fact support, including its deletion failures and all seed subsets. Not entailed does not mean classically false.

Independent Python bitsets and JavaScript sets match 210 full reports; a separate native set/truth-table checker replays the complete report. Ten original controls, exhaustive two-atom programs, seeded tests, installed-wheel reproduction and actual Chrome record checks. Six atoms/eight rules, no negation or variables; established semantics, not a new algorithm or production rule engine.


## HornLab: every route, every break

[Rule-deletion inspector](https://midya8.github.io/hornlab/rules.html) · [Method and primary sources](https://github.com/midya8/hornlab/blob/main/RULES.md) · [Source](https://github.com/midya8/hornlab)

Keep initial facts fixed and inspect all indexed-rule subsets, synchronous closures, every minimal rule support and every minimal deletion set. One broken route need not break the goal. Each support retains one-rule removal failures; each deletion retains restoration successes. Both minimal-hitting-set dualities and every support/deletion intersection are explicit, including empty-support and already-absent boundary cases.

Eighteen native tests retain all originals, with all 1,024 two-atom programs and 150 seeded rule lattices. Independent Python/JavaScript match 131 audits covering 5,304 subsets. Eleven browser controls expose 305 subsets, 35 queries, 36 supports, 27 deletion sets and 36 intersections, all record-checked at 320/390/1280. A separate native set/truth-table checker validates the complete lattice without calling the generator. Installed-wheel reproduction checks both inspectors through both CLI entry points. Established bounded monotone explanation, not causal attribution, ontology translation, a new algorithm or formal proof.


### BisimLab: same traces, different choices

[Source](https://github.com/midya8/bisimlab) · [Interactive inspector](https://midya8.github.io/bisimlab/) · [Method](https://github.com/midya8/bisimlab/blob/main/METHOD.md)

Finite agent-protocol equivalence from scratch: every strong-bisimulation refinement, every failed left/right step match, executable Hennessy-Milner witness DAGs, truth sets and a quotient graph. The default original control has equal finite trace languages but loses a choice after the same action; exact paired-subset BFS checks trace equality separately from branching equivalence. A native partition-signature checker never calls the generator, and independent JavaScript matches full reports. Nine native tests include all 512 three-state/one-action graphs against relation enumeration and 100 seeded graphs; three Node/actual-Chrome tests include 593 complete cross-engine reports and every control record at 320/390/1280. Installed-wheel checks cover both CLI entry points outside checkout. One to six states, all labels visible: no silent abstraction, probabilities, policy guarantee, source extraction, new algorithm or formal-proof claim. Established theory and seven inspected sources are attributed in the method.


### BisimLab: complete trace-product replay

[Interactive trace product](https://midya8.github.io/bisimlab/traces.html) | [Source and exact semantics](https://github.com/midya8/bisimlab/blob/main/TRACES.md)

The second inspector retains the entire reachable product of two states' possible successor sets, including every action edge after a mismatch and the both-empty sink. Inspect canonical BFS discovery words, layers, all possibility-mismatch nodes and a shortest distinguishing path. Equal finite traces still do not imply branching equivalence.

Python bitmasks, independent JavaScript sets and a separate native checker based on explicit subset tables agree on 4,715 trace reports. Seventeen native tests include exhaustive unary three-state graphs across every ordered pair, direct word enumeration, seeded multi-action cases and forged closure/provenance checks. Six Node/actual-Chrome tests cover every control record, export and invalid-input clearing at 320/390/1280px. Installed-wheel checks cover six original and seven trace controls, two CLI entry points and six import origins. One to six states, all actions visible; exponential and bounded, with no silent actions, model/API dependency, scalable-solver or new-algorithm claim. Established subset determinisation and product language equivalence are attributed in the source ledger.


### ShieldLab: a safe next step can still lose

[Source](https://github.com/midya8/shieldlab) | [Interactive inspector](https://midya8.github.io/shieldlab/) | [Exact method and seven-source ledger](https://github.com/midya8/shieldlab/blob/main/METHOD.md)

An exact tiny safety-game inspector for hand-written agent protocols. Every synchronous fixed-point obligation, winning controller move, losing rank and branching invariant/counterstrategy graph is visible. Changing only who controls a state flips the result: one-step-safe actions need not preserve safety forever. Independent bitmask Python and explicit-set JavaScript, plus a separate dual-attractor and exhaustive positional-policy checker.

Eight native tests include all 21,952 three-state graph/ownership/safety combinations and 150 seeded larger arenas. Three Node/actual-Chrome tests compare 643 complete reports and all six controls at 320/390/1280. Installed wheels replay both CLI entry points outside checkout. Finite total perfect-information model only: no runtime shield, LLM guarantee, liveness, timing, probability, new algorithm or formal proof. Dead ends are rejected; safe waiting need not mean progress.

### BuchiLab: a winning state is not a winning policy

[Interactive inspector](https://midya8.github.io/buchilab/) | [Source](https://github.com/midya8/buchilab) | [Method and seven-source ledger](https://github.com/midya8/buchilab/blob/main/METHOD.md)

Tiny finite adversarial repeated-goal games with every nested greatest/least fixed-point obligation, progress rank, complete positional controller policy and reachable cyclic non-goal SCC visible. Idle can stay inside the winning region forever and still lose: rank-guided progress and per-policy audits show why. A separate checker replays with sets/Floyd reachability and every joint-policy eventual lasso, without calling the generator. Nine native tests include 21,952 exhaustive three-state games; three Node/actual-Chrome tests compare 331 complete Python/JavaScript reports and every control record at 320/390/1280. Installed wheels replay seven original controls through both CLIs outside checkout. No fairness assumption, learned abstraction, deployed shield, general LTL compiler, formal proof or real-agent guarantee. Rank-permitted actions are sufficient, not all winning policies.

### BuchiLab: repeat the actual failure

[Action-level lasso inspector](https://midya8.github.io/buchilab/lassos.html) | [Exact witness contract](https://github.com/midya8/buchilab/blob/main/LASSOS.md)

A reachable bad component now becomes an exact action-labelled prefix once and nonempty non-goal cycle forever, for every failing fixed controller policy/root. Empty prefixes, self-loops, multiedge cycles, unreachable bad components and duplicate-target action choices are explicit. BFS generation is independently checked with bounded simple walks and the joint-policy lasso oracle. Original v1 reports and original tests stay intact: 16 native tests across four Python versions and five Node/actual-Chrome tests, including 314 complete witness-report comparisons and every record in ten controls at 320/390/1280. Installed wheels replay both report families outside checkout. Input-order anchor, shortest prefix/cycle individually, not globally shortest lasso. These are per-policy counterexamples, not one environment strategy defeating every controller policy or a real-agent guarantee.

## HallLab: distinct is a global promise

[Live inspector](https://midya8.github.io/halllab/) · [Source](https://github.com/midya8/halllab) · [Method and six-source ledger](https://github.com/midya8/halllab/blob/main/METHOD.md)

Tiny constraint-based AI assignment, with every supported variable/value backed by a complete injective assignment and every rejected edge explained by a forced-residual Hall obstruction. A full synchronous pairwise-AC baseline makes the global bottleneck visible. Exact matching/counting, independent exhaustive native checker, separate JavaScript assignment engine, editable graphs, all tight/deficient subsets and every propagation round.

12 native tests include 8,777 exhaustive domain graphs; 682 complete cross-engine reports; actual Chrome checks every control edge/subset/round at 320/390/1280. Fresh installed CLI replay. Original synthetic controls, no learned model or paid API. At most six variables/eight values, one constraint: not an optimized Régin SCC propagator, scalability benchmark or whole-CSP solver.


### HallLab: local support is not a shared solution

[Overlapping-scope inspector](https://midya8.github.io/halllab/overlaps.html) · [Exact overlap contract and sources](https://github.com/midya8/halllab/blob/main/OVERLAPS.md) · [Source](https://github.com/midya8/halllab)

Repeat full local all-different propagation to a synchronous fixed point, then compare it with exact common-assignment support across overlapping scopes. A two-color triangle keeps every local value but has no joint assignment. A satisfiable triangle keeps local values that never occur in a common solution. Inspect each round, original-variable mappings, scope-only witnesses, full common witnesses and exhaustive rejection bins.

Separate native API/module CLI, independent report checker and JavaScript engine. Eight new native tests and three new Node/Chrome tests preserve the original test sources. Full cross-engine checks cover 621 overlap reports; nine browser controls run at 320/390/1280 widths. Installed-wheel checks run outside the checkout. Tiny exact reference: six variables, eight values, six scopes, at most 262144 full tuples. Classic consistency theory, not a scalable CP solver or a new algorithm.


### HallLab: every minimal conflict, every minimal removal

[Live conflict inspector](https://midya8.github.io/halllab/conflicts.html) · [Exact contract and seven-source ledger](https://github.com/midya8/halllab/blob/main/CONFLICTS.md) · [Source](https://github.com/midya8/halllab)

All inclusion-minimal conflicting all-different scope sets and all inclusion-minimal scope-removal repairs, with complete single-deletion witnesses, common kept-network assignments and contained conflicts for every restoration. The default diamond has a size-one and four size-two minimal removals: minimal is not minimum. Inspect every active subset and the hitting-set intersections that explain why a repair must break every conflict. Domains stay fixed; an empty-domain background has no scope-removal repair.

Independent native histogram generation, per-subset product verification and recursive JavaScript search. 28 native tests, nine Node/actual-Chrome tests; 621 cross-engine reports and 4413 active subsets. Installed wheel reproduces all three report families outside checkout. Prior implementations/tests retained. All browser controls/proofs checked at 320/390/1280. Tiny exact relations, not a scalable MUS/MCS solver, weighted optimizer or a new duality theorem.


## STNLab - temporal bounds with attainable schedules

[Live inspector](https://midya8.github.io/stnlab/) · [Source](https://github.com/midya8/stnlab) · [Method and source ledger](https://github.com/midya8/stnlab/blob/main/METHOD.md) · [Case study](https://github.com/midya8/Midya-portfolio/blob/main/projects/stnlab.md)

For tiny hand-written AI plans, inspect every implied time difference: a tight path plus a complete schedule attaining the bound, or an explicit ray proving it unbounded. Negative cycles show exactly why no schedule exists, even away from the anchor. Removing one edge returns an alternate implication path or a complete separating schedule. Eleven editable controls include duplicate edges, zero cycles, free components and a chain with bound 100.

Native Floyd-Warshall/Bellman-Ford generation, independent permutation/edge-product verification and recursive browser search agree. Nine native tests cover exhaustive tiny graphs, seeded networks and strict CLI rejection; real Chrome checks all proof panels at three widths. Six points and twelve constraints, real-valued times, no resource capacity, uncertain durations or execution guarantee. Classic temporal-network theory, not a new optimization algorithm.


## STNLab insertion sensitivity

One proposed temporal constraint, an exact consistency threshold and every changed implied bound. [Source](https://github.com/midya8/stnlab) · [Insertion inspector](https://midya8.github.io/stnlab/insertions.html) · [Contract and source ledger](https://github.com/midya8/stnlab/blob/main/INSERTIONS.md).

Native old-matrix one-edge closure is checked against independent full recomputation. Inspect the old return path, a complete schedule at the feasibility boundary, a candidate-first negative cycle, or a still-unbounded anchored ray. All finite post-insertion bounds include attaining schedules; 41 integer weights are separate alternatives, not accumulated changes.

Ten new synthetic controls include exact-boundary feasibility, a missing return path, a pre-inconsistent base, duplicate/self-loop cases, a six-point threshold outside the input window and a 12-edge base plus candidate. The original inspector remains intact. Seventeen Python tests, six Node/real-Chrome tests and installed-wheel checks cover both families. This is bounded classical temporal reasoning, not event execution, uncertainty handling, a new algorithm or a scalable verifier.


### STNLab existential projection

[Interactive projection lab](https://midya8.github.io/stnlab/projection.html) | [Source](https://github.com/midya8/stnlab) | [Exact contract](https://github.com/midya8/stnlab/blob/main/PROJECTION.md)

Hide time points without losing the bounds their paths imply. STNLab restricts the closed network to retained original IDs, lifts jointly feasible retained assignments into full original schedules, and exposes retained assignments that naive edge deletion wrongly permits. Each finite projected bound has an original path and a full attaining schedule; unbounded pairs have anchored rays. Hidden negative cycles remain impossible.

Independent Fourier-Motzkin elimination, path enumeration and pinned-cycle checks audit the result. Native Python and separate browser recomputation agree across 12 projection controls, with installed CLI reproduction and real Chrome proof-panel tests at 320, 390 and 1280 pixels. Classical STN analysis over real-valued time points, not a new algorithm, calendar executor or uncertainty model.


## STNLab complete conflicts and repairs

[Live conflict/repair inspector](https://midya8.github.io/stnlab/conflicts.html) | [Source](https://github.com/midya8/stnlab) | [Exact contract and sources](https://github.com/midya8/stnlab/blob/main/CONFLICTS.md)

Enumerate every inclusion-minimal temporal conflict and every inclusion-minimal correction set. Replay negative cycles, conflict-deletion schedules, repaired schedules and restoration contradictions. An independent native verifier checks complete hitting-set duality; a separate JavaScript engine powers the inspector. Minimal is explicitly distinct from minimum-cardinality.

Validation: 31 native tests on Python 3.10-3.13, 12 Node/Chrome tests, 316 cross-engine reports, exhaustive tiny networks and installed-wheel reproduction for all four STNLab families. Chrome visits every control proof at 320/390/1280. Includes duplicate edges, disconnected conflicts, self-loops, empty repairs and the 12-edge boundary. Classical duality applied to bounded STNs, not a new-theory or scalable-solver claim.


## EUFLab: ground equality with evidence

[Live proof and countermodel inspector](https://midya8.github.io/euflab/) | [Source and reproduction](https://github.com/midya8/euflab) | [Semantics and six-source ledger](https://github.com/midya8/euflab/blob/main/METHOD.md)

Functions preserve equality, not difference. EUFLab exposes ground congruence proof DAGs, every contradicted disequality and a total finite interpretation for consistent inputs. Inspect non-injectivity, cyclic values, duplicate syntax, ordered arguments and inconsistent-premise boundaries. Native union-find/proof forests, separate browser relation saturation, independent proof/model verification and exhaustive set-partition references make the claims inspectable.

Validation: 9 native tests on Python 3.10-3.13; 156 cross-engine reports; 251 query selections at each of 320, 390 and 1280 pixels; installed-wheel generation and verification through both entry points. Bounded ground conjunctions only, not quantified logic, arithmetic, SMT-LIB parsing or a production SMT solver. No model service or paid API.


## EUFLab finite-model atlas

[Live finite-model atlas](https://midya8.github.io/euflab/atlas.html) | [Source and reproduction](https://github.com/midya8/euflab) | [Exact atlas contract](https://github.com/midya8/euflab/blob/main/ATLAS.md)

The most separated quotient is not necessarily the smallest model. EUFLab now enumerates every compatible term-equality pattern, finds minimum domain size, and classifies each pair as forced equal, forced different or flexible. Explore total model witnesses, unary backward difference, binary disjunctions, odd-cycle coloring and all 4,140 eight-name patterns. Counts are equality patterns, not full interpretations; extra unnamed domain elements remain possible.

Independent restricted-growth, explicit-block and subset-cover enumerators. Validation preserves the original nine native tests: 16 native tests on Python 3.10-3.13, six Node/Chrome tests, 76 complete cross-engine atlas reports, installed-wheel reproduction of both inspector families, and all 4,317 admitted control patterns at 320/390/1280 pixels. Exhaustive ground-conjunction search, capped at eight terms; no scalability or new-algorithm claim.


## EUFLab domain-cap debugger

[Live bounded-domain debugger](https://midya8.github.io/euflab/cardinality.html) | [Source and reproduction](https://github.com/midya8/euflab) | [Exact diagnosis contract](https://github.com/midya8/euflab/blob/main/CARDINALITY.md)

Too few values? Find every cause. With the domain cap held fixed, enumerate every inclusion-minimal assertion conflict and deletion repair. Separate intrinsic inconsistency from cap-only conflicts, inspect every assertion subset, and replay total models for repairs or one-literal core relaxations. Duplicate occurrences retain their identities; minimal repairs need not have minimum size. A three-cycle shows why explicit difference-edge coloring alone misses functional constraints.

Validation: 23 native tests on Python 3.10-3.13, nine Node/Chrome tests, 269 complete cross-engine reports, independent labeled-assignment and hitting-set references, and installed-wheel reproduction of all three inspector families. Chrome audits 379 subset selections, 36 core-relaxation actions, 29 repair actions and 104 cap changes at each of 320/390/1280 pixels. Eight terms, eight assertion occurrences, ground conjunctions only. Complete bounded enumeration, not a new algorithm or scalability claim.


## EUFLab costed repair planner

[Live planner](https://midya8.github.io/euflab/planner.html) · [Source and exact contract](https://github.com/midya8/euflab/blob/main/PLANNER.md)

Protect what cannot change, price what can. The fourth EUFLab inspector enumerates every permitted deletion set, every cost-only optimum and a separate cost/count Pareto frontier. Protected intrinsic or cap-only cores explain infeasibility. Each plan includes a total minimum-domain model with kept, protected and omitted assertion truth rows.

Zero-cost nonminimal ties are preserved, not silently filtered to minimal repairs. Deleting does not mean negating; the live control shows an omitted equality that still holds. Costs never override protection. Fourteen synthetic controls cover different-size/same-cost optima, two-coordinate tradeoffs, duplicate occurrences, hard obstructions and function-driven cardinality.

Native and browser engines agree on 358 complete reports. Independent labeled-domain references check graph/protection policies and functional DAGs; an independent certificate verifier rebuilds models and checks all masks/objectives. Python 3.10-3.13, installed module/console reproduction and actual Chrome phone/desktop checks. Eight terms/eight assertions, ground one-sort conjunctions; no general MaxSMT, new-algorithm or scalability claim. Nothing is actually edited.


### EUFLab exact repair-cost sensitivity

[Live sensitivity inspector](https://midya8.github.io/euflab/sensitivity.html) | [Source and certificate contract](https://github.com/midya8/euflab/blob/main/SENSITIVITY.md)

Vary one assertion deletion cost over every integer from 0 to 1,000,000. The certificate gives exact keep/delete intervals, breakpoint ties and every optimum mask, including zero-cost nonminimal repairs. An independent native verifier rebuilds all affine plan-cost lines; the browser inspector audits replacement costs, regret and total models without treating omitted assertions as negated. Hard protections and blocked policies remain explicit. This is bounded exhaustive analysis, not an industrial-scale solver or simultaneous multi-cost robustness guarantee.


### DFALab: active learning with exact counterexamples

[Live inspector](https://midya8.github.io/dfalab/) | [Source and contract](https://github.com/midya8/dfalab/blob/main/CONTRACT.md) | [Case study](https://github.com/midya8/Midya-portfolio/blob/main/projects/dfalab.md)

Ask membership questions, repair an observation table, then break a wrong conjecture with a shortest counterexample. Classic Angluin L* is replayed with every experiment, closure/consistency witness and complete reachable-product equivalence check. The final DFA has access words and pair-separating suffixes proving minimality. Independent Python/JavaScript reports and a separate certificate checker are tested against exhaustive tiny teachers and a pair-marking oracle. Exact equivalence relies on the supplied finite synthetic teacher, not random tests of a real service; no new algorithm or query-efficiency claim.

### DFALab: bounded conformance, not an unrestricted test-pass claim

[Live W-method inspector](https://midya8.github.io/dfalab/conformance.html) | [Construction, assumptions and sources](https://github.com/midya8/dfalab/blob/main/CONFORMANCE.md) | [Source](https://github.com/midya8/dfalab)

The classic DFA W-method now has a complete experiment inspector: every state-cover word, middle word, distinguishing suffix, canonical factor and acceptance path. It separates four claims: finite suite agreement, the supplied candidate's reachable-state bound, a bounded equivalence certificate and a separate exact graph audit. A faulty extra-state candidate passes when its bound is understated; increasing the bound exposes the fault. Tests do not infer a hidden service's state count.

An independent verifier reconstructs all factor combinations and checks every output and witness without calling the generator. Six added native tests include 52,488 exhaustive reference/candidate cases; 131 full native/browser-engine reports are cross-checked. Actual Chrome audits 3,444 test selections and 141 probes across eleven controls and three widths. Four Python versions, seven Node/Chrome checks and installed two-family reproduction preserve the original L* learning page and schema. These are synthetic fixture checks, not production-protocol benchmarks or a new theorem. The method is credited to Vasilevskii and Chow; the precise DFA theorem and reset/state-bound assumptions are documented.

### DFALab: exhaustive finite fault atlas and exact test-subset selection

[Live fault atlas](https://midya8.github.io/dfalab/fault-atlas.html) | [Exact domain, cost and sources](https://github.com/midya8/dfalab/blob/main/FAULT_ATLAS.md) | [Source](https://github.com/midya8/dfalab)

Enumerate every complete labeled implementation in a tiny unary/binary state domain, distinguish equivalent survivors from real faults, and inspect every acceptance-matrix row. Every subset of the constructed W-suite is checked under test-count then letter-count cost. All minima, escaping faults and chosen-test deletion witnesses are retained. Irredundancy is not confused with minimum cardinality; label/unreachable-state duplicates are not counted as unique languages or bug frequencies.

An independent native verifier reconstructs the complete machine domain and every subset result. Tests cover all 60 tiny minimal references with a separate equivalence oracle. Eleven complete cross-engine atlas reports match; actual Chrome audits 6,996 candidate selections and 804 subset selections across eight controls and three widths. All eighteen native checks on four Python versions, ten Node/Chrome checks and installed three-family reproduction preserve active learning and bounded conformance. Optimization is restricted to subsets of the generated W-suite, not globally shortest tests or real-world protocol coverage. Classic W-method and set-cover ideas are explicitly credited.


### SynthLab: counterexample-guided bit-vector program synthesis


**Fits the examples. Fails the function.** A learner chooses the cheapest grammar expression fitting known examples; an exact finite verifier returns the first wrong input. Inspect every iteration, eliminated candidate, complete truth table and evaluation tree. Full-domain semantic signatures safely deduplicate programs without using the target; a separate verifier enumerates every raw ordered grammar tree to check bounded completeness and canonical minimum cost.

Ten synthetic controls separate example agreement, exact finite correctness and minimum AST-node cost inside the explicit grammar. Eight native tests run on Python3.10-3.13, including512 Boolean target/grammar pairs and2764 raw trees at each of three widths; four Node/actual-Chrome tests audit30 reports,90 iterations,903 candidate signatures and3420 expression probes. Installed module+console reproduction runs outside the checkout. Classical CEGIS/enumeration credited. No novel algorithm, unbounded synthesis, cvc5 integration or production-code benchmark claim.

[Live inspector](https://midya8.github.io/synthlab/) · [Source](https://github.com/midya8/synthlab) · [Grammar, proof boundary and sources](https://github.com/midya8/synthlab/blob/main/CONTRACT.md)

#### Exact finite teaching-set atlas

**A correct program need not be uniquely identified.** The teaching inspector separates CEGIS correctness from eliminating every rival function. For realizable 1-bit and 2-bit targets it checks every input subset, reports all minimum-cardinality teaching sets and seed-constrained minima, and provides row-deletion rival witnesses. A separate direct-intersection verifier checks the complete atlas, including the embedded raw-AST synthesis certificate.

The two-bit XOR control has 132 distinct rival functions and 65,536 input subsets. CEGIS stops correctly with four examples but leaves three rivals; the atlas finds 182 four-row teaching sets. Same number of examples does not mean the same identifying power. Five teaching controls add seven native tests and three Node/Chrome checks, bringing the project to 15 native tests on Python 3.10-3.13 and seven Node/Chrome checks. Chrome audits 15 teaching reports, 1,203 subset selections and 597 rival truth selections; installed module and console reproduction runs outside the checkout.

[Teaching inspector](https://midya8.github.io/synthlab/teaching.html) · [Teaching contract and sources](https://github.com/midya8/synthlab/blob/main/TEACHING.md) · [Reviewed implementation](https://github.com/midya8/synthlab/pull/2)

Finite target-specific identification, not class-wide teaching dimension or PAC learning. Classical teaching-set/minimum-cover ideas credited to Goldman and Kearns; word-valued labels use explicit equality. No new teaching algorithm claim.

#### Exact adaptive query policies

**Let the answer choose the next question.** The adaptive inspector solves the smallest worst-case number of further input queries needed to identify any function still fitting the initial observations. It audits every nonempty version space, every query's label partition, all tied minimax rows, a canonical policy and every possible target path. A separate verifier checks the complete recurrence and the underlying raw-tree synthesis certificate.

A full seeded two-bit grammar leaves ten functions after two known observations. Two further adaptive queries suffice, while every fixed passive separating set needs three rows. Immediate split balance is not the same objective: across all balanced tie resolutions, policies need two or three further queries. Neither an easier hand-selected class nor an unlucky chosen baseline tie is used.

Seven additional native tests bring the project to 22 on Python 3.10-3.13; five additional Node/Chrome checks bring it to 12. The adaptive tests compare 541 complete native/JavaScript reports with independent verification. Actual Chrome audits 15 adaptive reports, 1,583 version-space selections, 111 query partitions, 306 answer branches, 84 target traces and 105 passive mask selections. Installed module+console reproduction includes all three certificate families outside the checkout.

[Adaptive inspector](https://midya8.github.io/synthlab/adaptive.html) · [Exact adaptive contract and sources](https://github.com/midya8/synthlab/blob/main/ADAPTIVE.md) · [Reviewed implementation](https://github.com/midya8/synthlab/pull/3)

At most ten functions after separately counted initial observations, exact noiseless labels and unit query cost. Future answers are simulated from supplied tables, not a live oracle. Classical decision-tree dynamic programming and generalized binary search credited. No expected-cost, PAC or novel-algorithm claim.

## WarpLab: inspectable differentiable alignment

Soft-DTW without the black box: scalar Python and browser JavaScript expose every Gibbs cell occupancy and joint edge flow, sequence/temperature gradients, and cost Hessian-vector products. A separate exhaustive path oracle checks every report field against all legal alignments.

- Stable log-space messages and directional expectation messages, no autodiff dependency. Cost curvature is checked against negative path-incidence covariance and finite differences.
- Eight synthetic controls include negative self-scores, a single legal path, low-temperature underflow and a 7 by 7 grid where all 8,989 paths tie. Hard ties compare exact rational sums of binary64 local costs, not a fuzzy tolerance.
- Strict JSON certificates, atomic CLI output and fresh installed module/console reproduction. Python 3.10-3.13 CI; 168 complete cross-language reports; real Chrome checks at 320/390/1280 pixels, including cell/edge inspection, complete paths, accessible row/column controls, export and error clearing.

[Live alignment inspector](https://midya8.github.io/warplab/) · [Source and reproduction](https://github.com/midya8/warplab) · [Mathematical contract](https://github.com/midya8/warplab/blob/main/CONTRACT.md) · [Reviewed implementation](https://github.com/midya8/warplab/pull/1)

Raw soft-DTW is not a metric and can be negative. Occupancy sums to expected path length, not one; it is not a transport coupling. Hessian products are in independent cost coordinates. Lengths are bounded to 1..7; synthetic controls are not accuracy or speed benchmarks. Established soft-DTW and differentiable-DP mathematics credited to Cuturi/Blondel and Blondel/Mensch/Vert. No novel-algorithm or ground-cost-independent divergence theorem claim.

### Path-length atlas

[Live length atlas](https://midya8.github.io/warplab/lengths.html) · [Length contract](https://github.com/midya8/warplab/blob/main/LENGTHS.md) · [Reviewed extension](https://github.com/midya8/warplab/pull/2)

Separate every legal visited-cell count before mixing paths. Length-resolved log messages expose exact path counts, conditional occupancies and joint edge flows, hard minima/ties, and conditional coordinate/temperature gradients. An explicit per-visited-cell penalty changes the mixture, not the conditional laws. Inspect the entropy decomposition, expected-length gradient and negative length-variance curvature.

The extension adds 98 independently verified complete cross-language atlases. Merged main passes 27 Python tests on each Python 3.10-3.13 and nine Node/Chrome tests, plus installed module/console reproduction for eight base and eight length controls. Live Chrome checks 81 length selections, 1,740 row/column cell inspections, 72 penalty changes and 96 complete reports at 320/390/1280 pixels. All ten deployed assets are source-exact; all 48 screenshots across both inspectors match verified main pixel for pixel.

Length includes both endpoints. Positive penalty favors shorter paths, negative penalty rewards longer paths: this is a changed objective, not an accuracy improvement. The independent oracle groups complete paths and checks the penalized law directly; it does not trust the length-message generator. Synthetic grids remain bounded to 1..7 samples, with at most 8,989 paths. No new-algorithm or benchmark claim.

### Inverse expected-length response

[Live inverse inspector](https://midya8.github.io/warplab/inverse.html) · [Inverse contract](https://github.com/midya8/warplab/blob/main/INVERSE.md) · [Reviewed extension](https://github.com/midya8/warplab/pull/3)

Choose a target expected visited-cell count and inspect whether penalty -4..4 can reach it. The full numerical bisection witness exposes every bracket, response, centered length variance and probability law. Finite-range failures, single-length unidentifiability and numerical flattening stay distinct. A narrow-bracket control deliberately misses the mean-residual tolerance, making the difference between stopping rules visible.

A separate complete-path oracle directly evaluates every witness penalty and checks the trace, status and selected response without calling the solver or length dynamic program. Merged main passes 37 Python tests on each Python 3.10-3.13 and 12 Node/Chrome tests. Tests include 36 complete cross-language inverse reports, derivative finite differences, random interior targets, generator-disabled verification and forged witnesses. Fresh installed module/console reproduction covers eight base, eight length and nine inverse controls. Live inverse Chrome checks 438 witness selections over 27 complete reports at 320/390/1280; all 15 deployed assets are source-exact, and all 75 screenshots across the three inspectors match verified main pixel for pixel.

This is bounded numerical evidence, not interval arithmetic or a unique-parameter certificate. A width stop does not promise a 1e-9 mean residual; unreachable targets show a diagnostic response, not a solution. Binary64 rounding can disagree at adversarial branch boundaries, in which case verification fails. No learned model, benchmark or new-algorithm claim.

## HingeLab: a boundary is not always an adversary

[Live inspector](https://midya8.github.io/hingelab/) · [Source](https://github.com/midya8/hingelab) · [Reviewed implementation](https://github.com/midya8/hingelab/pull/1) · [Case study](https://github.com/midya8/Midya-portfolio/blob/main/projects/hingelab.md)

Follow every rational affine region of a small ReLU network. Inspect hidden activation masks, exact decision roots and the full opposite-class set, including open endpoints and isolated ties. The report separates an attained nearest adversary from an unattained distance infimum and checks the actual closed-ball radius. A paired control keeps margin(x) = x fixed and changes only the reference side: the class-1 tie makes radius one robust on one side and nonrobust on the other.

Forward interval splitting is checked by an independent complete activation-mask enumerator that never calls the generator. Python Fraction and browser BigInt engines agree on 144 complete reports. Merged main passes 12 tests on each Python 3.10-3.13, including 200 seeded two-layer networks, generator-disabled verification and forged evidence. Four Node/Chrome tests and fresh installed module/console reproduction cover all eight controls. Live Chrome checks 54 region selections over 24 reports at 320/390/1280, export, stale clearing and invalid input. All five deployed assets are source-exact, and all 24 main/deployed screenshots match pixel for pixel.

This is exact only for the declared small rational, one-dimensional contract, with a fixed class-1 tie convention and explicit domain. SVG coordinates are rounded for display, never used as evidence. No trained model, model import, high-dimensional certificate, benchmark or new-algorithm claim. Established exact line-restriction and verification work is attributed; a downloaded browser report is independently checked only when the Python checker accepts it.

## HingeLab: every reference, one exact radius

[Live reference atlas](https://midya8.github.io/hingelab/reference.html) · [Source](https://github.com/midya8/hingelab) · [Reviewed implementation](https://github.com/midya8/hingelab/pull/2)

Compute the entire robust-reference set, not one sampled point. Exact class-component erosion keeps strict versus closed endpoints, isolated ties and domain-edge clipping. A nested tent's class-1 interval [-1/2, 1/2] at radius 1/2 shrinks to the robust singleton {0}; at 513/1024 it disappears. Its zero interval length never erases its existence. The exact robust-length fraction is not accuracy or a data probability.

A separate activation-mask/critical-atom checker exhausts every boundary/root and radius-shifted transition, without the reference generator or its erosion/union routines. Merged main passes 20 tests on each Python 3.10-3.13 and seven Node/Chrome tests. Evidence includes 160 new seeded networks with point agreement/radius monotonicity, 200 new complete exact Python/BigInt reference reports, 144 preserved base reports, generator-disabled and forged-type checks, and an additional 972-case tiny-network/domain/radius sweep. Fresh installed module/console reproduction covers eight base plus eight reference controls. Live Chrome checks 47 robust-component selections over 28 reference reports, plus 24 base reports, at 320/390/1280. All nine deployed assets match main, and all 52 main/deployed screenshots match pixel for pixel, including singleton, empty, above-threshold and zero-radius states.

The original bounded rational one-dimensional contract and class-1 ties are unchanged. The closed ball is intersected with the declared domain. Established piecewise-affine analysis and set erosion, not a new algorithm, trained/imported model, high-dimensional certificate, sampled-grid proof or benchmark. Browser evidence becomes independently checked only after Python accepts its download.

## HingeLab: every radius, exact

[Live all-radius profile](https://midya8.github.io/hingelab/radius.html) · [Source](https://github.com/midya8/hingelab) · [Radius-profile case study](https://github.com/midya8/Midya-portfolio/blob/main/projects/hingelab.md#radius-profile-extension)

Exact piecewise-linear robust interval length for every radius in [0,32],
class-wise and total existence sets with strict/closed extinction endpoints,
and the first radius at most a requested length fraction. Zero length is not
empty: margin x on [-2,2] retains a robust singleton at radius 2. A separate
mask/atom checker reconstructs the complete profile from candidate collision
radii and opposite-class closed-ball intersection, without importing the
profile/reference generator or erosion/union code. Full exact JSON export.

44 source files verified on merged main `4b1ceacf5ffeeb25ed8052c48053a926e91dd047`.
26 Python tests on each of 3.10-3.13; ten Node/Chrome tests; 104 new complete
cross-language profile reports plus 200 reference and 144 base reports; fresh
installed reproduction for eight controls in each report family. Live Chrome
checks 28 radius, 28 reference and 24 base reports. All 13 deployed assets are
source-exact; all 80 native/feature/main/deployed screenshots match without
masks and final phone/desktop/conditional pixels were inspected. Feature, PR,
main CI and Pages all green. [Merged PR](https://github.com/midya8/hingelab/pull/3).

Deliberately bounded scalar rational ReLU networks, closed balls clipped to the
declared domain and class-1 ties. Established set erosion, not a new algorithm,
training/import, high-dimensional certificate, accuracy/probability estimate,
benchmark or scaling claim. Browser evidence requires independent Python
acceptance. [Exact contract and finite-partition proof](https://github.com/midya8/hingelab/blob/main/RADIUS.md).


## RewriteLab: a shortcut can need a larger detour

[Live inspector](https://midya8.github.io/rewritelab/) · [Source](https://github.com/midya8/rewritelab) · [Case study](https://github.com/midya8/Midya-portfolio/blob/main/projects/rewritelab.md)

Complete bounded arithmetic-rewrite closures, shortest proofs and a separate exhaustive polynomial-semantic optimum. Five nodes block a real simplification; seven unlock its three-rewrite bridge. A weighted control still exposes a cost-7 semantic gap at the seven-node limit. Every reachable proof and semantic candidate is inspectable, with editable occurrence costs and independently checkable JSON evidence.

25 exact source files, 11 Python tests across four versions, three Node/Chrome tests, 72 complete cross-language reports, installed-wheel reproduction and full deployed behavior checks. Separate grammar/rule enumeration and exact degree-bounded interpolation check the evidence. Explicit finite graph, not an e-graph, tensor compiler, floating-point proof or runtime-speedup claim. [Contract](https://github.com/midya8/rewritelab/blob/main/CONTRACT.md) · [Sources](https://github.com/midya8/rewritelab/blob/main/SOURCES.md).


## RewriteLab budget barriers: when fitting is not reaching

[Live budget-barrier atlas](https://midya8.github.io/rewritelab/barriers.html) · [Source](https://github.com/midya8/rewritelab) · [Exact filtration contract](https://github.com/midya8/rewritelab/blob/main/BARRIERS.md) · [Merged change](https://github.com/midya8/rewritelab/pull/2)

The atlas retains every 3/5/7-node closure through the chosen cap and every
polynomial-equivalent candidate. It separates the first budget that fits both
source and target from the first budget that admits a rewrite proof. Each
blocked lower level has a complete closure obstruction, and each first-reachable
level has a shortest proof within that level. Source-too-large and
target-too-large are not mislabeled as blocked.

For `x*(1+1) -> x+x`, first fitting is 5, first reachable is 7, extra budget is
2 and shortest distance is 3. Thirteen of its 213 cap-7 semantic candidates
need a larger bridge. The weighted constant product is still a counter-control:
five of six candidates remain unreached through seven nodes. Leaf `x` first
has allowed budget 3, but its zero-step path has actual peak 1. Null means
not reached through the cap, not impossible at every larger budget.

Independent verification first checks every nested full closure with separate
generic rule templates and exact 25-point degree-bounded signatures, then
independently enumerates candidates and budget labels. It imports no atlas
generator, forward search or coefficient maps; the syntax/size/cost contract
and base independent verifier are shared. A test-only heap directly minimizes
peak-node labels through the independent template graph for all semantic
candidates of six sources.

Fresh public feature/main reproduction: 35 files source-exact; 20 tests on
Python 3.10-3.13; six Node/actual-Chrome tests; installed eight controls per
family through module and console outside the checkout, with forgeries rejected.
36 complete Python/JS atlases compare 13,016 candidate rows and 13,745 nested
proof rows. Chrome checks 25 atlases and every 3,844 candidate selection, all
five level states, three widths, export, cap changes and invalidation. Base
72 full cross-language reports and all base browser checks remain intact.
Feature/PR/main CI and Pages pass; nine deployed assets match main and 57
feature/main/live screenshots match without masks.

This is the least allowed budget in a fixed small grammar, not a new minimax
algorithm, e-graph, learned policy, tensor compiler or runtime benchmark. A
shortest proof at that budget need not be globally shortest across larger
budgets, and its peak need not equal the allowed budget. Reachable and semantic
optima each fall or stay fixed as the budget grows; their difference need not.
No result above the cap or IEEE floating-point equivalence is claimed.


## RewriteLab cost atlas: one graph, every cost tradeoff

[Live cost-weight atlas](https://midya8.github.io/rewritelab/weights.html) · [Source](https://github.com/midya8/rewritelab) · [Exact weight-box contract](https://github.com/midya8/rewritelab/blob/main/WEIGHTS.md) · [Merged change](https://github.com/midya8/rewritelab/pull/3)

A fixed rewrite graph can have different cheapest answers under different
operator costs. This atlas keeps all 512 positive integral (+, multiplication,
leaf) weight triples in 1..8. Every semantic expression is retained in an exact
operation-count group, together with its complete reachable subset. Every
outcome retains exact optimum ties and the cost gap. The accessible 8×8 slice
changes leaf cost without running another search; all optimum ties and group
members remain selectable.

For constant four, product vector (2 additions, 1 multiplication, 4 leaves)
competes with addition-only vector (3, 0, 4). They tie exactly when addition
and multiplication costs agree. There are 224 positive-gap triples, 288 with
zero gap and 64 ties. Each semantic group wins at 288 triples because ties
credit both, so win counts are not a probability partition. By contrast, the
five-node bridge source is strictly dominated by blocked `x+x` and has a gap
at all 512 triples. No crossover is invented for a dominated pair.

The independent checker validates a full unit-cost closure, counts canonical
syntax symbols separately from the generator's recursive tree traversal, and
rebuilds every group, reachable subset, weight outcome, tie, gap, dominator
and win count. Shared syntax and base independent closure checking are named
explicitly. All 512 ordinary optimize reports, including full expanded
expression ties, are cross-checked for both the constant crossover and the
blocked bridge. Strict positive-weight dominance is kept separate from zero
wins inside this finite box; absence of a box win is not a global impossibility.

Fresh public feature and main clones match all 45 source files and tracked
paths. There are 27 Python tests across 3.10-3.13 and nine Node/actual-Chrome
tests. Seventeen complete Python/JS weight reports compare 8,704 outcomes and
93 groups. Chrome checks 25 weight reports, all 4,096 outcome selections and
34,570 expression selections across eight controls and three widths, plus
current-weight export, invalid-selection recovery and stale clearing. Fresh
installed module and console reproduce eight controls each for all three
families outside the checkout and reject forgeries. Base and budget-barrier
checks remain intact. Feature/PR/main CI and Pages pass; all 13 live assets
match main and all 83 feature/main/live screenshots match without masks.

Costs count tree-node occurrences, not shared subexpressions or hardware
latency. This is an exhaustive integral weight box over a fixed seven-node
maximum grammar, not a continuous parameter-region analysis, learned policy,
e-graph, tensor engine, new algorithm or compiler-speed benchmark. The exact
rational identities are not IEEE floating-point transformation licenses.
Browser evidence is independently checked only after Python accepts its JSON.
## RewriteLab continuous regions: beyond a sampled cost grid

[Live explorer](https://midya8.github.io/rewritelab/regions.html) · [Source](https://github.com/midya8/rewritelab) · [Exact region contract](https://github.com/midya8/rewritelab/blob/main/REGIONS.md) · [Merged change](https://github.com/midya8/rewritelab/pull/4)

A finite cost grid cannot prove that an expression never wins elsewhere.
This extension computes complete optimum regions over every strictly positive
addition, multiplication and leaf-cost ratio. Normalizing their sum to one
turns the parameter space into a triangle. Each group's exact halfplanes yield
reduced rational vertices, with full expression memberships and reachable
subsets retained. Semantic and reachable optima have separate regions.

Closed geometry is not a positive-cost verdict. Empty, point, segment and area
regions retain their dimensions. A boundary-only winner is not obtainable at
strictly positive costs; an interior tie point or segment can be a real winner
despite zero area. Shared edges and vertices belong to every tied group. Area
is not a probability. The zero-cost boundary closes the diagram, not the
optimizer's request domain.

The generator uses exact rational polygon clipping. A separate checker instead
constructs feasible supporting-line intersections, counts canonical syntax
symbols and validates the complete nested unit-cost closure. It reconstructs
every group, vertex, dimension and positive-feasibility flag without importing
the generator, clipping or recursive count traversal. Shared syntax and base
independent closure checking are disclosed. JavaScript uses BigInt rational
arithmetic; float coordinates are only a display layer over exact vertex text.

Fresh public feature and main source match all 54 files and tracked paths.
Thirty-five Python tests pass on each of 3.10-3.13, alongside eight Node engine
and four actual-Chrome tests. Seventeen Python/JavaScript region reports agree
on 93 groups and 215 vertices. Independent tests cover all 36 three-node
sources, 500 random vector sets, exact degenerate/interior/boundary cases,
all eight controls at all 512 old grid points, 64 outside-grid positive points,
and forged geometry, types, closure and membership. Installed module and console
reproduce eight controls each in all four families outside the checkout and
reject forgeries.

Chrome checks 25 region reports, all 4,096 point selections and 34,570 expression
selections across eight controls and three widths, complete rational vertex
text, both diagrams per group, export, invalid recovery, stale clearing and
outside-grid prices. All previous inspector, barrier and weight-box checks are
retained. Feature/PR/main CI and Pages pass. All 16 deployed assets match main;
all 111 feature/main/live screenshots match exactly without masks.

The continuous cost domain does not enlarge the expression grammar: fixed
3/5/7-node budgets, rational identities and complete ordered trees still apply.
Costs count tree occurrences, not shared subexpressions or hardware latency.
No new algorithm, e-graph, learned costs, tensor engine, compiler-speed benchmark
or IEEE floating-point transformation license is claimed. Enumeration remains
exponential. Browser evidence is independently checked only after the Python
region checker accepts its complete JSON.
