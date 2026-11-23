# mizan-gate-demo

A live demo of Mizan Gate, a CI check that fails a pull request when an AI agent becomes more confident and wrong. All data here is synthetic and the agent is fake: `data/results.jsonl` holds one line per eval item (`id`, `confidence` from 0 to 1 or `null` for "I don't know", `correct`). Pushes to `main` set the baseline; each pull request is compared against it.
