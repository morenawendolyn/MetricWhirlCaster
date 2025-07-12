# MetricWhirlCaster

MetricWhirlCaster collects and dispatches metrics in real time, rotating between multiple backends like Prometheus, Graphite, and Loki based on context or traffic pattern.

## Features
- Rotates backend targets on the fly.
- Supports custom routing logic and fallback.
- Pluggable metric formatters.
- CLI and daemon mode available.

## Usage
```bash
git clone https://github.com/your-org/MetricWhirlCaster.git
cd MetricWhirlCaster
python whirlcaster/collector.py metrics/input.jsonl
