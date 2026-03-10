# az-scout

**Open-source Azure deployment planning platform** — real-time SKU availability, zone mappings, deployment confidence scoring, and AI-powered planning.

az-scout aggregates five live Azure ARM signals (SKU availability, vCPU quotas, Spot Placement Scores, retail pricing, and logical-to-physical Availability Zone mappings) into a composite **Deployment Confidence Score**, helping teams answer: *"Can I actually deploy this workload in this region, right now?"*

## Core

| | | |
|---|---|---|
| ⭐ **[az-scout](https://github.com/az-scout/az-scout)** | FastAPI backend, D3.js frontend, MCP server, AI chat assistant, plugin system | ![GitHub Release](https://img.shields.io/github/v/release/az-scout/az-scout?label=release) |

## Plugins

| Repository | Description | Release |
|---|---|---|
| [az-scout-plugin-strategy-advisor](https://github.com/az-scout/az-scout-plugin-strategy-advisor) | AI-powered deployment strategy advisor | ![GitHub Release](https://img.shields.io/github/v/release/az-scout/az-scout-plugin-strategy-advisor?label=) |
| [az-scout-plugin-batch-sku](https://github.com/az-scout/az-scout-plugin-batch-sku) | Azure Batch SKU availability | ![GitHub Release](https://img.shields.io/github/v/release/az-scout/az-scout-plugin-batch-sku?label=) |
| [az-scout-plugin-avs-sku](https://github.com/az-scout/az-scout-plugin-avs-sku) | Azure VMware Solution SKU availability | ![GitHub Release](https://img.shields.io/github/v/release/az-scout/az-scout-plugin-avs-sku?label=) |
| [az-scout-plugin-latency-stats](https://github.com/az-scout/az-scout-plugin-latency-stats) | Inter-region network latency statistics | ![GitHub Release](https://img.shields.io/github/v/release/az-scout/az-scout-plugin-latency-stats?label=) |

## Quick start

```bash
pip install az-scout && az-scout
```

📖 [Documentation](https://az-scout.github.io/az-scout/) · 📦 [PyPI](https://pypi.org/project/az-scout/) · 🐳 [Container image](https://ghcr.io/az-scout/az-scout)
