## Features

- Six tools over stdio: `orca_list_runs`, `orca_show_run`, `orca_graph`, `orca_checkpoints`, `orca_replay`, `orca_compare`
- Reads runs recorded **outside** the agent process, at the HTTP boundary to the model provider, so the captured run is the program as it really ran rather than an instrumented variant
- Causal edges are labelled `recorded` (the recorder observed it) or `inferred` (derived at query time from a named rule), so an agent can keep the two claims apart instead of merging them into one confident sentence
- Offline replay: the agent's own code, control flow and tool dispatch execute for real while the model's answers come from the trace — no provider contacted, no key, no tokens spent
- Model comparison forks one run from a checkpoint onto several models with the same files and conversation prefix, graded by a shell command's exit code

## Use Cases

- Answering "why did the agent change this file?" from the trace instead of from the agent's recollection of its own context window
- Reproducing a failure a colleague reported, without their API key and without spending tokens
- Pinning a recorded run as a CI regression test for instruction, tool-schema or orchestration changes
- Auditing which files and shell commands a past run actually touched, including ones nobody mentioned

## Comparison to Tracing and Observability Servers

Tracing servers expose spans an SDK emitted during the run; this exposes the verbatim request and response bytes captured at the provider boundary, plus a replay of the run. The difference shows up in what each can answer: a span tree says what was instrumented, while a byte-exact recording can be re-executed and diffed, and reports drift rather than normalizing it away.

## Limitations

- Blocked egress means model-provider egress, **not** network isolation — replay re-executes the recorded tool calls for real, so it is not a sandbox
- A matching replay is not a determinism result: the model is not re-asked, its recorded answers are served back
- Only reads runs already captured by `orca record ...`; with no recordings the server returns an empty list rather than failing

## Pricing

Free and open source, Apache-2.0.
