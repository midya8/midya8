## Hi, I'm Midya

I'm a Toronto-based technologist with 12+ years across technology, financial
services and telecommunications. Lately I'm building with large language models,
agentic systems and workflow automation.

### Projects

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
table for any SLO window). CLI and
importable
library, 210 unit tests,
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
response-size (bandwidth) analysis, and
Markdown incident
reports with spike windows and before/after deploy comparisons. Status and
time-window filters scope every statistic. Parses nginx/Apache combined and
JSON logs with per-line auto-detection, standard library only,
200 unit tests.

**[flowkit](https://github.com/midya8/flowkit)**

Dependency-free workflow runner: JSON-defined DAGs of shell commands with
retries and exponential backoff, per-attempt timeouts, fail-fast or
continue-on-error semantics, parallel execution of independent steps,
conditional steps and subset runs, and a
dry-run plan mode. Layered flow/step environment variables interpolate into
commands with a strict pre-run check, and run reports show captured output
tails (text or JSON, optionally written to a report file). Definitions are
validated up front (duplicates, dangling dependencies, cycles) and run in
deterministic topological order. Standard
library only, 92 unit tests, CI across Python 3.10-3.13.

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
