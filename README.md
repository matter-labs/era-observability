# Era Observability

This repository contains json sources for Grafana dashboards that are used to observe `ZKSync Era` as well as can be used for any other hyperchain deployment. Dashboards are regularly updated.   

## How to use

This section goes through a simple setup for a local deployment.

1. Setup your local environment and start services as described [here](https://github.com/matter-labs/zksync-era/blob/main/docs/guides/launch.md). `zk init` and `zk server` is enough for the matter of this exercie; 
2. Setup local Prometheus + Grafana, for example using [Dockprom](https://github.com/stefanprodan/dockprom);
3. Open the Grafana UI (`http://127.0.0.1:3000/` if you used `Dockprom`) and import the dashboards via regular json import;
4. (Optionally) run the integration tests via `zk test i server` to generate some transactions.

Voila! You should see some data displayed in Grafana now.

If some charts do not work please raise an issue in this repo. 

## Dashboards

* **General** - one pager high level overview of L1/L2 blockchains and L2 APIs;
* TODO: add others