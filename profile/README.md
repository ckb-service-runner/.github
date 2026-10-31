### Run a CKB full node. Let it do more.

**CKB Service Runner (CSR)** installs beside your [CKB](https://github.com/nervosnetwork/ckb) full node in five minutes and gives it:

- 📊 **a dashboard**: sync, peers, resources, your node on the network map
- 🏆 **a public ranking** of independent full nodes: uptime, sync, age, diversity
- ⚙️ **a service runtime** (testnet now, mainnet from 1.x): run decentralised services in a CKB-VM sandbox and earn tips

```sh
curl -fLO https://raw.githubusercontent.com/ckb-service-runner/ckb-service-runner/main/scripts/install.sh
sudo bash install.sh
```

| Repository | What it is |
|---|---|
| [ckb-service-runner](https://github.com/ckb-service-runner/ckb-service-runner) | the runner: install this on your node |
| [csr-network-monitor](https://github.com/ckb-service-runner/csr-network-monitor) | probes runners, publishes the ranking and a weekly stat cell |
| [runsimulation-testnet](https://github.com/ckb-service-runner/runsimulation-testnet) | creates test jobs on testnet |

🌍 **Live network:** [csr-monitor.chainsolution.net](https://csr-monitor.chainsolution.net) · 💬 [Telegram](https://t.me/ckbrunner) · 📖 [Background on Nervos Talk](https://talk.nervos.org/t/a-revenue-layer-for-ckb-nodes/10734)

Open source (MIT). Testnet first. No change to CKB or its consensus.
