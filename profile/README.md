# Azure Scout

**Open-source Azure deployment planning platform** — real-time SKU availability, zone mappings, deployment confidence scoring, and AI-powered planning.

az-scout aggregates five live Azure ARM signals (SKU availability, vCPU quotas, Spot Placement Scores, retail pricing, and logical-to-physical Availability Zone mappings) into a composite **Deployment Confidence Score**, helping teams answer: *"Can I actually deploy this workload in this region, right now?"*

<div align="center">

### 🔭 [az-scout](https://github.com/az-scout/az-scout)

FastAPI backend · D3.js visualization · MCP server · AI chat assistant · Plugin system

![GitHub Release](https://img.shields.io/github/v/release/az-scout/az-scout?label=release)
![PyPI](https://img.shields.io/pypi/v/az-scout?label=pypi)
![License](https://img.shields.io/github/license/az-scout/az-scout)

```
uvx az-scout
```

📖 [Documentation](https://az-scout.com) · 🐳 [Container image](https://ghcr.io/az-scout/az-scout)

</div>

---

### Plugins

<!-- PLUGINS-START -->
| Repository | Description | Release |
|---|---|---|
| [az-scout-plugin-aks-placement-advisor](https://github.com/az-scout/az-scout-plugin-aks-placement-advisor) | AKS Placement Advisor — evaluates and recommends VM SKUs for AKS node pools. | ![GitHub Release](https://img.shields.io/github/v/release/az-scout/az-scout-plugin-aks-placement-advisor?label=) |
| [az-scout-plugin-avs-rvtools-analyser](https://github.com/az-scout/az-scout-plugin-avs-rvtools-analyser) | AVS migration risk analysis from RVTools Excel exports. | ![GitHub Release](https://img.shields.io/github/v/release/az-scout/az-scout-plugin-avs-rvtools-analyser?label=) |
| [az-scout-plugin-avs-sku](https://github.com/az-scout/az-scout-plugin-avs-sku) | Azure VMware Solution (AVS) SKU exploration. | ![GitHub Release](https://img.shields.io/github/v/release/az-scout/az-scout-plugin-avs-sku?label=) |
| [az-scout-plugin-batch-sku](https://github.com/az-scout/az-scout-plugin-batch-sku) | Azure Batch SKU availability checker across multiple regions. | ![GitHub Release](https://img.shields.io/github/v/release/az-scout/az-scout-plugin-batch-sku?label=) |
| [az-scout-plugin-compare-cost-between-regions](https://github.com/az-scout/az-scout-plugin-compare-cost-between-regions) | Compare Azure costs between regions using Cost Management exports. | ![GitHub Release](https://img.shields.io/github/v/release/az-scout/az-scout-plugin-compare-cost-between-regions?label=) |
| [az-scout-plugin-latency-stats](https://github.com/az-scout/az-scout-plugin-latency-stats) | Inter-region latency statistics with D3.js graph visualization. | ![GitHub Release](https://img.shields.io/github/v/release/az-scout/az-scout-plugin-latency-stats?label=) |
| [az-scout-plugin-network-cost](https://github.com/az-scout/az-scout-plugin-network-cost) | Azure VNet peering cost estimation between regions. | ![GitHub Release](https://img.shields.io/github/v/release/az-scout/az-scout-plugin-network-cost?label=) |
| [az-scout-plugin-odcr-coverage](https://github.com/az-scout/az-scout-plugin-odcr-coverage) | ODCR coverage analysis — identify VMs at risk of allocation failure. | ![GitHub Release](https://img.shields.io/github/v/release/az-scout/az-scout-plugin-odcr-coverage?label=) |
| [az-scout-plugin-regions-cheapest](https://github.com/az-scout/az-scout-plugin-regions-cheapest) | Find the cheapest Azure regions for a given VM SKU. | ![GitHub Release](https://img.shields.io/github/v/release/az-scout/az-scout-plugin-regions-cheapest?label=) |
| [az-scout-plugin-strategy-advisor](https://github.com/az-scout/az-scout-plugin-strategy-advisor) | Multi-region capacity strategy recommendation engine. | ![GitHub Release](https://img.shields.io/github/v/release/az-scout/az-scout-plugin-strategy-advisor?label=) |
<!-- PLUGINS-END -->
