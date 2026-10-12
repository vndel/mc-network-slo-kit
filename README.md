# mc-network-slo-kit

Service-level indicators for player-facing Minecraft networks. Measure connection success and latency from independent probes; TPS is a backend signal, not a complete player experience metric.

## Example objectives
Set objectives from observed baselines and communicate exclusions. Separate proxy acceptance, authentication, backend join, and in-game tick health. Use multi-window burn-rate alerts rather than paging on a single failed probe.

Do not label a service 99.9% available until probes, maintenance policy, and enough historical data support that claim. MIT licensed.
