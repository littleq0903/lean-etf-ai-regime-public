# lean-etf-ai-regime-public

Public delivery repository for the validated ETF risk-regime JSON feed.

QuantConnect should read:

```text
https://littleq0903.github.io/lean-etf-ai-regime-public/regime.json
```

This repository should contain only static files required by QuantConnect and GitHub Pages. The private builder repository generates, validates, and syncs `docs/regime.json` here.

The AI output is not a trading system. It only provides a validated risk multiplier. ETF selection, sizing, and orders remain deterministic inside QuantConnect LEAN.
